# Heart_Attack_Risk_Analysis

## Dataset Description:
This dataset provides a comprehensive array of features relevant to heart health and lifestyle choices, encompassing patient-specific details such as age, gender, cholesterol levels, blood pressure, heart rate, and indicators like diabetes, family history, smoking habits, obesity, and alcohol consumption. Additionally, lifestyle factors like exercise hours, dietary habits, stress levels, and sedentary hours are included. Medical aspects comprising previous heart problems, medication usage, and triglyceride levels are considered. Socioeconomic aspects such as income and geographical attributes like country, continent, and hemisphere are incorporated.

***Source:*** [Heart Attack Risk Analysis- Kaggle](https://www.kaggle.com/competitions/heart-attack-risk-analysis/overview)
### Columns:
0. ***Patient ID:*** Unique identifier for each patient (7010 Patient)
1. ***Age:*** Age of the patient (ranging from 18 to 90)
2. ***Sex:*** Gender of the patient (Male/Female) <br><br>
3. ***Cholesterol:*** Cholesterol levels of the patient (ranging from 120 to 400 mg/dl)<br>
  ***Note:*** <br>
  _under 200:_ Healthy Heart<br>
  _200 to 239:_ At Risk<br>
  _240 & higher:_ Dangerous    
  ***Source:*** [Cholesterol Levels](https://my.clevelandclinic.org/health/articles/11920-cholesterol-numbers-what-do-they-mean) <br><br>
4. ***Blood Pressure:*** Blood pressure of the patient (systolic/diastolic)<br>
***Note:*** <br>
  _<120 & <80:_ Normal Blood Pressure<br>
  _120 to 129 & <80:_ Elevated Blood Pressure<br>
  _130 to 139 &/or 80-89:_ Stage 1 Hypertension<br>
  _140 to <180 &/or >90 - <120:_ Stage 2 Hypertension<br>
  _180 & higher &/or 120 & higher:_ Hypertensive Crisis    
  ***Source:*** [Blood Pressure](https://my.clevelandclinic.org/health/diagnostics/17649-blood-pressure) <br><br>
5. ***Heart Rate:*** Heart rate of the patient (Between 40 and 110 beats/min)<br>
    ***Note:*** <br>
    _If you want to calculate your maximum and target heart rates yourself, you can use these formulas:_ <br>
    _220 - your age = maximum._<br>
    _Maximum x 0.6 = low end of target range._<br>
    _Maximum x 0.8 = high end of target range._<br>
   ***Source:*** [Heart Rate](https://my.clevelandclinic.org/health/diagnostics/heart-rate) <br> <br>
7. ***Diabetes:*** Whether the patient has diabetes (1:Yes, 2:No)<br>
***Note:*** <br>
_Diabetes is a chronic disease that occurs either when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. Insulin is a hormone that regulates blood glucose._<br>
   ***Source:*** [Diabetes](https://www.who.int/news-room/fact-sheets/detail/diabetes#:~:text=Diabetes%20is%20a%20chronic%20disease,hormone%20that%20regulates%20blood%20glucose.) <br> <br>
8. ***Family History -*** Family history of heart-related problems (1: Yes, 0: No)
9. ***Smoking:*** Smoking status of the patient (1: Smoker, 0: Non-smoker)
10. ***Obesity:*** Obesity status of the patient (1: Obese, 0: Not obese) <br>
***Note:*** <br>
_Obesity is a chronic complex disease defined by excessive fat deposits that can impair health. Obesity can lead to increased risk of type 2 diabetes and heart disease, it can affect bone health and reproduction, it increases the risk of certain cancers. Obesity influences the quality of living, such as sleeping or moving._ <br>
***Source:*** [Obesity](https://www.who.int/news-room/fact-sheets/detail/obesity-and-overweight#:~:text=Obesity%20is%20a%20chronic%20complex,the%20risk%20of%20certain%20cancers.) <br> <br>
11. ***Alcohol Consumption:*** Level of alcohol consumption by the patient (1:Yes, 2:No)
12. ***Exercise Hours Per Week:*** Number of exercise hours per week (Exercise hours are between 0.0024 & 19.9987 hrs/week)
13. ***Diet:*** Dietary habits of the patient (Healthy/Average/Unhealthy)
14. ***Previous Heart Problems:*** Previous heart problems of the patient (1: Yes, 0: No)
15. ***Medication Use:*** Medication usage by the patient (1: Yes, 0: No)
16. ***Stress Level:*** Stress level reported by the patient (1-10), where _1_ is the lowest & _10_ is the highest.
17. ***Sedentary Hours Per Day:*** Hours of sedentary activity per day (between 0.0013 & 11.9993 hrs/day)<br>
***Note:*** <br>
_According to the charity [Just Stand](https://www.juststand.org/the-tools/sitting-time-calculator/), the following thresholds determine a person’s risk of developing health problems due to sitting:_ <br>
_Low risk:_ Sitting for less than 4 hours per day. <br>
_Medium risk:_ Sitting for 4–8 hours per day. <br>
_High risk:_ Sitting for 8–11 hours per day. <br>
_Very high risk:_ Sitting for more than 11 hours per day. <br>
***Source:*** [What happens to the body after sitting down for too long?](https://www.medicalnewstoday.com/articles/sitting-down-all-day#how-long-is-too-long) <br> <br>
18. ***Income -*** Income level of the patient (between 20,062 & 299,954)
19. ***BMI -*** Body Mass Index (BMI) of the patient<br>
***Note:*** <br>
_BMI will fit into one of 5 bands:_ <br>
_Underweight:_ under 18.5 <br>
_Healthy Range:_ between 18.5 and 24.9 <br>
_Overweight:_ between 25 and 29.9  <br>
_Obesity:_ between 30 and 39.9 <br>
_Severe Obesity:_ 40 & over <br>
20. ***Triglycerides -*** Triglyceride levels of the patient
21. ***Physical Activity Days Per Week -*** Days of physical activity per week
22. ***Sleep Hours Per Day -*** Hours of sleep per day
23. ***Country -*** Country of the patient
24. ***Continent -*** Continent where the patient resides
25. ***Hemisphere -*** Hemisphere where the patient resides
26. ***Heart Attack Risk -*** Presence of heart attack risk (1: Yes, 0: No)
