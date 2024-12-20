<p align="right">

BSc Hospital system 
CS Department  
Project ID: UQU-CS-2024-10  
October 2024 
</p>


<p align="center">
<img src="https://example.com/hospital_logo.png" width="200"> <!-- Replace this link with the hospital logo -->
</p>

<h1 align="center">Hospital Information System Report</h1>

<h3 align="center">Patient and Administration Information System</h3>

<h2 align="center">Author: Computer science students </h2>

<p align="center">

Dept. of Computer Science  
Faculty of Computer in AL-Lith Branch
Umm Al-Qura University, KSA

</p>



<!-- Page Break -->



*Submitted to the Computing at Umm Al-Qura University in partial fulfillment of the requirements for the degree of Bachelor of Science in Computer Science.*

## Authors

* *Name:* Fahad Bandar Fahad Shawoush
* *Address:* 444008375
* *Email:* fbndr708@gmail.com
* *Name:* Jasser Zeyad Al-aqqad
* *Address:* 444001576
* *Email:* gaseraz150@gmail.com
* *Name:* Ammar Mohammed Mari
* *Address:* 444009991
* *Email:* amhm840@hotmail.com
* *Name:* Sami Husni Al-Ruhili
* *Address:* 444007928
* *Email:* samyalruhili@gmail.com
* *Name:* Yazeed Ahmed Aljuawybiri
* *Address:* 444003076
* *Email:* s444003076@st.uqu.edu.sa
* *Name:* Osama bandar ALahmadi
* *Address:* 444008572
* *Email:* Askosamabandar@gmail.com

## University supervisors:

* *Ali Abdulaziz Khader Al-Zubaidi*
* Department Computing

### Dept. of Computing
Faculty of Computer in Al-Lith Branch
Umm Al-Qura University
Internet: http://uqu.edu.sa
Phone: +966 56 358 4937
Fax: +966 56 358 4937
Kingdom of Saudi Arabia



<!-- Page Break -->



# Intellectual Property Right Declaration

This is to declare that the work under the supervision of Dr. Ali Abdul Aziz Khader Al-Zubaidi titled Hospital Information System Report which was implemented as part of the requirements of Bachelor of Computer Science in the College of Engineering and Computer Science is the exclusive property of Umm Al-Qura University and the concerned supervisor and is protected by intellectual property rights laws and agreements. It can only be considered/used for purposes such as expansion for further improvement, product development, adoption of commercial/organizational use, etc., with the permission of the university and the concerned supervisor.

This above statement applies to all students and faculty members.

**Date:** 14/10/2024

## Authors:

- **Name:** Fahad Bandar Fahad Shawoush **Signature:** ____________________

- **Name:** Yazeed Ahmed Aljuawybiri **Signature:** ____________________

- **Name:** Jasser Zeyad Al-aqqad **Signature:** ____________________

- **Name:** SAMI HUSNI ALRUHILI **Signature:** ____________________

- **Name:** Ammar Mohammed Mari **Signature:** ____________________

- **Name:** Osama bandar ALahmadi **Signature:** ____________________



<!-- Page Break -->



# Anti-Plagiarism Declaration 
This is to declare that the above publication, produced under the supervision of Dr. Ali Abdul Aziz Khader Al-Zubaidi, and titled Hospital Information System Report, is the sole contribution of the author(s). No part hereof has been reproduced illegally (cut and paste) which can be considered as Plagiarism. All referenced parts have been used to argue the idea and

have been cited properly. I/We will be responsible and liable for any consequence if violation of this declaration is

proven. **Date:** 16/10/2024

 **Authors:**
- **Name:** Fahad Bandar Fahad Shawoush **Signature:** ____________________

- **Name:** Yazeed Ahmed Aljuawybiri **Signature:** ____________________

- **Name:** Jasser Zeyad Al-aqqad **Signature:** ____________________

- **Name:** SAMI HUSNI ALRUHILI **Signature:** ____________________

- **Name:** Ammar Mohammed Mari **Signature:** ____________________

- **Name:** Osama bandar ALahmadi **Signature:** ____________________



<!-- Page Break -->



# Acknowledgments

*We would like to extend our deepest gratitude to the founders of this project. Their vision, leadership, and dedication have been the driving force behind the development of this Hospital Information System. Without their continuous support and belief in the project's mission, this work would not have been possible.*

*Special thanks to the development team, healthcare professionals, and hospital staff whose invaluable contributions have made this project a reality.*



<!-- Page Break -->



# ABSTRACT

The Hospital Information System (HIS) is designed to optimize healthcare operations, streamline patient management, and improve communication between various hospital departments. This system aims to provide a comprehensive solution that enhances patient care, automates routine administrative tasks, and ensures secure handling of medical records. With the integration of scheduling, billing, and reporting functionalities, HIS will contribute to the efficiency and effectiveness of hospital workflows. This project leverages modern web-based technologies to deliver an intuitive and scalable solution that meets the dynamic needs of the healthcare environment.

**Keywords**: Hospital Information System, patient management, healthcare automation, medical records



<!-- Page Break -->



# TABLE OF CONTENTS

1. Introduction  
    1.1 Purpose of the Project  
    1.2 Purpose of this Document  
    1.3 Overview of this Document  
    1.4 Existing System

2. System Analysis  
    2.1 Data Flow and Processes  
    2.2 System Requirements  
    2.3 Proposed Solutions  
    2.4 Alternative Solutions Considered

3. System Design  
    3.1 Design Constraints  
    3.2 Architectural Design  
    3.3 Database Design

4. Implementation  
    4.1 Development Tools and Technologies  
    4.2 Key Milestones

5. Testing and Validation  
    5.1 Testing Methods  
    5.2 Validation

6. Maintenance and Future Enhancements  
    6.1 Maintenance Plan  
    6.2 Future Enhancements

7. Use Cases  
    7.1 Use Case 1: Billing System  
    7.2 Use Case 2: Laboratory Results

8. User Interfaces  
    8.1 Administrator Dashboard  
    8.2 Doctor's Dashboard  
    8.3 Appointment Scheduling Interface

9. Acknowledgments

10. Abstract



<!-- Page Break -->



# Software Requirements Specification (SRS) for Hospital Information System


## Chapter 1: Introduction
    

### 1.1 Purpose of the Project

The goal of this project is to design and develop a **Hospital Information System (HIS)** that will facilitate hospital management processes by centralizing patient information, enhancing interdepartmental communication, and improving patient care services. The system will aim to automate key hospital functions such as patient registration, medical record maintenance, appointment scheduling, billing, and reporting.

The HIS will also provide secure and easy access to patient data for doctors, nurses, and administrative staff while ensuring compliance with healthcare regulations. This will allow hospital staff to deliver timely and efficient care, reduce administrative overhead, and improve overall hospital efficiency.


### 1.2 Purpose of this Document
This document provides a detailed outline of the functional and non-functional requirements, as well as the overall system architecture, that developers and stakeholders will need to follow during the development lifecycle. It defines the scope of the project, user interactions, system behavior, performance benchmarks, and future scalability considerations.

The document will act as the primary reference for:
- **Developers**: To understand the functionalities and features they need to implement.
- **System Testers**: To ensure all system components function as specified.
- **Stakeholders**: To validate the project scope and objectives.

### 1.3 Overview of this Document
This document is structured according to the stages of the Software Development Life Cycle (SDLC), and includes the following sections:
- **Chapter 1**: Introduction
- **Chapter 2**: Overall Description of the System
- **Chapter 3**: Functional Requirements
- **Chapter 4**: Non-Functional Requirements
- **Chapter 5**: System Models and Diagrams
- **Chapter 6**: Additional Considerations (Legal, Safety, Constraints)


### 1.4 Intended Audience and Reading Suggestions
The intended audience for this document includes:
- **Developers**: To refer to system requirements and technical specifications.
- **Project Managers**: To track the progress of system design and implementation.
- **Hospital Administrators and Stakeholders**: To ensure that the system aligns with organizational objectives and patient care goals.
- **System Testers**: To validate functionality and performance benchmarks.

Each section of the document provides progressively detailed information, beginning with an overview of the system requirements and moving into the specifics of each module.



<!-- Page Break -->



## Chapter 2: Overall Description

### 2.1 Product Perspective

The **Hospital Information System (HIS)** is a comprehensive solution designed to automate and optimize various hospital functions such as patient registration, medical record keeping, appointment scheduling, billing, and reporting. The system will operate on a cloud-based infrastructure to allow scalability and flexibility in data access.

The system is built with modularity in mind, meaning that additional features or functionalities can be added later with minimal disruption. For example, if the hospital wants to introduce telemedicine or an AI-based diagnostic tool, these modules can be integrated with the HIS.


#### External Interfaces
- **Users**: Doctors, nurses, administrative staff, and patients will interact with the system via user-friendly graphical interfaces.
- **Third-Party Systems**: The HIS will integrate with external systems such as **Electronic Health Records (EHR)**, **Laboratory Information Management Systems (LIMS)**, and **Insurance Platforms**.
- **Hardware Interfaces**: The system will interface with hospital devices such as biometric scanners, card readers, and laboratory equipment for automated data input.

### 2.2 Product Features
The HIS will include the following features:

#### 2.2.1 **Patient Management**
- **Patient Registration**: Allow hospital staff to capture detailed patient information, including demographic data, insurance, and medical history.
- **Search Functionality**: Staff can quickly retrieve patient records using various search filters (e.g., patient ID, name, date of birth).


#### 2.2.2 **Appointment Management**
- **Doctor Scheduling**: Doctors' calendars can be managed, showing their availability for appointments and operations.
- **Patient Notifications**: Automated notifications and reminders sent via email or SMS to patients before their scheduled appointments.


#### 2.2.3 **Medical Records Management**
- **Storage of Health Records**: Securely store and manage all patient health records, including test results, diagnoses, and treatment plans.
- **Doctor's Notes**: Doctors can update patient records with diagnoses, medications, and other observations in real-time.


#### 2.2.4 **Billing and Payment**
- **Automated Billing**: Generate accurate bills based on the services rendered, medications prescribed, and diagnostic tests performed.
- **Integration with Insurance**: The system will support automated insurance claims, including verification of patient coverage and processing of payments.


#### 2.2.5 **Reporting and Analytics**
- **Reports Generation**: Generate detailed reports on patient admissions, financial performance, resource utilization, and doctor activity.
- **Analytics Dashboard**: Provide real-time data analytics for hospital administrators to monitor key performance indicators (KPIs).


### 2.3 User Classes and Characteristics

The system will serve different types of users with varying levels of access and functionality:

- **Doctors**: Full access to medical records, appointment schedules, and diagnostic tools.

- **Nurses**: Access to patient care plans, medication schedules, and doctor’s instructions.

- **Administrative Staff**: Manage appointments, billing, and insurance claims.

- **Patients**: Limited access to their medical history, appointments, and billing information via a secure patient portal.



<!-- Page Break -->



## Chapter 3: Functional Requirements

### 3.1 Patient Registration and Management

#### Functional Requirement 1: **Patient Registration**
- The system shall allow the receptionist to register a new patient by entering their name, date of birth, address, and insurance information.
- The system shall automatically generate a unique patient ID upon registration.


#### Functional Requirement 2: **Search and Update Patient Data**
- The system shall allow hospital staff to search for patients using various filters such as name, ID, or date of birth.
- Authorized users shall be able to update patient records with new diagnoses, medications, and lab results.


### 3.2 Appointment Scheduling

#### Functional Requirement 3: **Doctor Availability**
- The system shall display the availability of doctors and allow patients to schedule or reschedule appointments.
- The system shall send automated email/SMS notifications to patients to remind them of their upcoming appointments.



### 3.3 Medical Records Management

#### Functional Requirement 4: **Medical Record Storage**
- The system shall securely store all patient medical records, including diagnoses, medications, treatments, and lab results.
- The system shall allow authorized users (doctors, nurses) to add new information to a patient’s record.

### 3.4 Billing and Financial Management

#### Functional Requirement 5: **Billing and Invoice Generation**
- The system shall generate an invoice for each patient based on the services rendered during their visit.
- The system shall provide an online payment option and track payment status.



### 3.5 Reporting Tools

#### Functional Requirement 6: **Reports**

- The system shall allow administrators to generate custom reports on patient admissions, financial data, and doctor performance.



<!-- Page Break -->



## Chapter 4: Non-Functional Requirements


### 4.1 Performance Requirements

- The system must be capable of handling at least 500 concurrent users without any significant degradation in performance, ensuring smooth access and operation during peak hours.
- The response time for most critical actions, such as retrieving patient records, scheduling appointments, and updating medical records, must not exceed 3 seconds.
- Database queries related to patient records, billing, and scheduling should execute in under 1 second on average to maintain a seamless user experience.
- The system shall log performance metrics, including response times, error rates, and server load, for ongoing monitoring and optimization.

### 4.2 Security Requirements
- All patient data in transit must be encrypted using SSL/TLS protocols to protect against unauthorized access during transmission.
- Sensitive data, including personal and medical records, shall be stored securely with encryption algorithms such as AES-256 to comply with HIPAA and other data protection regulations.
- The system shall require multi-factor authentication (MFA) for administrative access and medical personnel, adding an extra layer of security to critical data and system operations.
- Regular security audits must be conducted, with vulnerability scanning and penetration testing, to identify and mitigate potential threats.
- Access to patient records shall be role-based, with different levels of access permissions assigned to different roles (e.g., receptionist, doctor, administrator) to minimize unauthorized access.

### 4.3 Scalability Requirements
- The system must be scalable both vertically and horizontally to support the hospital’s growth, accommodating a potential doubling of user base over the next 5 years.
- The system architecture should support the seamless integration of additional modules, such as Telemedicine, Lab Reports, or Pharmacy Management, as required by future hospital expansions.
- Cloud hosting and containerization technologies shall be used to ensure flexible scaling, allowing new resources to be added as demand increases.
- Database capacity should be easily expandable to store increasing volumes of patient records, medical histories, and appointment data without compromising performance.

### 4.4 Usability Requirements
- The system shall provide an intuitive and user-friendly interface, designed with simplicity to minimize the learning curve for hospital staff of varying technological proficiency.
- Interactive tutorials and a comprehensive help section shall be integrated to assist users with initial navigation and usage.
- The interface must be accessible, with compliance to WCAG (Web Content Accessibility Guidelines) standards to support users with disabilities.
- The system must include features to allow personalization and customization for each user’s workflow preferences, such as saving commonly used settings or shortcuts.



<!-- Page Break -->



### 5.1 Use Case Diagrams

- **Use Case 1: Patient Registration**
  - **Actors**: Receptionist
  - **Preconditions**:
    - The receptionist is logged into the Health Information System (HIS) with appropriate permissions.
    - Required patient information (personal, contact, and medical history) is available for entry.
  - **Postconditions**:
    - A new patient profile is created in the system, assigned a unique ID for future reference.
    - Confirmation of the registration is displayed to the receptionist and stored in the system log.

  - **Main Flow**:
    1. The receptionist accesses the patient registration form via the system’s main interface.
    2. The receptionist enters personal information (e.g., name, date of birth, contact details).
    3. The receptionist provides medical information as required (e.g., medical history, allergies, and current medications).
    4. The receptionist submits the form.
    5. The system validates the information, checking for completeness and consistency.
    6. A new patient record is created and assigned a unique ID, stored in the Patient Database.
    7. The system confirms the successful registration and provides the patient ID for future reference.


- **Use Case 2: Appointment Scheduling**
  - **Actors**: Patient
  - **Preconditions**:
    - The patient has an existing account and is logged into the HIS system.
    - The doctor’s schedule is up-to-date and reflects current availability.
  - **Postconditions**:
    - The appointment is successfully booked, and the doctor’s schedule is updated to reflect the new booking.
    - A confirmation of the appointment is sent to the patient via email or SMS.

  - **Main Flow**:
    1. The patient navigates to the appointment scheduling section within the HIS.
    2. The patient selects a doctor from the available list and chooses a suitable time slot based on availability.
    3. The patient confirms the appointment details, including date, time, and doctor selection.
    4. The system verifies the time slot’s availability to prevent double booking.
    5. The doctor’s schedule is updated to include the new appointment.
    6. The system sends an appointment confirmation to the patient, with details and a reminder.

### 5.2 Data Flow Diagrams
- **Level 0 DFD**: Health Information System Overview
  - **Entities**: Patients, Doctors, Administrative Staff, Billing System
  - **Processes**:
    1. Patient Registration
    2. Appointment Scheduling
    3. Medical Records Management
    4. Billing and Payment Processing
    5. Reporting and Analytics

  - **Data Stores**:
    - Patient Database
    - Appointment Database
    - Medical Records Database
    - Billing Database

  - **Flow**:
    - Patients submit their information to the system for registration, appointments, and updates.
    - Doctors access and update patient records as part of diagnosis and treatment.
    - Administrative staff manage billing, records, and generate reports.
    - The billing system processes payments and maintains billing history for each patient.



- **Level 1 DFD**: Patient Registration Process
  - **Entities**: Receptionist, Patient, HIS System
  - **Processes**:
    1. Collect Patient Information
    2. Validate Information
    3. Create Patient Record
  - **Data Stores**:
    - Patient Database 

  - **Flow**:
    -The receptionist collects both personal and medical information directly from the
     patient.
    -The system validates the provided information, checking for accuracy and
    completeness against existing records to avoid duplicates.
    -Upon successful validation, a new patient record is created in the Patient Database.
    -The system sends a confirmation notification to the receptionist, completing the
      registration process.



<!-- Page Break -->



## Chapter 6: Additional Considerations


### 6.1 Legal and Compliance Requirements
To ensure the system complies with healthcare regulations like **HIPAA** in the United States, additional steps must be taken to protect the confidentiality and security of patient data. These steps include:

- **Data Encryption**: Data should be encrypted both in transit (between devices and over the network) and at rest to ensure unauthorized parties cannot access it.
- **Access Control**: Access control mechanisms should be in place, allowing only authorized personnel to access patient information.
- **Logging and Auditing**: Accurate records should be kept for all data access attempts. A monitoring system should be in place to detect any unauthorized access to patient data.
- **Staff Training**: Regular training for employees on secure data handling and awareness of potential cybersecurity threats.

### 6.2 Safety Requirements
To enhance security and protection, additional safety requirements could include the following:

- **Frequent Backups**: Adding extra backup intervals, such as every 6 hours, for critically important data.
- **Testing the Disaster Recovery Plan**: Disaster recovery plans should be periodically tested to ensure effectiveness, including testing backups and data retrieval in a controlled environment.
- **Update Management**: Ensuring all updates occur after business hours to minimize system impact and prevent data loss or system disruption during updates.


### 6.3 Constraints
Due to the system constraints, such as the hospital’s existing infrastructure, additional considerations may be required:

- **Bandwidth Management**: To prevent backup or data transfer processes from impacting overall system performance, a dedicated bandwidth should be allocated to the system.
- **Remote Support**: Given the limited on-site IT staff, remote support may be useful to resolve issues beyond the team’s capacity.
- **Priority-Based System Segmentation**: Prioritizing IT solutions for high-priority cases to ensure that available resources are used effectively.

<!-- Page Break -->
