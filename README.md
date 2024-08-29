# Medical-Appointment---No-Show

The following dataset "Medical Appointment No Shows" consist of 110,527 rows of data and 14 variables detailing patients' characteristics and more importantly whether they show up to a medical appointment or not in Brazil.

The 14 variables (columns/characteristics) provided in the dataset are the following:

PatientId - unique identification of a patient
AppointmentID - unique identification of an appointment
Gender - binary identifier of a patient's gender (Male / Female)
ScheduledDay - date that someone called/registered to setup an appointment
AppointmentDay - actual date the appointment is scheduled and expected for patient to attend
Age - numerical value representing how old the patient is
Neighbourhood - location where the appointment takes place
Scholarship - binary identifier of whether a patient is enrolled in the "Bolsa Familia" social welfare program in Brazil
Hipertension - binary identifier indicating whether a patient has hypertension (True / False)
Diabetes - binary identifier indicating whether a patient has diabetes (True / False)
Alcoholism - binary identifier indicating whether a patient is an alcoholic (True / False)
Handcap - binary identifier indicating whether a patient is handicap (True / False)
SMS_received - binary identifier indicating whether a patient received any messages reminding them of their appointment (True / False)
No-show - binary identifier indicating whether a patient showed up for their appointment (True / False)

The analysis will focus on the following three questions:
1. How often are appointments missed (i.e., How often is No-Show = True) ?
2. Is there a difference between male and female not showing up for their appointments ?
3. Is there a difference between patients with scholarship versus those without scholarship show up for their appointments?
