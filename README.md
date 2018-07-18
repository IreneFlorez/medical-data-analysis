# medical-data-analysis

## Overview
Why do 20%+ of patients miss their scheduled appointments? This project analyzes data collected from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. 
Using NumPy and Pandas, this project looks at relationships between multiple variables: at least one dependent variable (No-show) and three independent variables (age, diabetes, week_day). variables are investigated using both single-variable (1d) and multiple-variable (2d) explorations.

## Contents
* data set used
* Jupyter and html files with the Python code written as part of the analysis
- analysis and data wrangling documentation
- data visualizations showing multiple comparisons and trends
- relevant statistics 
 
## Questions
* Which factors can help predict if a patient will miss their scheduled appointment? 
* What is the overall no-show percentage?
* What is the relationship between absenteeism and age?
* What is the relationship between absenteeism and appointment day?

## About the data
A number of characteristics about the patient are included in each row:
- PatientId - Identification of a patient AppointmentID 
- Identification of each appointment Gender = Male or Female
- AppointmentDay = The day of the actuall appointment, when they have to visit the doctor. 
- Age = How old is the patient. 
- Neighbourhood = Where the appointment takes place. 
- Scholarship = Ture of False . Observation, this is a broad topic, consider reading this article https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia 
- Hipertension = True or False Diabetes = True or False 
- Alcoholism = True or False Handcap = True or False SMS_received = 1 or more messages sent to the patient. 
- No-show = True or False.
- ScheduledDay: tells us on what day the patient set up their appointment.
- Neighborhood: indicates the location of the hospital.
- Scholarship: indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.


#Data Source:
Udacity & https://www.kaggle.com/joniarroba/noshowappointments/home
