# medical-data-analysis

Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

#Project Contents:
This project will eventually contain:
* A report communicating the findings
    - looking at relationships between multiple variables: at least one dependent variable (No-show) and three independent variables (age, diabetes, handcap). The stated question(s) is investigated from multiple angles. At least three variables are investigated using both single-variable (1d) and multiple-variable (2d) explorations.

    - Uses NumPy and pandas where appropriate

    - documents any changes that were made to clean the data, such as merging multiple files, handling missing values, etc.
    - Reasoning is provided for each analysis decision, plot, and statistical summary.
    - The results of the analysis are presented such that any limitations are clear. The analysis does not state or imply that one change causes another based solely on a correlation.

    - The project's visualizations are varied and show multiple comparisons and trends. Relevant statistics are computed throughout the analysis when an inference is made about the data.
    - At least two kinds of plots should be created as part of the explorations.

* Python code written as part of the analysis
* The data set used 

#Question: 
Why do 30% of patients miss their scheduled appointments?
What factors are important for us to know in order to predict if a patient will show up for their scheduled appointment?

#Context
A person makes a doctor appointment, receives all the instructions and no-show. Who to blame? If this is help, don´t forget to upvote :) Greatings!
scholarship variable means this concept = https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia

#Dataset:
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.

#Data Explanation:
PatientId - Identification of a patient AppointmentID - Identification of each appointment Gender = Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man. DataMarcacaoConsulta = The day of the actuall appointment, when they have to visit the doctor. DataAgendamento = The day someone called or registered the appointment, this is before appointment of course. Age = How old is the patient. Neighbourhood = Where the appointment takes place. Scholarship = Ture of False . Observation, this is a broad topic, consider reading this article https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia Hipertension = True or False Diabetes = True or False Alcoholism = True or False Handcap = True or False SMS_received = 1 or more messages sent to the patient. No-show = True or False.

‘ScheduledDay’ tells us on what day the patient set up their appointment.
‘Neighborhood’ indicates the location of the hospital.
‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
Be careful about the encoding of the last column: it says ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

#Data Source:
Udacity & https://www.kaggle.com/joniarroba/noshowappointments/home
