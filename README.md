# Non-Intrusive-Anaemia-Detection

I was provided with a dataset obtained from a hospital in which the fingernail images of several patients were collected with the label of whether or not they had anaemia. All 10 fingernails of every patient were captured for about 172 patients. 

The task was to predict blood haemoglobin levels and classify cases as anaemic or non-anaemic

The dataset hasn't been uploaded due to confidentiality reasons
There were a lot of bad samples due to lack of a proper system for finger placement and camera angle due to which a lot of cropping and filtering had to be done manually 

The dataset was heavily skewed towards non-anaemic patients because only 14 anaemic cases were included hence the required MAE for haemoglobin prediction could not be achieved. I used Synthetic Minority Oversampling(SMOTE) to try to mitigate the offset in the classification task
