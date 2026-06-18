# Assignment-1: GitHub Repository, Readme File and commit messages
In this MSc assignment we have been provided with data files for hospitals, patients, doctors and prescriptions. This project aims to visualise the healthcare related dated stored within provided CSV files via the creation of SQL tables and generating SQL queries. 

A link to the full respository for assignment 1 is available here: https://github.com/pjgreenwood218/Assignment-1-GitHub-Repository-Readme-File-and-commit-messages

To start I created a flow chart to decompose the assignment to smaller management tasks, please view: https://github.com/pjgreenwood218/Assignment-1-GitHub-Repository-Readme-File-and-commit-messages/blob/main/Decomposition%20of%20Assignment%201.docx

The export of the SQL database is available: https://github.com/pjgreenwood218/Assignment-1-GitHub-Repository-Readme-File-and-commit-messages/blob/main/mysql%20export_file.sql

## Description of files, databases and tables used:
The following files used for this project are stored in ~/assessments/hpdm206Z/assessment1: hospitals.cvs, patients.cvs, doctors.cvs and prescriptions.cvs.

The hospital.cvs file contains the following information represented in SQL table 'Hospitals'.

The patients.cvs file contains the following information represented in SQL table 'Patients'.

The doctors.cvs file contains the following information represented in SQL table 'Doctors'.

The precription.cvs file contains the following information represented in SQL table 'Prescriptions'.

The data types (INT, VARCHAR or DATE) to be used for each table is visable in the code used to generate the tables, which is available here: https://github.com/pjgreenwood218/Assignment-1-GitHub-Repository-Readme-File-and-commit-messages/blob/main/Create%20Tables%20in%20mysql.docx

As these are relational databases primary and foreign keys have been included in the code for each SQL table. The summary of relationships is depicted in the entity relationship diagram: https://github.com/pjgreenwood218/Assignment-1-GitHub-Repository-Readme-File-and-commit-messages/blob/main/ERD.docx

## Rationale for SQL queries:
SQL queries were created for tables named: Hospitals, Patients, Doctors and Prescriptions. 

The code used for SQL queries is available here:https://github.com/pjgreenwood218/Assignment-1-GitHub-Repository-Readme-File-and-commit-messages/blob/main/Generating%20queries%20in%20SQL.docx

The aim of generated SQL queries is to replicate real world data driven insights. The purpose of each query provided below:
•	Print a list of doctors at a given hopsital: The code written allows the hospital id to be input by the user and will identify from the doctors table the doctors that work at the selected hospital. This may be useful in review of staffing or to identify where key opinion leaders work to collaborate in research. 

•	Print a list of all prescriptions for a particular patient, ordered by the prescription date: The code written allows for patient id to be input by the user and will identify the prescriptions from the precription table that are assigned to selected patient. This may be useful to gain insight on medical history of the patient. 

•	Print a list of  prescriptions that a doctor has prescribed: The code written allows for doctor id to be input by the user and will identify all presciptions from the prescription table written by that doctor. This may be useful in the case where prescriptions and alternative treatments need to be discussed.

•	Add a new patient to the database, including being registered to one of the doctors: The code written allows input of information of a new patient into the patients table. This may be useful when a new patient registers at a hospital. 

•	Print which doctor has made the most prescriptions: This code is written to join the prescriptions and doctors table, and show the name of the doctor with the most prescriptions. This could be useful for workload tracking. 

•	Print a list of doctors at the hospital with the biggest size: This code is written to join the doctors and hospitals table together, and rank the hospitals based on size, including the doctors that work at each hospital. 
