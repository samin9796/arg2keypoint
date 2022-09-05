## Argument-Keypoint Mapping for Automatic Argument Summarization

In this work, we walk through running our experiments on the Argument-to-keypoints task with Approach 1 and Approach 2. The Github repo is still being prepared for reproducibility and easy understanding.

### Data
In this project we use the ArgKP dataset for Argument-to-keypoint summarization task. 
The datasets for cross/in-domain are in the Data folder.

### Baseline
```BERT/T5_baseline.ipynb``` are the baseline of this project.
### Approach 1
```Approach1_T5_base_OpenPrompt.ipynb``` contains all the codes for different experiments of the approach 1. 

This notebook contains five different templates that four of them are commented out and only one of them should be used in each experiment.

To reproduce the results of **zero-shot** experiments, the **Training** step must be skipped. 

To reproduce the results of **few-shot** experiments, the **few-shot train set** should be imported. 

To reproduce the results of different **subset** experiments, the **subset train set** should be imported.
### Approach 2
The approach_2 folder contains the files about generation intermediary texts using T5-small and BART large (```BART/T5_approach_2.ipynb```) and match classification using Naive Bayes, SVM, Decision Tree (```machine learning classifiers.ipynb```) and BERT-base (```classification_BERT.ipynb```).


