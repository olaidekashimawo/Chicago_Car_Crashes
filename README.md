# Chicago_Car_Crashes
Flatiron Phase III project : Build a classifier to predict the primary contributory cause of a car accident. Use the model to assess severity of the accident
Data from Chicago car accidents was analyzed, and several models were created including logistic regression, KNN, Decision Tree, and Random Forest.It consist of crashes from 2022-2023 From these data.
### Data 
The datasets was from the City of Chicago. There were three datasets that we observed, "Traffic Crashes - Crashes", "Traffic Crashes - Vehicle", and "Traffic Crashes - People" wasmerged them into one database.

Column names and descriptions can be found here;

Traffic Crashes - Crashes: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

Traffic Crashes - Vehicle: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3

Traffic Crashes - People: https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d

### Objective 
we will develop a models to better understand the causes of car crashes requiring EMS or EMT response.

### Some of the features and its description

|  	| FEATURES 	| DESCRIPTION 	|
|---	|---	|---	|
| 0 	| CRASH_RECORD_ID 	| This number can be used to link to the same crash in the Vehicles and People datasets. 	|
| 2 	| WEATHER_CONDITION 	| Weather condition at time of crash, as determined by reporting officer 	|
| 3 	| LIGHTING_CONDITION 	| Light condition at time of crash, as determined by reporting officer 	|
| 4 	| FIRST_CRASH_TYPE 	| Type of first collision in crash 	|
| 5 	| ALIGNMENT 	| Street alignment at crash location, as determined by reporting officer 	|
| 6 	| ROADWAY_SURFACE_COND 	| Road surface condition, as determined by reporting officer 	|
| 7 	| ROAD_DEFECT 	| Road defects, as determined by reporting officer 	|
| 8 	| CRASH_TYPE 	| A general severity classification for the crash. <br>Can be either Injury and/or Tow Due to Crash or No Injury / Drive Away 	|
| 10 	| PRIM_CONTRIBUTORY_CAUSE 	| The factor which was most significant in causing the crash, as determined by officer judgment 	|
| 13 	| MOST_SEVERE_INJURY 	| Most severe injury sustained by any person involved in the crash 	|
| 14 	| CRASH_DAY_OF_WEEK 	| The day of the week component of CRASH_DATE (Sun=1, Mon=2, Tue=3, Wed=4, Thu=5, Fri=6, Sat=7) 	|
| 16 	| VEHICLE_TYPE 	| The type of vehicle, if relevant 	|
| 20 	| PERSON_TYPE 	| Type of roadway user involved in crash 	|
| 21 	| VEHICLE_ID 	| The corresponding CRASH_UNIT_ID from the Vehicles dataset. 	|
| 23 	| SEX 	| Gender of person involved in crash, as determined by reporting officer 	|
| 24 	| AGE 	| Age of person involved in crash 	|
| 25 	| SAFETY_EQUIPMENT 	| Safety equipment used by vehicle occupant in crash, if any 	|
| 26 	| AIRBAG_DEPLOYED 	| Whether vehicle occupant airbag deployed as result of crash 	|
| 28 	| INJURY_CLASSIFICATION 	| Severity of injury person sustained in the crash 	|
 #Obtain:

### Extracting data from the following files;
* Crash=https://data.cityofchicago.org/resource/85ca-t3if.csv
* Vehicle=https://data.cityofchicago.org/resource/68nd-jvt3.csv
* Person=https://data.cityofchicago.org/resource/u6pd-qa9d.csv:
### Data Cleaning
* Look into your data.
* Analyze the merge data.
* Understanding null values and deciding how to eliminate them
* Adding useful data and changing data kinds
* removing redundant and duplicate columns
* Inpecting the columns
* Binning and Mapping

### EDA 
* Creating visualizations to understand data 
### Preprocessing 
* we ran a train-test-split  to prevent data leakage
* Subsampled the dataset
* Modeled logistic regression, KNN, decision trees, bagging, and random forest.
* Grid-search each model for optimized parameters.
### Class Imbalance (SMOTE)

### Result 
Model
The following models were tested which included logistic regression, k-nearest neighbors, decision trees, Random forest .
* Random Forest Classifier returned an accuracy rate of 83% In this report, the precision for class 0 is 0.85, which means that out of all the predictions the model made for class 0, 85% were correct. The precision for class 1 is 0.74, which means that out of all the predictions the model made for class 1, 74% were correct.

* Recall is the ratio of true positive predictions to the total number of actual positive cases in the dataset. In this report, the recall for class 0 is 0.96, which means that out of all the actual cases of class 0 in the dataset, 96% were correctly identified by the model. The recall for class 1 is 0.42, which means that out of all the actual cases of class 1 in the dataset, only 42% were correctly identified by the model.

* F1-score: F1-score is the harmonic mean of precision and recall, and is a measure of the overall accuracy of the model. In this report, the F1-score for class 0 is 0.90, while the F1-score for class 1 is 0.53.

* The overall accuracy and weighted average metrics are higher for the Random Forest model, indicating better performance overall

### Recomendation
I recommend the following because the Random classifier has an 83% accuracy rate;
Increase enforcement of traffic laws and regulations, particularly with respect to distracted driving and failure to maintain a proper lane.
Installation of physical barriers between opposing lanes of traffic, wider lanes, and better marking of lanes and road edges.
Encourage the use of advanced driver assistance systems (ADAS) for instance blind spot detection, lane departure warning, and automatic emergency braking. 

### Next Step
To further analysis to better understand the factors that contribute to crashes; This could involve analyzing
crash data, conducting simulated driving studies, and
analysis driver behavior and roadway design.
location of the crash
