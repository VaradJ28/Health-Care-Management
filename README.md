Health Care Management 

Overview
The Health Care Management System is a robust application designed to streamline patient care management. Built with React.js on the frontend, Node.js with Express on the backend, and MySQL for data storage, this system provides an efficient way for patients to manage their appointments and medical history while ensuring privacy and avoiding appointment clashes.

Features
Patient Interface
Login: Secure login system for patients.
Appointment Booking: Book and manage appointments with available doctors.
Medical History: Provide previous medical history during registration.
Manage Appointments: View, update, or cancel existing appointments. Cancelled appointments create free slots for other patients.
Diagnosis and Prescriptions: Access complete diagnosis, prescriptions, and medical history related to appointments.
Privacy: Patient medical history is accessible only to the doctor with whom the appointment is booked.

System Functionality
Slot Management: Avoids clash of appointments by ensuring each patient has a reserved slot.
Doctor Access: Doctors can view patient medical history only for their appointments to maintain confidentiality.

Tech Stack
Frontend: React.js
Backend: Node.js with Express
Database: MySQL
Getting Started
Prerequisites
Node.js
MySQL

Installation

bash
cd health-care-management

Setup the backend:

Navigate to the backend directory:

bash
cd backend
Install the required Node.js packages:

bash

npm install
Set up the MySQL database using the provided schema file (schema.sql).

Start the backend server:

bash
npm start
Setup the frontend:

Navigate to the frontend directory:

bash
cd ../frontend
Install the required Node.js packages:

bash
npm install
Start the frontend development server:

bash
npm start
Configure environment variables:

Create a .env file in the backend directory and configure database connection details and any other necessary environment variables.
Usage

Patient Login: Use your credentials to log into the patient interface.
Book Appointments: Select a doctor and choose a suitable time slot.
View/Update/Cancel Appointments: Manage your existing appointments from the dashboard.
Medical History: Enter your previous medical history during registration.
Privacy: Access your diagnosis, prescriptions, and medical history from the appointment details.


License

This project is licensed under the MIT License - see the LICENSE file for details.

