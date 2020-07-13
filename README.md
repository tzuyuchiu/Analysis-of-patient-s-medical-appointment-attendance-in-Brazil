# Analysis of patient's medical appointment attendance in Brazil
## Introduction
This project is part of Udacity's Data Analyst Nano Degree Program.
A non-attending patient who neither uses nor cancels their appointments with no prior notice, are frequent and costly. 
We will be working on a dataset of medical appointments from the hospitals in Brazil. The dataset was originally scraped and uploaded to Kaggle (https://www.kaggle.com/joniarroba/noshowappointments). 
The version of the dataset we are working with is a sample of 110,257 data points. The independent variable is if the patient show-up or no-show to the appointment.
The data dictionary provided with data is as follows:

PatientId: Identification of a patient
AppointmentID: Identification of each appointment
Gender: Male or Female. Female is the greater proportion; woman takes way more care of their health in comparison to man.
AppointmentDay: The day of the actuall appointment, when they have to visit the doctor.
ScheduledDay: The day someone called or registered the appointment, this is before appointment of course.
Age: How old is the patient.
Neighbourhood: Where the appointment takes place.
Scholarship: True of False. Observation, this is a broad topic, consider reading this article
Hipertension: True or False
Diabetes: True or False
Alcoholism: True or False
Handcap: True or False
SMS_received: 1 or more messages sent to the patient.
No-show: True or False

## Research Questions
The aim of this project is to clean the data and analyze the data to find out what are the important factors to know if the people will fail to show up to thier appointments.

1. Which neighbourhoods have the highest no_show rate?

2. Is the period between scheduled day and appointment day affecting the number of no-show appointments?

3. How does each month compare to the others in terms of No-Show Appointment?

4. What factors are important to know if a patient will show up for thier apointment?

## Conclusions
Our analysis suggested that

- There is no sigificant difference between the age distribution bwtween the patient who showed up for the appointment and patient who failed to show up for the appointment.

- People that have a disease are 3% more likely to show up for the appointment than people who do not have a disease.

- There is a higher percentage of people that received SMS and did not show up when compared to people who received the SMS and did not show up.

- The patient had the period, between scheduled day and appointment day, with more than two weeks are more likely to no_show for the appointment than patients with less than 14 days of interval period.

- Being enrolled in the scholarship program does not make people more likely to show up to the appointment.

- In May, the patient are 1-2% more likely to fail for the appointment than the other two months.

## Limitations:
- There are a couple of limitations with our data:

- Most of variables are categorical,which does not allow for a high level of statistical method that used to provide correlations.

- We do not have many details for certain factors to draw conclusions. Our data shows that the people received SMS are more likely no-show. This could be the hospital target those no-sho patients with SMS.

- We can not show the correlations between factors since most of variables are binary.

- We don't have enough data for time series which is hard to make conclusion for month or year obervations.
