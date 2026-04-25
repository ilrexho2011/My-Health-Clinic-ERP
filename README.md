# My Health - Clinic Management System 
## The most complete and multi-functional hospital or medical center management system. 

<img width="1660" height="934" alt="image" src="https://github.com/user-attachments/assets/2d23ee5f-f675-44cd-81c4-af61f2a37f6d" />


It combines admin, patients, doctors, nurses, laboratorists, pharmacists, receptionist, accountants so that all the paperworks and manual tiresome works can be automated easily and efficiently.

## Executive Summary
The “My Health Clinic ERP” package represents a web-based clinic and hospital management system. It is implemented on a CodeIgniter MVC architecture and is designed to centralize medical, administrative, operational, and financial processes in a single multi-user platform.
•	Automates workflows such as patient registration, appointments, prescriptions, diagnoses, invoicing, reporting, and notifications.
•	Organizes access by role: administrator, doctor, patient, nurse, pharmacist, laboratorist, accountant, and receptionist.
•	Separates application logic into controllers, models, configuration, helpers, hooks, libraries, and core services.
•	Includes user guides, UI assets, uploads, logs/cache, and service components for Email, SMS, and PayPal payments.

## Package Objective
The primary objective is to digitize and automate daily clinic operations. The system reduces dependence on manual paperwork, improves coordination between business roles, and establishes a centralized source of information for patients, appointments, prescriptions, reports, medicines, and payments.

## Package Building Blocks and Their Role

<img width="1662" height="933" alt="image" src="https://github.com/user-attachments/assets/a34d5f11-feed-4be5-9e0d-274929a6bf89" />

Building Block	 |   Role	 |  Main Function
----------------------------------------------------------------------------------------
sistemi	            205	      Core framework and libraries / Framework dhe librari bazë
asetet	            186	      CSS, JavaScript, fonts and UI assets / Asete UI
guida	               82	      User and implementation guide / Udhëzues përdorimi
aplikacioni	         49	      Application MVC layer / Shtresa aplikative MVC
ngarkimet	           31	      Uploaded clinical and user content / Përmbajtje e ngarkuar
README.md	            1	      Package description / Përshkrim pakete
index.php	            1	      Application entry point / Pika hyrëse
sap_aem	              1	      Supplementary component / Komponent shtesë

## Enterprise Assessment
•	Strengths: clear role separation, MVC architecture, multi-language capability, package documentation, and broad operational coverage.
•	Technical attention areas: before production use, security configuration, password handling, library versions, input validation, and database backup strategy should be verified.
•	Recommendation: add a modern audit layer, structured logging, granular access control, and an API integration layer for external healthcare systems.
