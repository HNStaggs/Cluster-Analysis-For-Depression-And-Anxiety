# Cognitive Phenotype Clusters in Comorbid Depression and Anxiety 
Cluster Analysis for Cognitive Subtypes in Depression and Anxiety Comorbidity 

# BACKGROUND:
National Alliance on Mental Illness reports that anxiety and depression comorbidity rates are as high as 60%

There are many issues with diagnosis via DSM self-report only. The diagnostic categories are rigid, yet also allow for too much heterogeneity. 
The majority of “diagnosis-privileged” professionals in California are NOT clinical psychologists. In fact, only 18% of people able to give a mental 
health diagnosis in California are clinical psychologists (according to the California Health Care Foundation). Diagnoses from clinical psychologists 
are more robust because they are the only group allowed to administer objective, neuropsychologic tests that collect cognitive performance data. Because most 
diagnoses lack objective neuropsych testing, many patients are at risk of receiving a treatment that does not fit with their level of cognitive
functioning. There is a need for objective data for patient assessments and in research. Mood disorders affect more than thoughts and emotions, and 
individual differences in the presentation of mental health symptoms exist, so it may be useful to substype patients by cognitiv status in order to triage 
treatment.

Issues with self report symptoms: 
-Self report creates 100s of symptom combinations
-Global scores lack functional context
-Scientifically difficult to model (multicolinearity and overly-complex solutions)
-Self perception has biases

Pro's of cognitive data:
-Can track functional improvement or decline over time
-Easier to model
-Objective

This exploratory analysis of community comorbidity included cognitive data from a diverse, nationwide sample recruited with teleresearch methods.
Clinical thresholds of anxiety and depression were assessed with two validated measures: the Patient Health Questionnaire 8 and the Generalized
Anxiety Disorder 7, with global scores having a 0.8 correlation, indicating comorbidity of symptoms.

The following question was explored: Are objective cognitive performance metrics more robust than self-report symptoms for subtyping? 

# SAMPLE: 230 teleresearch participants

# VARIABLES: 
ID - participant id, Age - in years, Sex - male (1) / female (2), Education - , Cohort - aging (summer 2022), vdap (summer 2023), Verify veteran (veteran status) - no (0) , yes (1), Gad1 - , Gad2 - , Gad3 - , Gad4 - , Gad5 - , Gad6 - , Gad7 - , Phq1 - , Phq2 - , Phq3 - , Phq4 - , Phq5 - , Phq6 - , Phq7 - , Phq8

# DATA COLLECTION METHODS
Cognitive data was collected via browser-deployed tasks in Gorilla Experiment Builder.
A visual search task asked participants to "Find the Orange L."
There was an absent and present condition. The absent condition was sensitive to behavioral producers. 
The two metrics pulled from the task were: accuracy and reaction time z-scores.


# DATA ANALYSIS METHODS
K-means clustering


