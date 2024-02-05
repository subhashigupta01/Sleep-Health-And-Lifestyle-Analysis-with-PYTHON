# Sleep-Health-And-Lifestyle-Analysis-with-Python
It is my second repository on Sleep, Health, Lifestyle analysis.

**Data Description**

The Sleep Health and Lifestyle Dataset has 400 rows and 13 columns,
covering a wide range of variables related to sleep and daily habits.
It includes details such as gender, age, occupation, sleep duration, quality of sleep,
physical activity level, stress levels, BMI category, blood pressure, heart rate, 
daily steps, and the presence or absence of sleep disorders.

**Dataset used**- [sleep_health_and_lifestyle_dataset](https://github.com/subhashigupta01/Sleep-Health-And-Lifestyle-Analysis-with-PYTHON/blob/2b45ba4d8cf9c1506eee58a053656d779f9142a5/Sleep_health_and_lifestyle_dataset.csv) 

**Key Features of the Dataset:**

<br>
Comprehensive Sleep Metrics: Explore sleep duration, quality, and factors influencing sleep patterns.
<br>
Lifestyle Factors: Analyze physical activity levels, stress levels, and BMI categories.
<br>
Cardiovascular Health: Examine blood pressure and heart rate measurements.
<br>
Sleep Disorder Analysis: Identify the occurrence of sleep disorders such as Insomnia and Sleep Apnea.
<br>


1. Person ID: An identifier for each individual.
<br>
2. Gender: The gender of the person (Male/Female).
<br>
3. Age: The age of the person in years.
<br>
4. Occupation: The occupation or profession of the person.
<br>
5. Sleep Duration (hours): The number of hours the person sleeps per day.
<br>
6. Quality of Sleep (scale: 1-10): A subjective rating of the quality of sleep, ranging from 1 to 10.
<br>
7. Physical Activity Level (minutes/day): The number of minutes the person engages in physical activity daily.
<br>
8.  Stress Level (scale: 1-10): A subjective rating of the stress level experienced by the person, ranging from 1 to 10.
<br>
9. BMI Category: The BMI category of the person (e.g., Underweight, Normal, Overweight).
<br>
10. Blood Pressure (systolic/diastolic): The blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure.
<br>
11.Heart Rate (bpm): The resting heart rate of the person in beats per minute.
<br>
12.Daily Steps: The number of steps the person takes per day.
<br>
13.Sleep Disorder: The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea).


**Details about Sleep Disorder Column:**

None: The individual does not have any specific sleep disorder.

Insomnia: The individual who is experiencing difficulty falling asleep or staying asleep, leading to poor-quality sleep.

Sleep Apnea: The individual who is suffering from pauses in breathing during sleep, resulting in disrupted sleep patterns and potential health risks.


**Project Objectives**

This data is created for illustrative purposes. The main objectives of the project is to analyze and visualize the data related to health, lifestyle, and demographic factors, derive actionable insights from the visualizations, and predict stress levels. 

**What I done to get insight from Data**

I used google colab to create and analyse data. Here going to share what exactly I have done in the project.

1. **Data Cleaning**- Replace and clean data while filling null values.
2. **Exploratory Data Analysis (EDA)**-Analyze or summarize data for knowing pattern of data,so that I can get insights from it.Doing this used Histplot, Barplot, swarmplot, Regplot, Lmplot, kdeplot etc.

**Data analyze with python**-[Sleep_Disorder_Analyses](https://github.com/subhashigupta01/Sleep-Health-And-Lifestyle-Analysis-with-PYTHON/blob/6482f2f6ab83093eedc9116e5df5acb2a6c6bf7e/Sleep_health_and_lifestyle_dataset.ipynb)

**Conclusions**

The analysis of the dataset has revealed several noteworthy findings:

**Age and Stress:** Younger individuals tend to experience higher levels of stress compared to their older counterparts. Additionally, men, on average, report higher stress levels than women. Surprisingly, there is no discernible correlation between stress levels and the presence of sleep disorders.

**Physical Activity and Sleep:** The level of physical activity shows a positive correlation with sleep duration. However, for individuals with Apnea, higher physical activity is associated with shorter sleep duration.

**Impact of Sleep Disorders:** Sleep disorders do not appear to significantly affect sleep duration differently among men and women.

**Prevalence of Insomnia and Apnea:** Insomnia is most prevalent in the age range of 40-45, while Apnea occurs most frequently between the ages of 50-60.

**Occupational Sleep Patterns:** Notably, Engineers and Lawyers exhibit the longest average sleep duration, while Teachers and Salespeople tend to sleep the least. Specific occupations with varying occurrences of sleep disorders include:

Insomnia: Teachers, Salespeople
Apnea: Nurses
No Disorder: Lawyers, Doctors, Engineers, Accountants

**Gender Disparities in Sleep Disorders:**

Apnea is more prevalent among women.
Doctors and Lawyers, predominantly male occupations, show a higher occurrence of no sleep disorder.

**Apnea and Weight:** A significant proportion of individuals with Apnea are overweight, particularly women. However, physical activity level alone may not explain the higher prevalence of Apnea in women compared to men.

**Occupational and Gender Distribution:**
All Nurses are females, and most individuals with Apnea are nurses.
Among those with no sleep disorders, a majority are Doctors and Lawyers, who are predominantly male.
There are no men over 50 years of age, and Apnea is more prevalent among women older than 48

These findings provide valuable insights into the complex interplay between age, gender, occupation, physical activity, and sleep patterns within the analyzed dataset.


