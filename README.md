# Auto-ML
## Conditions to use the Auto-ML Pipeline Tool
1) The dataset should be preprocessed.
2) Ensure that your target column is at the last column in the dataset.

## Gandharva's Constant
This is a threshold number to samrtly classify a dataset into a regression or a classification problem. Gandharva's constant can be expressed in the following manner
gandharva_constant = length(set(target_column))/len(target_column)
if gandharva_constant>=0.4 --------> regression problem
else-------> classification problem
## Dataset
Breifing about the dataset, it contains 60 feature columns and one target columns. 60 features are simply the values captured by the SONAR Machine and based on these mathematical readings, we have to predict whether the object detected by the SONAR is a rock or a war-mine planted by enemy. You can acces the dataset from the following link down below.
https://drive.google.com/drive/folders/1RGm6fiYMts1n42ja27XCuDLo0CG9DrSC?usp=sharing
# Code Files (.ipynb programs)
## Auto-ML.ipynb
The following link is the colab file link of the implementation of Auto-ML.
https://colab.research.google.com/drive/1VLNJyErVatSj_TXmatt4KL8kBWUk38qo










