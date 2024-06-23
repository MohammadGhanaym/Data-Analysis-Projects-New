# Medical Appointment Dataset Analysis

## Introduction

This repository contains an analysis of a medical appointment dataset focusing on understanding the characteristics of people who show up and those who do not show up for their doctor appointments. The dataset consists of 100k medical appointments in Brazil and includes 14 variables.

## Data Source

The dataset used in this analysis is sourced from [Kaggle - No-show appointments dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments/data).

## Variables Description

- **PatientId**: Identification of a patient
- **AppointmentID**: Identification of each appointment
- **Gender**: Male or Female
- **AppointmentDay**: The day of the actual appointment
- **ScheduledDay**: The day the appointment was scheduled
- **Age**: Age of the patient
- **Neighbourhood**: Where the appointment takes place
- **Scholarship**: True or False, indicating if the patient is enrolled in the Bolsa Família program
- **Hipertension**: True or False
- **Diabetes**: True or False
- **Alcoholism**: True or False
- **Handcap**: True or False
- **SMS_received**: Number of messages sent to the patient
- **No-show**: True or False, indicating if the patient showed up to their appointment

## Key Insights and Conclusions

- **Waiting Time**: Waiting time has a significant impact on attendance rates. Strategies to decrease waiting times should be prioritized.
- **Age**: Younger patients are more likely to miss appointments compared to older patients.
- **Chronic Conditions**: Patients with chronic conditions are more likely to attend appointments, but this alone does not significantly distinguish attendees from non-attendees.
- **SMS Reminders**: Patients receiving SMS reminders are more likely to miss appointments, suggesting the need for a revised reminder strategy.
- **Same-Day Appointments**: Patients attending same-day appointments have high attendance rates and do not rely heavily on SMS reminders.
- **Neighborhood**: Certain neighborhoods exhibit higher attendance rates, highlighting the need for targeted interventions in areas with lower attendance.

## Files Included

- `age_by_No_show.png`: Chart showing age distribution by appointment attendance.
- `investigation_of_medical_appointment.html`: HTML version of the analysis notebook.
- `investigation_of_medical_appointment.ipynb`: Jupyter Notebook containing the analysis code.
- `neighbourhood_count_by_no_show.png`: Chart showing appointment count by neighborhood and attendance.
- `noshowappointments.csv`: Dataset file containing the medical appointment data.
- `proportions_of_age_groups_by_no_show.png`: Chart showing proportions of age groups by appointment attendance.
- `proportions_of_gender_by_no_show.png`: Chart showing proportions of gender by appointment attendance.
- `proportions_of_sms_received_by_no_show.png`: Chart showing proportions of SMS received by appointment attendance.
- `proportions_of_waiting_time_categories_by_no_show.png`: Chart showing proportions of waiting time categories by appointment attendance.
- `waiting_time_categories_by_SMS_received.png`: Chart showing waiting time categories by SMS received.


## Contributions

Contributions and feedback are welcome. Feel free to open issues or pull requests for improvements or additional analysis.
