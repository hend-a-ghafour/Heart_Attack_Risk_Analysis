# Heart_Attack_Risk_Analysis

## Dataset Description:
This dataset provides a comprehensive array of features relevant to heart health and lifestyle choices, encompassing patient-specific details such as age, gender, cholesterol levels, blood pressure, heart rate, and indicators like diabetes, family history, smoking habits, obesity, and alcohol consumption. Additionally, lifestyle factors like exercise hours, dietary habits, stress levels, and sedentary hours are included. Medical aspects comprising previous heart problems, medication usage, and triglyceride levels are considered. Socioeconomic aspects such as income and geographical attributes like country, continent, and hemisphere are incorporated.

***Source:*** [Heart Attack Risk Analysis- Kaggle](https://www.kaggle.com/competitions/heart-attack-risk-analysis/overview)
### Columns:
0. ***Patient ID:*** Unique identifier for each patient (7010 Patient)<br><br>
1. ***Age:*** Age of the patient (ranging from 18 to 90)<br><br>
2. ***Sex:*** Gender of the patient (Male/Female) <br><br>
3. ***Cholesterol:*** Cholesterol levels of the patient (ranging from 120 to 400 mg/dl)<br>
 > ***Note:*** <br>
 _Healthy Heart:_ under 200 <br>
 _At Risk:_ 200 to 239<br>
 _Dangerous:_ 240 & higher    
  ***Source:*** [Cholesterol Levels](https://my.clevelandclinic.org/health/articles/11920-cholesterol-numbers-what-do-they-mean) <br><br>
4. ***Blood Pressure:*** Blood pressure of the patient (systolic/diastolic)<br>
***Note:*** <br>
  _Normal Blood Pressure:_ <120 & <80<br>
  _Elevated Blood Pressure:_ 120 to 129 & <80<br>
  _Stage 1 Hypertension:_ 130 to 139 &/or 80-89<br>
  _Stage 2 Hypertension:_ 140 to <180 &/or >90 - <120<br>
  _Hypertensive Crisis:_ 180 & higher &/or 120 & higher   
  ***Source:*** [Blood Pressure](https://my.clevelandclinic.org/health/diagnostics/17649-blood-pressure) <br><br>
5. ***Heart Rate:*** Heart rate of the patient (Between 40 and 110 beats/min)<br>
    ***Note:*** <br>
    _If you want to calculate your maximum and target heart rates yourself, you can use these formulas:_ <br>
    _220 - your age = maximum._<br>
    _Maximum x 0.6 = low end of target range._<br>
    _Maximum x 0.8 = high end of target range._<br>
   ***Source:*** [Heart Rate](https://my.clevelandclinic.org/health/diagnostics/heart-rate) <br> <br>
6. ***Diabetes:*** Whether the patient has diabetes (1:Yes, 2:No)<br>
***Note:*** <br>
_Diabetes is a chronic disease that occurs either when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. Insulin is a hormone that regulates blood glucose._<br>
   ***Source:*** [Diabetes](https://www.who.int/news-room/fact-sheets/detail/diabetes#:~:text=Diabetes%20is%20a%20chronic%20disease,hormone%20that%20regulates%20blood%20glucose.) <br> <br>
7. ***Family History -*** Family history of heart-related problems (1: Yes, 0: No)<br><br>
8. ***Smoking:*** Smoking status of the patient (1: Smoker, 0: Non-smoker)<br><br>
9. ***Obesity:*** Obesity status of the patient (1: Obese, 0: Not obese) <br><br>
***Note:*** <br>
_Obesity is a chronic complex disease defined by excessive fat deposits that can impair health. Obesity can lead to increased risk of type 2 diabetes and heart disease, it can affect bone health and reproduction, it increases the risk of certain cancers. Obesity influences the quality of living, such as sleeping or moving._ <br>
***Source:*** [Obesity](https://www.who.int/news-room/fact-sheets/detail/obesity-and-overweight#:~:text=Obesity%20is%20a%20chronic%20complex,the%20risk%20of%20certain%20cancers.) <br> <br>
10. ***Alcohol Consumption:*** Level of alcohol consumption by the patient (1:Yes, 2:No)<br><br>
11. ***Exercise Hours Per Week:*** Number of exercise hours per week (Exercise hours are between 0.0024 & 19.9987 hrs/week)<br><br>
12. ***Diet:*** Dietary habits of the patient (Healthy/Average/Unhealthy)<br><br>
13. ***Previous Heart Problems:*** Previous heart problems of the patient (1: Yes, 0: No)<br><br>
14. ***Medication Use:*** Medication usage by the patient (1: Yes, 0: No)<br><br>
15. ***Stress Level:*** Stress level reported by the patient (1-10), where _1_ is the lowest & _10_ is the highest.<br><br>
16. ***Sedentary Hours Per Day:*** Hours of sedentary activity per day (between 0.0013 & 11.9993 hrs/day)<br>
***Note:*** <br>
_According to the charity [Just Stand](https://www.juststand.org/the-tools/sitting-time-calculator/), the following thresholds determine a person’s risk of developing health problems due to sitting:_ <br>
_Low risk:_ Sitting for less than 4 hours per day. <br>
_Medium risk:_ Sitting for 4–8 hours per day. <br>
_High risk:_ Sitting for 8–11 hours per day. <br>
_Very high risk:_ Sitting for more than 11 hours per day. <br>
***Source:*** [What happens to the body after sitting down for too long?](https://www.medicalnewstoday.com/articles/sitting-down-all-day#how-long-is-too-long) <br> <br>
17. ***Income -*** Income level of the patient (between 20,062 & 299,954)<br><br>
18. ***BMI -*** Body Mass Index (BMI) of the patient (between 18.0023 & 39.9936)<br>
***Note:*** <br>
_BMI will fit into one of 5 bands:_ <br>
_Underweight:_ under 18.5 <br>
_Healthy Range:_ between 18.5 and 24.9 <br>
_Overweight:_ between 25 and 29.9  <br>
_Obesity:_ between 30 and 39.9 <br>
_Severe Obesity:_ 40 & over <br>
***Source:*** [Body mass index (BMI)](https://www.nhsinform.scot/healthy-living/food-and-nutrition/healthy-eating-and-weight-management/body-mass-index-bmi/#:~:text=between%2018.5%20and%2024.9%20%E2%80%93%20This,is%20described%20as%20severe%20obesity)<br><br>
19. ***Triglycerides -*** Triglyceride levels of the patient (between 30 mg/dL & 800 mg/dL)<br>
***Notes:*** <br>
_Triglycerides are a very common kind of fat in your body. They’re in butter and other fats in food. You also make triglycerides from extra calories to use later. But high triglyceride levels can raise your risk of issues like heart attacks and strokes. Exercise and other healthy habits can bring triglyceride levels back to normal.**Normal and high triglyceride levels would be as follows:**_ <br>
_Normal (Ages between 10 & 19):_ below 90 mg/dL. <br>
_Normal (Adults):_ below 150 mg/dL. <br>
_Mild:_ 150-199 mg/dL. <br>
_Moderate:_ 200-499 mg/dL. <br>
_Severe:_ Greater than 500 mg/dL. <br>
***Source:*** [Triglycerides](https://my.clevelandclinic.org/health/articles/11117-triglycerides)<br><br>
20. ***Physical Activity Days Per Week -*** Days of physical activity per week (between 0 & 7 days/week)<br><br>
21. ***Sleep Hours Per Day -*** Hours of sleep per day (4 hrs/day & 10 hrs/day)<br><br>
22. ***Country -*** Country of the patient (20 Countries)<br><br>
23. ***Continent -*** Continent where the patient resides (6 Continents)<br><br>
24. ***Hemisphere -*** Hemisphere where the patient resides (Southern Hemisphere & Northern Hemisphere)<br><br>
25. ***Heart Attack Risk -*** Presence of heart attack risk (1: Yes, 0: No)<br><br>
