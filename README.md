
# Doctor_App

Welcome to the Doctor_App GitHub repository! This repository contains the source code for a web application that allows patients and doctors to interact and manage appointments. The application consists of two main entities: "Patient" and "Doctor".



## Frameworks and Language used

[![JAVA Docs](https://img.shields.io/badge/JAVA-v20.0.1-blue.svg)](https://docs.oracle.com/en/java/)
[![GPLv3 License](https://img.shields.io/badge/Spring_Boot-v3.0.6-yellow.svg)](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)


## Required Dependencies

To run this project, you will need to add the following dependencies to your pom.xml file

`Spring Web`,`Spring Boot Dev Tool`,`Lombok`,`Spring Data JPA`,`Validation`,`MySQL Driver`



## Controllers
### PatientController

The `PatientController` class contains methods related to patient functionality. Here are the available methods:

* `signUp`: This method is used by patients who are new to the application to sign up and provide their details.
* `signIn`: Patients can use this method to sign in to the application.
* `availableDoctors`: This method retrieves a list of available doctors for scheduling an appointment.
* `createAppointment`: Patients can use this method to book an appointment with a doctor.
* `cancelAppointment`: Patients can cancel their appointments using this method.

### DoctorController

The `DoctorController` class contains methods related to doctor functionality. Here are the available methods:

* `addDoctors`: Doctors can use this method to add their profiles to the application.
* `getMyAppointments`: Doctors can retrieve a list of all their appointments using this method.

## Data Structure used in project :
- List

## Contributing
If you'd like to contribute to the Doctor_App project, you can follow these steps:

    1. Fork the repository on GitHub.

    2. Clone your forked repository to your local machine.

    3. Create a new branch for your feature or bug fix.

    4. Make the necessary changes and additions in your branch.

    5. Commit and push your changes to your forked repository.

    6. Submit a pull request to the main repository, explaining your changes and why they should be merged.

    7. Wait for the repository maintainer to review your pull request. Feel free to address any questions or comments raised during the review process.

## Project Summary :

````
 Doctor_App is a web application designed to facilitate the interaction and management of appointments between patients and doctors. The application provides a platform where patients can sign up, schedule appointments, and cancel appointments, while doctors can add their profiles and view their appointment schedule.
 
````

