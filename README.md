
# HealthMate – Electronic Health Record & Medicine Reminder System

## Overview

HealthMate is a web-based healthcare management application designed to simplify the management of patient medical records and medicine reminders. The system connects patients, doctors, laboratories, and users on a single platform, allowing secure access to healthcare information anytime.

The application enables:

* Patients to upload and manage medical records.
* Doctors to access prescriptions and patient reports.
* Laboratories to upload test reports.
* Users to set medicine alarms and reminders.

The project is developed using Java-based enterprise technologies with MVC architecture.

---

# Features

## Patient Module

* Patient registration and login
* Upload prescriptions and medical reports
* View uploaded reports and prescriptions
* Set medicine reminder alarms
* Access medical history anytime

## Doctor Module

* Doctor login and dashboard
* View patient prescriptions
* Upload prescriptions and reports
* Access patient medical records

## Laboratory Module

* Laboratory login and dashboard
* Upload test reports
* View patient prescriptions
* Maintain laboratory records

## User Management

* Secure authentication system
* Change password functionality
* Role-based access control

---

# Tech Stack

## Backend

* Java
* Spring MVC
* Hibernate ORM
* Maven

## Frontend

* JSP
* HTML5
* CSS3
* Bootstrap
* JavaScript

## Database

* MySQL

## Server

* Apache Tomcat

---

# Project Structure

```bash
HealthMate/
│── src/main/java/com/davv/
│   ├── controller/
│   ├── dao/
│   ├── entities/
│   ├── model/
│   └── services/
│
│── src/main/resources/
│   └── hibernate.cfg.xml
│
│── src/main/webapp/
│   ├── resources/
│   ├── views/
│   └── WEB-INF/
│
│── pom.xml
```

---

# Architecture

The application follows the MVC (Model-View-Controller) architecture:

* **Model** → Handles business logic and database entities.
* **View** → JSP pages used for user interface.
* **Controller** → Handles user requests and responses.

Hibernate ORM is used for database connectivity and object-relational mapping.

---

# Main Components

## Controllers

* `DoctorController.java`
* `PatientController.java`
* `LabController.java`
* `UserController.java`
* `WebController.java`

## Services

* `AlarmService.java`
* `MedicalRecordService.java`
* `LabRecordService.java`
* `FileUploadService.java`
* `UserService.java`

## Entities

* Doctor
* Patient
* Laboratory
* MedicalRecord
* MedicineAlarm
* PatientDocument
* User

---

# Installation & Setup

## Prerequisites

Make sure the following software is installed:

* Java JDK 8 or above
* Apache Tomcat
* Maven
* MySQL
* Eclipse/IntelliJ IDE

---

## Clone the Repository

```bash
git clone https://github.com/your-username/HealthMate.git
```

---

## Database Configuration

1. Create a MySQL database.
2. Update database credentials inside:

```bash
src/main/resources/hibernate.cfg.xml
```

Example:

```xml
<property name="hibernate.connection.url">jdbc:mysql://localhost:3306/healthmate</property>
<property name="hibernate.connection.username">root</property>
<property name="hibernate.connection.password">your_password</property>
```

---

## Build the Project

```bash
mvn clean install
```

---

## Run the Application

1. Deploy the project on Apache Tomcat.
2. Start the Tomcat server.
3. Open browser:

```bash
http://localhost:8080/HealthMate/
```

---

# Screens Included

* Home Page
* Login Page
* Registration Page
* Patient Dashboard
* Doctor Dashboard
* Laboratory Dashboard
* Upload Reports Page
* Medicine Reminder Page

---

# Future Enhancements

* Email and SMS notifications
* Online appointment booking
* AI-based health suggestions
* Mobile application integration
* Cloud storage support
* Video consultation feature

---

# Advantages

* Centralized healthcare management
* Easy access to patient records
* Secure data handling
* Improved communication between patients and doctors
* Medicine reminder support for better healthcare management

---

# Learning Outcomes

Through this project, the following concepts were implemented:

* Spring MVC Architecture
* Hibernate ORM
* Database connectivity
* File upload handling
* Session management
* Authentication and authorization
* JSP and Bootstrap UI development

---

# Author

**Sakshi Parmar**

Java Backend Developer

Skills:

* Java
* Spring MVC
* Hibernate
* JSP & Servlet
* MySQL
* Bootstrap

---

# License

This project is developed for educational and learning purposes.
