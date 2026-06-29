# blurb-classification-thesis
This repository contains the code used for my thesis project for the Master Applied Data Science at Utrecht University.

## The code files contain the following: /n
**1 Data cleaning exploration and splitting dataset to hand label (blurbs together)**/n
Notebook 1a: Data cleaning  part 1/n
Notebook 1b: Data exploration/n
Notebook 1c: Data cleaning part 2 + sampling sub dataset to manually label/n
Notebook 1d: Splitting the manually labeled dataset in in train/validation/test sets/n/n

**2. Approach 1: Feature based classification**/n
Notebook 2a: Creating features for the manually labeled sets and 25 k sentences of the unlabeled data/n
Notebook 2b: Fitting/tuning/saving feature based sentence classifier (Model 2)/n
Notebook 2c: Evaluating feature based sentence classifier (Model 2) on test set/n

**3. Approach 2: Finetuning RobBERT model with manually labeled data only**/n/n
Notebook 3a: Training/tuning/saving RobBERT model (Model 2)/n
Notebook 3b: Evaluating RobBERT model on the test set/n/n

**4. Approach 3: Fine tuning RobBERT models with manually labeled data + weak labels**/n
Notebook 4a: Fitting/tuning/saving feature based labeling model/n
Notebook 4b: Creating weak labels + apply quality filter/n
Notebook 4c/4d/4e: Training/tuning/saving the three RobBERT models (Model 3a/3b/3c)/n
Notebook 4f: Evaluating the RobBERT models using weakly labeled data on the test set/n
Notebook 4g : Evaluating labeling model on test set (label quality check)/n/n

Notebook 5 : Deeper insight in model 2 and model 3b (probability distribution plots, word attribution, and misclassifications) 

