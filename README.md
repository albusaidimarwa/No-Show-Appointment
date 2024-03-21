# No-Show-Appointment
Statistical and graphical observations for medical appointments in Brazil downloaded from this website: https://www.kaggle.com/joniarroba/noshowappointments&sa=D&ust=1532469042118000

This project will investigate several factors/characteristics that may affect the show-up and no-show decisions to the appointment by analysing 'noshowappointments-kagglev2-may-2016.csv' document that collects data of 110,527 medical appointments in Brazil. Each appointment includes information for 14 associated variables/characteristics, which are:
  PatientId: serial ID for a patient. AppointmentID: serial ID for an appointment. Gender: Gender of a patient (female coded as (F) or male coded as (M)). 
  ScheduledDay: The day when a patient set up an appointment.
  AppointmentDay: The day of patient's appointment. Age: Age of the patient. Neighbourhood: the location of the hospital. Scholarship: tells us if a patient is enrolled in Brazilian welfare program, Bolsa Família (1 for enrolled, 0 for not). Hypertension and Diabetes: tell us if a patient has the health issue or not(1 for infected, 0 for not). Alcoholism: tell us if a patient consume alcohol or not(1 for consume, 0 for not). Handicap: tell us the numbers of handicaps a patient would face. SMS_Received: tells us if the patient received an SMS (1 for recieved, 0 for not). No_Show: whether the patient show-up or not (Yes for no-show, No for show-up). 

This program is structured to answer the broad question mentioned above, so, we need to break it down into the following:

What is the overall appointments' attendance performance of the patients?
How the following factors are important in order to predict if a patient will show up for their scheduled appointment?
2.1 Gender
2.2 Age
2.3 Neighbourhood
2.4 Scholarship and SMS_Received
2.5 Health issues (Hypertension, Diabetes and Alcoholism)
How is the time difference between the scheduled day and appointment day affect patient's decision?
