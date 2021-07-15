# PARKINSON'S DISEASE PREDICTION USING XG BOOSTER

# Analysis
  - This project is based on analysing the dataset of tests done for parkinson disease of 
UCI Repository. The dataset contains 195 records of people with 23 different attributes 
which contain biomedical measurements. We try to analyze the dependancies of different 
factors that are required to predict whether the person has parkinson’s disease or not.The 
data used in this study were gathered from 188 patients with PD (107 men and 81 women) 
with ages ranging from 33 to 87 (65.1Â±10.9) at the Department of Neurology in 
CerrahpaÅŸa Faculty of Medicine, Istanbul University. The control group consists of 64 
healthy individuals (23 men and 41 women) with ages varying between 41 and 82 
(61.1Â±8.9). During the data collection process, the microphone is set to 44.1 KHz and 
following the physicianâ€™s examination, the sustained phonation of the vowel /a/ was 
collected from each subject with three repetitions.
  - In this the status values which are binary (sigmoid values) , Health status of the 
subject (one) - Parkinson's, (zero) – healthy.
 - In this model we used to train the different attributes (labels) using desicion 
tree based ensemble machine learning algorithm that uses gradient boosting framework.

# Algorithm used
 - XG Boost algorithm

# Accuracy
 -  97.43589743589743

 # Conclusion
  - The person having HNR value greater than 5 mostly suffers from parkinsons 
disease. The above algorithm predicts at an accuracy of 97.43 , whereas 
other algorithms like SVM predicts at an accuracy of more than 97
