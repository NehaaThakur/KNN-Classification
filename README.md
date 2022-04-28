# KNN-Classification
Used KNN classification to anlayse individuals in low and high-income groups based on census data that had attributes of US citizens like occupation, education, gender, race to name a few. 
The objective of this project is to fit to predict whether an individual earns more than USD 50,000 
(50K) or less in a year using the 1994 US Census Data. The target feature has two classes defined as 
"<=50K" and ">50K" respectively. The full dataset contains about 45K observations.
The dataset provided has 15 columns and 48841 rows. Out of the 15 columns, 14 columns represent 
the features or attributes that were used for classification, while the last column (income) is the target 
variable. The table below provides a brief description of the attributes in the dataset.
Feature Variable Type Description
Age Numeric Age of individual starting from 17 and above 
Workclass Categorical Employment type of the individual: Private, Self-emp-not-inc, 
Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, 
Never-worked
Fnlwgt Final weight. This is the number of people the census believes 
the entry represents.
Education Categorical Highest level of education achieved by an individual: Bachelors, 
Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assocvoc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th6th, Preschool.
Education_no Numeric The number of years spent in education
Marital_status Categorical Married-civ-spouse, Divorced, Never-married, Separated, 
Widowed, Married-spouse-absent, Married-AF-spouse
Occupation Categorical Type of occupation: Tech-support, Craft-repair, Other-service, 
Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, 
Machine-op-inspct,Adm-clerical, Farming-fishing, Transportmoving, Priv-house-serv, Protective-serv, Armed-Forces.
Relationship Categorical Represents what this individual is relative to others; Wife, Ownchild, Husband, Not-in-family, Other-relative, Unmarried.
Race Categorical White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black
NEAREST NEIGHBORS CLASSIFICATION: INCOME CENSUS
Sex Categorical Female, Male.
Capital_gain Numeric Increase in a capital asset's value realized when the asset is sold
Capital_loss Numeric Capital asset is sold for less than the price it was purchased for
Hours_per_week Numeric The hours an individual has reported to work per week
Native_country Categorical country of origin for an individual
Label Type Description
Income Numeric whether or not an individual makes more than $50,000 annually
