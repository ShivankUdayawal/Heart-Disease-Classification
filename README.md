# Heart-Disease-Classification
### Given clinical parameters about a patient, need to identify whether a person has heart disease or not.

## Introduction :
Heart disease describes a range of conditions that affect your heart. Diseases under the heart disease umbrella include blood vessel diseases, such as coronary artery disease, heart rhythm problems (arrhythmias) and heart defects you’re born with (congenital heart defects), among others.

The term heart disease is often used interchangeably with the term cardiovascular disease. Cardiovascular disease generally refers to conditions that involve narrowed or blocked blood vessels that can lead to a heart attack, chest pain (angina) or stroke. Other heart conditions, such as those that affect your heart’s muscle, valves or rhythm, also are considered forms of heart disease.

Heart disease is one of the biggest causes of morbidity and mortality among the population of the world. Prediction of cardiovascular disease is regarded as one of the most important subjects in the section of clinical data analysis. The amount of data in the healthcare industry is huge. Data mining turns the large collection of raw healthcare data into information that can help to make informed decisions and predictions.

According to a news article, heart disease proves to be the leading cause of death for both women and men. The article states the following :

   * About 610,000 people die of heart disease in the United States every year–that’s 1 in every 4 deaths.1
   * Heart disease is the leading cause of death for both men and women. More than half of the deaths due to heart disease in 2009 were in men.1
   * Coronary Heart Disease(CHD) is the most common type of heart disease, killing over 370,000 people annually.
   * Every year about 735,000 Americans have a heart attack. Of these, 525,000 are a first heart attack and 210,000 happen in people who have already had a heart attack.

The World Health Organization (WHO) lists cardiovascular diseases as the leading cause of death globally with 17.9 million people dying every year. The risk of heart disease increases due to harmful behavior that leads to overweight and obesity, hypertension, hyperglycemia, and high cholesterol. Furthermore, the American Heart Association complements symptoms with weight gain (1–2 kg per day), sleep problems, leg swelling, chronic cough and high heart rate. Diagnosis is a problem for practitioners due the symptoms’ nature of being common to other conditions or confused with signs of aging.

This makes heart disease a major concern to be dealt with. But it is difficult to identify heart disease because of several contributory risk factors such as diabetes, high blood pressure, high cholesterol, abnormal pulse rate, and many other factors. Due to such constraints, scientists have turned towards modern approaches like Data Mining and Machine Learning for predicting the disease.

## Problem Statement :
  #### Given clinical parameters about a patient, need to identify whether a person has heart disease or not.

## Description of Dataset :
The dataset consists of 303 individuals data. There are 14 columns in the dataset, which are described below.

 **1. Age :** displays the age of the individual.

 **2. Sex :** displays the gender of the individual using the following format :

     1 = male 
     0 = female

 **3. Chest-pain type :** displays the type of chest-pain experienced by the individual using the following format :

     1 = typical angina
     2 = atypical angina
     3 = non — anginal pain
     4 = asymptotic

 **4. Resting Blood Pressure :** displays the resting blood pressure value of an individual in mmHg (unit)

 **5. Serum Cholestrol :** displays the serum cholesterol in mg/dl (unit)

 **6. Fasting Blood Sugar :** compares the fasting blood sugar value of an individual with 120mg/dl.

     If fasting blood sugar > 120mg/dl then : 1 (true)
     else : 0 (false)

 **7. Resting ECG :** displays resting electrocardiographic results

     0 = normal
     1 = having ST-T wave abnormality
     2 = left ventricular hyperthrophy

 **8. Max heart rate achieved :** displays the max heart rate achieved by an individual.

 **9. Exercise induced angina :**

     1 = yes
     0 = no

 **10. ST depression induced by exercise relative to rest :** displays the value which is an integer or float.

 **11. Peak exercise ST segment :**

     1 = upsloping
     2 = flat
     3 = downsloping

 **12. Number of major vessels (0–3) colored by flourosopy :** displays the value as integer or float.

 **13. Thal : displays the thalassemia :**

     3 = normal
     6 = fixed defect
     7 = reversible defect

 **14. Diagnosis of heart disease :** Displays whether the individual is suffering from heart disease or not :

     0 = absence
     1, 2, 3, 4 = present.
