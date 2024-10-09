# Non-Intrusive-Anaemia-Detection

I was provided with a dataset obtained from a hospital wherein the fingernail images of several patients were collected with the label of whether or not they had anaemia. All 10 fingernails of every patient was recorded for about 172 patients. 

The dataset hasn't been uploaded due to confidentiality reasons
There were a lot of bad samples due to lack of a proper system for finger placement and camera angle due to which a lot of cropping and filtering had to be done manually by me

The dataset was heavily skewed towards non-anaemic patients because only 14 anaemic cases were included hence the required MAE for haemoglobin prediction could not be achieved. I used SMOTE to try to mitigate the offset in the classification task
