Team Skill-3 to develop **TEST PAPER GENERATOR**



# **DEFINING THE SYSTEM** #

---


# **1.0 Introduction** #

## **1.1 Purpose of Vision Document** ##

This document provides the current vision for the TEST PAPER GENERATOR system.

## **1.2 Product Overview** ##

Test Paper Generator(TPG Pro) will provide reliable and easy to use features for conducting test or quiz. This makes it convenient to devise a test paper with one's own selection of questions or randomly generate test paper from a question bank that has already been deployed and reserved in the database.  It works as an aid in avoiding redundant questions in the same test paper as well as reduces manual effort and utilization of paper to a large extent.

This system will beneficial to testing service provider by saving lots of time to develop multiple choice examinations or short question examination and  also useful to parents by generating mock test papers to set up exams for their children.

TPG Pro will have good functionality for generating test papers for an exam. Following features are included in this version.
  * Ability to create manual or automatic paper generation without repetition.
  * Provides immediate evaluation after completion of test.
  * Create numerous analytic reports


---


# **2.0 User Description** #

## **2.1 User/Market Demographics** ##

In the high-tech era of computers, paper based tests for generating test papers to each student separately are becoming to be a lot tedious, time consuming and the result in inaccurate evaluation.

We develop comprehensive system that recognizes the need for an assessment tool that offers you to create and manage test for educators and trainers.

TPG Pro will be the complete set of tools, come up with the bundle of applications which are integrated and work together to create, run and grade exams instantly and precisely. Also allows for generating test and exam with various highly configured test options.


## **2.2 User profiles** ##
![http://testpapergenerator.googlecode.com/files/user_profiles.jpg](http://testpapergenerator.googlecode.com/files/user_profiles.jpg)

## **2.3 User Environment** ##
**The system is proposed for following user environments:**
  * Academic/Educational institutes
  * Testing service providers

**From paper based to computer based system environment:**

The complete web-based solution provides easy user interface

**System platforms environment**

The system can support any of the windows based Operating System


## **2.4 Key User Needs** ##
![http://testpapergenerator.googlecode.com/files/key_user_need.jpg](http://testpapergenerator.googlecode.com/files/key_user_need.jpg)


---


# **3.0 Product Overview** #

## **3.1 Product Perspective** ##

  * TGP Pro will interface to the database to manage it via web server.
  * TPG Pro web enables test generation and maintaining database over window client server database.
  * The system administrator can define the users’ privileges like identification, authorization and authentication in to the system. According to their role, system will decide the access features of the system.
  * The system will divide in several modules based on privileges given to users. One module will be design for professors who can access and manipulate database question bank. Second will be design for test coordinators who can generate the test papers by using that database and third module will be for parents to setup mock tests for their children.
http://testpapergenerator.googlecode.com/files/product_overview.JPG

## **3.2 Product Position Statement** ##
![http://testpapergenerator.googlecode.com/files/product_position_statement.jpg](http://testpapergenerator.googlecode.com/files/product_position_statement.jpg)

## **3.3 Summary of Capabilities** ##
![http://testpapergenerator.googlecode.com/files/summary_capabilities.jpg](http://testpapergenerator.googlecode.com/files/summary_capabilities.jpg)

## **3.4 Assumptions and Dependencies** ##
  * Detail knowledge of all risks and issues
  * Detail knowledge of all changed request
  * Operating system must be installed: Windows 2000/XP Prof with service pack 2 or 3(32 bit or 64 bit)
  * Oracle 9.0 must be preinstalled
  * Web server : SUN JAVA system web server 7.0 with JDBC oracle connectivity
  * 1GB RAM, 160 GB Hard disk space

## **3.5 Cost and Pricing** ##
  * Starts at $399(For single user) depending on the features

---


# **4.0 Feature Attributes** #
![http://testpapergenerator.googlecode.com/files/FEATURE_ATTRIBUTE.jpg](http://testpapergenerator.googlecode.com/files/FEATURE_ATTRIBUTE.jpg)

---


# **5.0 Product Features** #

## **5.1 Critical Features** ##
  * Fea1 : Create a test without repetition of same question : To generate the random test paper without repetition of same question is very important feature of the system. As a test should not have the same question repeated again. An advanced algorithm will choose the random questions for the test without repetition

  * Fea4 : Immediate evaluation after completion of test : For particular questions types, web based test can provide immediate grading. According to the questions, answers are already been evaluated and recorded in the database. As soon as finished with the test can give you the immediate evaluation.

  * Fea7 : Secure Database : Users can access only particular database that assigned to them. The questions bank of particular subject should be protected to the unauthorized access.

  * Fe6 : Ability to support any OS environment : The software will support any OS environment Windows, Mac, Linux


## **5.2 Important Features** ##

  * Fea8 : Create paper or web based tests : Users can take print the generated test. Also can configure the web based test so students can login and appear for the test.

  * Fea10 : Creates numerous reports : Users can generates various reports like grade, test, item analysis, test performance


---


# **6.0 Use Cases** #

## **(1) Upload questionnaires** ##

**Brief Description:**

This feature allows educational staffs or professors to post their questionnaires in to the database. Also they can arrange those questionnaires by subject wise.

**System or Subsystems:**

TPG Pro, Personal Computer, internet connection, printer

**Flow of Events:**

  * Select the subject in which they have to upload their questions.
  * Write questionnaires and then submit them.
  * Database will automatically update.
  * Professors can also check the grades of students.
  * Also they can generate analytical reports that they want.

**Pre Condition:**

Professors must have to log in into the software system

**Post Conditions:**

TPG Pro will generate a confirmation message about database update.
If professors want, System will generate those reports for which they give requests.

## **(2) setup quiz** ##

**Brief Description:**

This feature allows Test coordinators to access database to retrieve data from question bank and can set up quizzes automatically or manually for specific subject.

**System or Subsystems:**

TPG Pro, Personal Computer, internet connection, printer

**Flow of Events:**

  * Select the subject in which they have to setup the quiz.
  * Test coordinator must have to select an option for setup quiz automatically or manually.
  * Test coordinator also will check the grades of students
  * Also they can generate analytical reports that they want.

**Pre Condition:**

Test coordinators must have to log in into the software system

**Post Conditions:**

TPG Pro System will generate test papers as per the selection of test coordinator.
If test coordinators want, System will generate those reports for which they give requests.

## **(3) setup mock test (Limited access to database)** ##

**Brief Description:**

This feature allows parents to access database to retrieve data from question bank and can set up quizzes automatically or manually for specific subject. But parents can only access limited questionnaires from the database.

**System or Subsystems:**

TPG Pro, Personal Computer, internet connection, printer

**Flow of Events:**

  * Select the subject in which they have to setup the quiz.
  * Parents must have to select an option for setup quiz automatically or manually.
  * Parents also will check the grade for that exam.

**Pre Condition:**

Parents must have to log in into the software system

**Post Conditions:**

TPG Pro System will generate test papers as per the selection of parents.
System will provide grade for that exam and also give solution for that.


---


# **7.0 Other Product Requirements** #

## **7.1 Applicable Standards** ##

  * TCP/IP, IEEE STD xx-xxxx for communication standards
  * Windows for platform compliance standards
  * UL, CMM, ISO for safety and quality standards

## **7.2 System Requirements** ##

  * Must be installed in Windows operating system (Windows 2000/XP professional/Vista with 32 bit or 64 bit)
  * 1GB RAM, 160 MB Hard disk space
  * Oracle 9.0 must be preinstalled

## **7.3 Licensing,Security and Installation** ##

  * There should be some terms and conditions set forth the rights being licensed to the customer for use of this software. These rights are the only rights customer has to the software, so if customer does not agree to the terms and conditions, then they cannot use it.
  * There is one or more years of warranty given under this terms and conditions.
  * By clicking “I Agree”, or by opening the file package containing in the Software, customer agree that this terms and conditions is a legally binding and valid contract, and further agree to take all necessary steps to ensure that the terms and conditions are not violated by any person or entity under customer’s control or in our service.
  * Licensor grants to you this license solely software to use in a single copy of the Software on a single computer or device for use by a single concurrent user only and solely provided that you adhere to all of the terms and conditions.
  * With complete features that are required by the software, it can be installed in the system with the given CD. Basic features can be installed by a naïve user and customer support help will also be provided.
  * First user will have to create a user id and password, which will be have a limited life.

## **7.4 Performance Requirements** ##

![http://testpapergenerator.googlecode.com/files/performance_requirement.jpg](http://testpapergenerator.googlecode.com/files/performance_requirement.jpg)


---


# **8.0 Documentation Requirements** #

## **8.1 User Manual** ##

This User Manual provides guidelines on how to cope up with the user-friendly interface of the TGP Pto system application. If you are signing up for the first time you need to enter a user id and password of your choice. Then a account will be created after verifying by the administrator. In case of any problem during registration that can be reported to the TGP Support Center (support@TGP.net) .The user manual will provide all the necessary information about how to register and how to use this software, describing each and every part of the software. It also describes the basic requirement of the system you are going to run on.

## **8.2 Online Help** ##

As mentioned earlier that so much care will be taken to ensure that user does not face any problem while or in future after using the software. So, specifically with customer care support, online help is also provided. You can access the main webpage as mentioned above. User can follow the links provided on the websites.


## **8.3 Installation Guides, Configuration, Read Me File** ##

A installation process is not recommended for the system but a connectivity between the graphical user interface and database must be performed in an improvised manner. Read Me File includes suggestions on how to use the system , and specifies each and every section of the system in detailed manner.
  * Welcome
  * Installing your TPS system
Building a graphical user interface , user-friendly interface which is the front end.
A database must be created which consists of all details of questionnaires.
Database connectivity must be maintained between GUI and database.

## **8.4 Labeling and Packaging** ##

  * The system will be delivered by our representatives that will also train users to operate the system
  * All terms and licenses have to be signed before the system is in use


---


# **9.0 Glossary** #

## **9.1 TPG (Test Paper Generator)** ##

This is software which generates test papers for conducting examinations. It can be used as a plug-in or executable file for conducting any kind of exam, be it online test or any general paper test. This makes it convenient to devise a test paper with one's own selection of questions or randomly generate test paper from a question bank that has already been deployed and reserved in the database.

## **9.2 Academic/Educational staffs** ##

They can make up questionnaires for specific topic & store in database. So at the  time of examinations software will automatically generates random questions for the test.

## **9.3 Test coordinators** ##

They can retrieve questions for the Multiple Choice Questions (MCQ) examinations and the Short Answer Question (SAQ) written examinations, participating in standard setting activities and marking examination papers against established criteria.

## **9.4 Database privileges** ##

These are kind of rights given to the users according to their different roles to access database. Professors will get most of the database rights while test coordinators will get only some of them.

## **9.5 Questionnaires** ##

These are the set of questions stored by professors in the database.

## **9.6 Question bank** ##

Question bank is the database in which all the data will be stored or accessed by professors and test coordinators will use those questions to set up quiz paper. The database relies upon system to organize the storage of questionnaires.