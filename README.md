# heath-management
A Django-based web application for managing medical appointments between doctors and patients, with role-based access control for administrators, doctors, and patients.

Features
User Roles:

Admin: Manages the system and can view all appointments
Doctor: Views patient appointments, adds prescriptions, and manages their schedule
Patient: Books and views their own appointments

Appointment Management:

Patients can book appointments with doctors
Doctors can view and manage their appointments
Status tracking (Pending, Approved, Cancelled, Done)
Appointment cancellation functionality

Prescription System:

Doctors can add prescriptions to completed appointments
Prescription history tracking

Authentication:

User registration with role selection
Login/logout functionality
Role-based dashboard redirection

Usage
Registration:

Register as a patient or doctor
Admins must be created via the Django admin panel

Appointments:

Patients can book appointments via the "Book Appointment" page
Doctors can view and manage their appointments
Admins can view and manage all appointments

Prescriptions:

Doctors can add prescriptions to completed appointments
Prescriptions are linked to specific appointments
<img width="956" height="412" alt="a" src="https://github.com/user-attachments/assets/384ca9af-ab2d-46f7-80fe-b139514dc96c" />

