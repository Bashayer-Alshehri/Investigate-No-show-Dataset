## Medical Appointments No-Shows


## Overview
In this project, I aim to investigate the factors that affect the medical scheduled appointments attendance in Brazil. The Dataset that I'm trying to explore and investigate includes some features about patients plus whether the patient shows up to the appointments or not.The Data analysis in this project is an attempt to highlight some Trends that may or may not cause patients to attend.

You can find the original problem and the Dataset from here : https://www.kaggle.com/joniarroba/noshowappointments

This project was completed as part of Udacity's Data Analyst Nanodegree certification.


## Details
I have worked with the dataset and fixed a few problems like, removing wrong data, fixed the datatype of the data, adding new features based on existing data. I have also investigated most of the patient features in the dataset and made a few observations comparing them to the (no_show) feature. As this was only an exploratory analysis, many potential correlations may remain uncovered. The data should be investigated further with more advanced statistical analysis to potentially reveal new insights and correlations.

For more details see analysis documentation Jupyter Notebook or HTML.


## Findings
The most important findings are:


the 'Scheduled Day' started on 2015-11-10 and end on 2016-06-08 .
the 'AppointmentDay' started on 2016-04-29 and end on 2016-06-08 .
the appointments for the (Monday, Tuesday, Wednesday) days they kind of equals in distributed while (Friday, Thursday) days they a little bit less than the days before, "Saturday" with 24 appointments and no appointment for Sunday.
The average the waiting period is 10, where the min is 0 days, and 75% is 15 days while the max is 179 days
The top number of patients that scheduled their appointments on the same days is 40,000 patients.
Out of 38,562 patients, there were 1792 patients about 5% who did not show up.
There are many young patients but in general, the patient's age is well-distributed and the number of patients goes drastically down for patients older than 60 years.
The Average Age of patients is 37, while the min patients age is 0 'infants', 25% of patients are 18 years old 'teenagers', 75% of patients are 55 years old and the max is about 115.
Most of the patients are not alcoholics.
Most of the patients are not diabetes but more than alcoholics.
There are four handicapped categories with most of the people not being handicapped.
Most patients do not suffer from hypertension.
On average, 20% of appointments were missed.
Out of 71839 appointments made by females, 13% of females were missed their appointment.
Out of 38687 appointments made by the male, 6% of the male were missed their appointment.
There are multiple appointments for the same patients, where the number of appointments for the top 5 patients ranges from 88 to 62 appointments, Taking into consideration, that the time range of visits appointed spans over 2 months, an appointment is most likely each examination or each specialist visit.
The bar chart of the patient's feature confirms that the number of patients that didn't show up in their scheduled appointment is 20%.
The average the waiting period is 10, where the min is 0 days, and 75% is 15 days while the max is 179 days.


## Statistical Analysis Scope
Data Wrangling
Exploratory Data Analysis (EDA)
Examination of central tendency and spread
Data visualizations


## Tools
Python, libraries: numpy, pandas, matplotlib, seaborn
Jupyter Notebook 
