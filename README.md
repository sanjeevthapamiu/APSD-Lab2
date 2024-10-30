# APSD Lab #2

## ADS Functional Requirements

System is a web-based solution (i.e. website)
System is used by Office Manager to:
* Register Dentists (unique ID, first name, last name, phone, email, 
specialization)
* Enroll new Patients (first name, last name, phone, email, mailing 
address and date of birth)
* Book the appointment upon receiving request from Patient (System will 
additionally send confirmation email to customer as well)

System is used by patients to:
* Request Appointment by submitting online form
* Sign in to the system and view their Appointments (including Dentist 
Details they have been booked to see)
* Request to change or cancel their appointment
System is used by Dentists to:
* Sign in to the system and view listing of their Appointments (including 
scheduled to see Patient Details)

System should also provide the information about each Surgery (name, 
location address, telephone number)

System should also have Appointment which is normally made for a specific 
date and time and the dentist is expected to see/treat the patient at one 
of the surgery locations

Point to be Noted:
* Dentists cannot be given more than 5 appointments in any week
* System should prevent a Patient from requesting a new appointment if 
they are outstanding unpaid bill)


## ADS UML Class Diagram
![ADS UML Class Diagram](https://github.com/sanjeevthapamiu/APSD-Lab2/blob/main/ADSUMLClassDiagram.jpeg)
