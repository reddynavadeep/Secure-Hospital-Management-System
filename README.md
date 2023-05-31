# Secure-Hospital-Management-System
This project is a secure hospital system that manages user accounts, patient records, appointments, lab tests, insurance claims, help and support, and chatbot services. The system is designed to meet the security requirements for managing sensitive hospital data.<br/>

## Technologies Used
### Front End
- Angular 
- HTML
- CSS
- Bootstrap
- JavaScript

### Back End
- Spring Boot
- Java
- Java Services
- Rest API

### DataBase
- MySQL


## User Categories
The system supports two types of users:
### Internal Users
- Hospital Staff: Responsible for approving appointment requests, creating and viewing patient records, diagnosis, prescriptions, lab test reports, and transaction requests.
- Doctors: Responsible for viewing and updating patient records, creating and updating diagnosis information, prescriptions, and lab test reports.
- Lab Staff: Responsible for creating, updating, and deleting lab test reports, verifying lab test requests, and approving or rejecting requests received from patients.
- Insurance Staff: Responsible for validating and approving insurance claim requests and authorizing fund disbursement.
- Administrator: Responsible for managing employee records, authorizing transaction requests, accessing system log files, and ensuring the smooth functioning of the hospital system.

### External Users
- Patients: Can request appointments with doctors, view their records, diagnosis, prescriptions, lab tests, payments, and transactions.

## Secure Hospital System Functionalities
The system provides the following functionalities:

- Appointments and Visits: Users can book, authorize, and view appointments.
- Diagnosis: Doctors can record and view patient diagnosis and schedule follow-up appointments if needed.
- Lab Tests: Doctors can recommend lab tests based on diagnosis, and lab staff can verify and release results.
- Insurance: Patients can claim insurance, and insurance staff can authorize and disburse funds.
- Help & Support Center: Patients can raise help requests that can be viewed by hospital staff.
- Chatbot: A chatbot helps patients with general inquiries and redirects them to appropriate web pages.
- OTP Verification: A series of alphanumerical characters is automatically generated using Google SMTP server and is used to authenticate a user for login or to view transactions.
- Session Management: The system uses session management to track user requests, and tokens are required for every user request.
- Preventing Malicious Login: The system has integrated Google reCAPTCHA to prevent malicious logins.
- Public Key Certificate: The system uses a self-signed public key certificate issued by Firebase to validate sender authorization and name.
- Data Masking: Sensitive data in the database is masked and secured using hashing algorithms.

