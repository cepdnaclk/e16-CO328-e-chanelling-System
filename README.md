___
# E-Channeling System
___

![](https://www.techringe.com/wp-content/uploads/2019/08/Doctor1.png)

## Group 13
E/16/127 - Yoshith Harshana

E/16/039 - Nimashi Uthpala

E/16/087 - Sachini Dissanayaka

___
## Introduction
An online doctor appointment booking system can prove to be a boon to doctors and patients alike. For those among us who have seen the waiting room of busy doctors, it will draw memories of patients and their attendants crowding around the receptionist. It was not necessarily first-in and first-out. Many times it was based on who was able to throw their weight around and seize the opportunity to stride in to meet the doctor even before the earlier patient had walked out. In some cases, tokens were given out that represented our number in the queue.

The wait could be quite long and if the patient was not quick to mark her presence when called out it could mean a further wait. Patients being sick, there was always a high probability of the attendants also falling sick as everyone was crowding around each other. This evolved to a telephone-based appointment booking, mainly managed on paper. It was hardly flexible. No-shows were very common. With the advent of Personal Computers, appointments were maintained on the desktop. This certainly brought more orders, however, appointments still required the patient to phone the receptionist to book the appointment. Widespread use of mobile phones and the internet has driven the need for doctors to offer the facility of online appointment booking – a far superior option for both doctors and patients. The aim of this project is to create a system that handles doctor-patient management system that will doctors on their works and will also help the patients to book doctor appointments and view medical progress. 

## System Description
The E-channeling system has a listing of doctors. When a patient needs an appointment urgently but sees that their doctor is fully booked, they may look at the schedules of other available doctors at a specific hospital instead of turning to the competitor. Also, doctors have the ability to check their appointments and patient details using the application.
Administrators act as authorities of the system they have the ability to enter the doctors into the system and handle the patients and the payments, appointments, and maintenance of the system

Doctor Listings
Doctor listings help patients find the doctors with the needed qualifications. The channeling system has an effective filter feature so that patients don’t waste time scrolling through all the doctor profiles. Patients may want to search for specific types of treatment, expertise, positive feedback, location, etc.

Patient Profile
It is not only doctors who have to share information about themselves. Patient profiles also contain their electronic health record, results from various examinations, and lab tests. The administrator has the authority to update and attach documentation to patient profiles. 

### UML Activity Diagram
This E- Channeling  system involved three actors,

Doctor

Administrator

Patient

Use cases for the Actors are as follows

Doctor - 
Create Appointment,
Check Patient Details.
Add description,
View his/her profile

Administrator - 
Manage doctors,
Manage Patients,
Manage Appointment,
View feedbacks

Patient - 
Check Doctors,
View profile,
Check Appointment,
Make feedback,


![](https://user-images.githubusercontent.com/67429062/139879107-aa34cb64-72ab-420f-bdfd-80efb4b6042f.png)

### Flow Chart

![](https://user-images.githubusercontent.com/67429062/139879514-0c5c6fc2-1a9c-4a3f-aa55-0d8f595c4510.png)
![](https://user-images.githubusercontent.com/67429062/139879544-ba8677d2-2105-474b-a7c3-35ed71302eba.png)


### ER  Diagram 

![](https://user-images.githubusercontent.com/67429062/139880347-e2784de8-670f-4ec3-8fec-72557bf3d0f5.png)

## Software design

For the patient

The patient should add some important information to register for the system. Then the patient can login to the system by using the entered email address and the password 

After login to the system patient can search for the doctors, make an appointment, and can add feedback.

![patient-registration](https://user-images.githubusercontent.com/67429062/139880634-c7a79ec6-bd7b-4f1d-88c6-5b2dfa417a8d.png)

![patient-login](https://user-images.githubusercontent.com/67429062/139880750-81c191d0-b514-4ddb-bc29-6824ff3d090f.png)
![Change Password](https://user-images.githubusercontent.com/67429062/139880855-97ff3b41-d589-45ce-81fc-33a96669eaa1.png)





For the Administrator

Administer can add doctors, view doctors and patients, view appointments and view feedback.
![Image 20](https://user-images.githubusercontent.com/67429062/139881778-8dbec1b8-da17-41ad-8874-f8411f6bccb7.png)
![Image 24](https://user-images.githubusercontent.com/67429062/139881624-dbb3c0a2-5ac3-4de3-a668-de7c0acfae4f.png)

For doctors

After registering for the system, doctors can view his/her appointment details, patient details and can edit their profiles.



![Image 18](https://user-images.githubusercontent.com/67429062/139882358-1f42bab6-242a-4aa8-8405-44623aa67193.png)

![Image 17](https://user-images.githubusercontent.com/67429062/139882435-a59a0923-90ba-4033-9d7f-074ebf66b737.png)


## Testing
For the testing, we generate a set of data,  which can be used to test the new system before accepting it. In the test generation phase, all the parts come which are to be tested to ensure that system does not produce any error. If there are some errors then we remove them and further it goes for accepting.

Login Information System 

This system will maintain the login information of its user to enter in the software
 - Validation
Administrators need to login using the unique id and password

Contact number should have 10 digits

All the details must be filled up

Email address should be in the proper format

Login information should be filled in before the user allowed

- Error handling
 - 
If the user doesn’t fill up validated information then the system displays an error message for the user and request to enter the validation information.


Performance required

- Security
- 
The system should be Protected from unauthorized access Where the valid Username and Password are required so no other can access it. 
The system is tested according to the above features.

## Used Technologies

- HTML

MySQL Workbench is a unified visual tool for database architects, developers, and DBAs. MySQL Workbench provides data modeling, SQL development, and comprehensive administration tools for server configuration, user administration, backup, and much more. MySQL Workbench is available on Windows, Linux, and Mac OS X.

- CSS

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript. CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate CSS file and reduce complexity and repetition in the structural content.

- Java Script

JavaScript often abbreviated as JS, is a high-level, interpreted programming language. It is a language that is also characterized as dynamic, weakly typed, prototype-based, and multi-paradigm. Alongside HTML and CSS, JavaScript is one of the three core technologies of the World Wide Web. JavaScript enables interactive web pages and thus is an essential part of web applications. The vast majority of websites use it, and all major web browsers have a dedicated JavaScript engine to execute it.

- Mysql

MySQL Workbench is a unified visual tool for database architects, developers, and DBAs. MySQL Workbench provides data modeling, SQL development, and comprehensive administration tools for server configuration, user administration, backup, and much more. MySQL Workbench is available on Windows, Linux, and Mac OS X.

- Xampp

XAMPP is a free and open-source cross-platform web server solution stack package developed by Apache Friends, consisting mainly of the Apache HTTP Server, MariaDB database, and interpreters for scripts written in the PHP and Perl programming languages. XAMPP stands for Cross-Platform (X), Apache (A), MariaDB (M), PHP (P), and Perl (P). It is a simple, lightweight Apache distribution that makes it extremely easy for developers to create a local web server for testing and deployment purposes. Everything needed to set up a web server – server application (Apache), database (MariaDB), and scripting language (PHP) – is included in an extractable file. XAMPP is also cross-platform, which means it works equally well on Linux, Mac, and Windows. Since most actual web server deployments use the same components as XAMPP, it makes transitioning from a local test server to a live server extremely easy as well.

- Php

Hypertext Preprocessor (or simply PHP) is a server-side scripting language designed for Web development but also used as a general-purpose programming language. It was originally created by Rasmus Lerdorf in 1994,] the PHP reference implementation is now produced by The PHP Group. PHP originally stood for Personal Home Page, ] but it now stands for the recursive acronym PHP: Hypertext Preprocessor. 

PHP code may be embedded into HTML code, or it can be used in combination with various web template systems, web content management systems, and web frameworks. PHP code is usually processed by a PHP interpreter implemented as a module in the web server or as a Common Gateway Interface (CGI) executable. The web server combines the results of the interpreted and executed PHP code, which may be any type of data, including images, with the generated web page. PHP code may also be executed with a command-line interface (CLI) and can be used to implement standalone graphical applications. 

- Boostrap

Bootstrap is a free and open-source front-end framework for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation, and other 6 interface components, as well as optional JavaScript extensions. Unlike many web frameworks, it concerns itself with front-end development only.

- VS code




















