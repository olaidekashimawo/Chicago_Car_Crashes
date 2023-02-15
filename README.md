# Chicago_Car_Crashes
Flatiron Phase III project : Build a classifier to predict the primary contributory cause of a car accident. Use the model to assess severity of the accident
# Data 
Data from Chicago car accidents was analyzed, and several models were created including logistic regression, KNN, Decision Tree, and Random Forest.It consist of crashes from 2022-2023 From these data,
# Objective 
we will develop a models to better understand the causes of car crashes requiring EMS or EMT response.

|  	| FEATURES 	| DESCRIPTION 	|
|---	|---	|---	|
| 0 	| CRASH_RECORD_ID 	| This number can be used to link to the same crash in the Vehicles and People datasets. 	|
| 1 	| POSTED_SPEED_LIMIT 	| Posted speed limit, as determined by reporting officer 	|
| 2 	| WEATHER_CONDITION 	| Weather condition at time of crash, as determined by reporting officer 	|
| 3 	| LIGHTING_CONDITION 	| Light condition at time of crash, as determined by reporting officer 	|
| 4 	| FIRST_CRASH_TYPE 	| Type of first collision in crash 	|
| 5 	| ALIGNMENT 	| Street alignment at crash location, as determined by reporting officer 	|
| 6 	| ROADWAY_SURFACE_COND 	| Road surface condition, as determined by reporting officer 	|
| 7 	| ROAD_DEFECT 	| Road defects, as determined by reporting officer 	|
| 8 	| CRASH_TYPE 	| A general severity classification for the crash. <br>Can be either Injury and/or Tow Due to Crash or No Injury / Drive Away 	|
| 9 	| DAMAGE 	| A field observation of estimated damage. 	|
| 10 	| PRIM_CONTRIBUTORY_CAUSE 	| The factor which was most significant in causing the crash, as determined by officer judgment 	|
| 11 	| SEC_CONTRIBUTORY_CAUSE 	| The factor which was second most significant in causing the crash, as determined by officer judgment 	|
| 12 	| NUM_UNITS 	| Number of units involved in the crash. A unit can be a motor vehicle,<br> a pedestrian, a bicyclist, or another non-passenger roadway user. <br>Each unit represents a mode of traffic with an independent trajectory 	|
| 13 	| MOST_SEVERE_INJURY 	| Most severe injury sustained by any person involved in the crash 	|
| 14 	| CRASH_DAY_OF_WEEK 	| The day of the week component of CRASH_DATE (Sun=1, Mon=2, Tue=3, Wed=4, Thu=5, Fri=6, Sat=7) 	|
| 15 	| UNIT_NO 	| A unique ID for each unit within a specific crash report. 	|
| 16 	| VEHICLE_TYPE 	| The type of vehicle, if relevant 	|
| 17 	| EXCEED_SPEED_LIMIT_I 	| Indicator of whether the unit was speeding, as determined by the reporting officer 	|
| 18 	| FIRST_CONTACT_POINT 	|  	|
| 19 	| PERSON_ID 	| A unique identifier for each person record. IDs starting with P indicate passengers.<br> IDs starting with O indicate a person who was not a passenger in the vehicle<br> (e.g., driver, pedestrian, cyclist, etc.). 	|
| 20 	| PERSON_TYPE 	| Type of roadway user involved in crash 	|
| 21 	| VEHICLE_ID 	| The corresponding CRASH_UNIT_ID from the Vehicles dataset. 	|
| 22 	| SEAT_NO 	| Code for seating position of motor vehicle occupant: 1= driver, 2= center front, <br>3 = front passenger, 4 = second row left, 5 = second row center, 6 = second row right, <br>7 = enclosed passengers, 8 = exposed passengers, 9= unknown position, 10 = third row left, <br>11 = third row center, 12 = third row right 	|
| 23 	| SEX 	| Gender of person involved in crash, as determined by reporting officer 	|
| 24 	| AGE 	| Age of person involved in crash 	|
| 25 	| SAFETY_EQUIPMENT 	| Safety equipment used by vehicle occupant in crash, if any 	|
| 26 	| AIRBAG_DEPLOYED 	| Whether vehicle occupant airbag deployed as result of crash 	|
| 27 	| EJECTION 	| Whether vehicle occupant was ejected or extricated from the vehicle as a result of crash 	|
| 28 	| INJURY_CLASSIFICATION 	| Severity of injury person sustained in the crash 	|
