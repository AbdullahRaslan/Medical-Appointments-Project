# Medical Appointment No Shows Dataset Exploration
## by: Abdullah Raslan


## Dataset

This dataset includes information about more than 100,000 medical appointments for patients in Brazil 
and many of them did not show up in their scheduled appointments. This dataset contains 110527 records 
of patient appointments. Each Patient have 10 characteristics most of them are categorical.
Dataset can be accessed from [here](https://www.kaggle.com/joniarroba/noshowappointments)


## Summary of Findings

After doing primary cleaning for the dataset, the main interest is to find a relationship between a certain
feature for patients and not showing up in their scheduled appointments. Age for example can be a big influencer
in not showing up in the appointment, also if the patient has a scholarship or if he was Hipertensive, have 
diabetes, Alcoholist or a Handcap. All this characteristics might have an influence and will support my investigation.
The majority have showed up but around 20% of appointments are missed. For age as a factor under scope, we can observe
a peak in ages from 0 to 2 year. Females are the majority.

Some of the variables that I noticed they affect not showing up to an appointment are:
- Appointment Delay: not showing up status had a higher average delay days than shwowing up.
- Scholarship: patients with scholarship tend to have a higher proportion in not showing up to an appointment compared 
to those who don't have a scholarship.
- Hypertension: Not hypertensive patients have a higher proportion in not showing up to an appointment compared to those
who are.
- Diabetes: Not diabetic patients have a higher proportion in not showing up to an appointment compared to those who are.

## Key Insights for Presentation

For the presentation, I focused on factors that influence showing up to appointments. Started with explaining that 
around 20% of patients in the dataset miss their scheduled appointments, So we need to dig deep in the correlation
between their characteristics and showing up status. Then I plotted on a logarithmic scale, the distribution of 
appointment delay is right skewed and the highest delay exceeds 175 days. Also concluding that the likelihood of 
missing an appointment increases when the delay days are larger.

Last plot was showing that with a slight difference in proportion, if the patient is not hypertensive or not diabetic 
its more likely that he/she will miss the appointment.