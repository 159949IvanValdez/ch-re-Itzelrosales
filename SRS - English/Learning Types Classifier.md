
# Introduction

This document explains and analyzes the requirements and processes of the project "LTC" (Learning Types Classifier), developed by a university student of Software Engineering Career.

  ## Purpose
  
  The purpose of this document is to describe the general functioning of the LTC project, which is defined as a software solution to the problem of classifying the types of learning of children in the basic education degree.

  This solution will provide greater ease, speed and efficiency to the process of identification of types of learning because with its implementation will be possible to reduce the time, material cost and errors in the process. In addition, the information collected may be easy to access and retrieve for later uses.

  
  ## Scope  
  
  The system has the name “Learning Types Classifier” because it is basically designed to identify and classify the types of learning of children of basic education according to their preferences.

  LTC will be a useful tool for teachers at Plan de Iguala Elementary School in this identification process; will be responsible for handling student data including a description of their profile according to their interests, tips and techniques to achieve better learning and, of course, information about the type of learning they have.

  The main beneficiary with the LTC will be the academic institutions that implement it. The objective of using this system is to optimize processes in time and material resources.
 
 
  ## Definitions, acronymus, and abbreviations
    
  - LTC: Learning Types Classifier. 
  
  - SRS (Software Requirements Specification): Is a description of a software system to be developed. 
  
  - Database: Organized collection of data.
  
  - Data: Is information that has been translated into a form that is efficient for movement or processing.
  
  - User: Is any individual who is not involved with supporting or developing a computer or service.
  
  - Requirement: Is a specification of a need or want.
  
  - Project: Is an undertaking with specific start and end parameters designed to produce a defined outcome, such as implementing a new computer system.
  
  - Process: Is a series of steps and decisions involved in the way work is completed. 
  
  - System: Is a collection of elements or components that are organized for a common purpose.
  
  - Data exchange protocols: Is a support manual intended to guide the consistent implementation of the Data Exchange Framework. 
  
  - Interface: Is a shared boundary across which two or more separate components of a computer system exchange information.
  
  - Stability: The quality, state, or degree of being stable.
  
  - Availability: Refers to the ability of a user to access information or resources in a specified location and in the correct format.
  
  - Efficiency: Signifies a level of performance that describes using the least amount of input to achieve the highest amount of output.
  
  - Computer crimes: Is an act performed by a knowledgeable computer user, sometimes referred to as a hacker that illegally browses or steals a company's or individual's private information.
  
  
  ## References
  
  https://en.wikipedia.org/wiki/Software_requirements_specification
  
  https://www.techopedia.com/definition/1185/database-db
  
  https://searchdatamanagement.techtarget.com/definition/data
  
  https://www.computerhope.com/jargon/u/user.htm
  
  https://simplicable.com/new/requirement-definition
  
  https://searchcio.techtarget.com/definition/project-management
  
  https://www.processmodel.com/blog/what-is-a-process/
  
  https://searchwindowsserver.techtarget.com/definition/system
  
  https://dex.dss.gov.au/data-exchange-protocols/dex_data_exchange_protocols/
  
  https://en.wikipedia.org/wiki/Interface_(computing)
  
  https://www.merriam-webster.com/dictionary/stability
  
  https://www.techopedia.com/definition/990/availability
  
  https://www.investopedia.com/terms/e/efficiency.asp
  
  https://www.computerhope.com/jargon/c/compcrim.htm
  
  ## Overview
  
  The SRS document for the LTC project is divided into the following sections:
  
  • The introduction section that focuses on the explanation, objectives and description of the document.
  
  • The overall description section oriented to the general description of the system, where the information is directed to the client or potential user.
  
  • The specific requirements section that talks about the specific requirements. This includes technical terms directed principally to the developers and programmers of the project.
  
  • The support information section contains the appendices and links of information related to the topic for general interest.

  
# Overall Description

In this section we identify the factors that affect the product and its requirements, as well as the context of the development of the system. These can be related to the development time by phases, costs and customer involvement.


  ## Product Perspective
  
  The LTC system is made up of different functions, among them a classifier that will give a result depending on the descriptive data (name, age, preferences (answers to previously asked questions)) that the user enters in it.

This software will also allow the management of student information, in this case the learning profiles, advice and study techniques suitable for this, for which it will need to communicate with a database to which would only have access the director of the institution or the teacher.

   
  ## Product Functions
  
  • Classification of learning styles based on user preferences.
  
  • Creation of descriptive profiles of each user.
  
  • Storage of information in an external database. (Can be the institutional database).
  
  • Provide information about the learning styles according to the user's when obtaining a result of the classifier.

  
  ## User Characteristics
  
  The system will have three types of user: Academic (Students), Administrative(Teachers and School Principal) and External (Parents or Guardians).
  Of these three types, users are divided into final and potential according to the use they give the system.
  
  The system will have two final users, who will interact with LTC directly.
  
  | Users| Description|
| ------------- |:-------------:| 
| Student| Is the one who will introduce his data, answers about his preferences and interests and will obtain the appropriate result for him.|
| Teacher| Will have access to the system to analyze the results of each student and thus channel it to activities that favor their learning.| 

The LTC will have two more users, who will interact with the main users in the classification process and with the system only if necessary.

| Users| Description|
| ------------- |:-------------:| 
| Parent or Guardian| Access the LTC to enter data if the student cannot or knows how to operate the system.|
| School Principal| Will have access to the system to analyze the information together with the teacher, in case there is a need to channel students to some kind of special help. Will also receive the results of the system in the school database.| 
  
  
  ## Constraints
  
  - Data exchange protocols must be used via the internet during the storage process in the database.
  
  - Regarding security, the use of the system by sessions should be considered to limit access to main users only.


  ## Assumptions and dependencies
  
  | Assumptions| Dependencies|
| ------------- |:-------------:| 
| The LTC system will be a desktop program.| For LTC to work properly, it is required to have mainly Internet connection.|
| It can be used by different users at the same time but only by sessions.| The teacher and the school principal have knowledge to handle certain types of software.| 
  
  
# Specific requirements
  
  In this section, each of the requirements and specifications of the LTC system are described in more detail.
  
  
  ## External interface requirements
  
  - The graphical interface with which the end user interacts must be intuitive, such that without a user manual, any type of user can identify and use the system functions.
  
  - It must include a telephone number for user support, in this case the administration number (school principal). Where they help to solve doubts and fix problems.
  
  - It should have two themes (light and dark) with nice colors in sight so that the user can work with the system comfortably.
  
 **Welcome Message**
  
  - In the graphical user interface, there will be a welcome message for the purpose of the system.

  - The message window will have a size of 650 x 487 pixels and will be of contrasting color to the background.

  - This window can be edited by the direct system administrator (teacher or school principal) and it will be possible to add         images png, jpg and gif.
  
  **Menu**

   - The menu will be displayed on the left side when closing the window with the welcome message and according to the type of user (academic, administrative or external) the elements will be the following: 

     **Academic user:** 
      
      • Start
      
      • Log in
      
      • Take test
      
      • Results Consultation
      
      • Sign off


      **Administrative user:** 
       
       • Start
       
       • Log in
       
       • Search for
       
       • Student Profile Consultation
       
       • Results Consultation
       
       • Group Consultation

       • Create profiles (**Only the school principal**)
       
       • Ups and downs of academic and external users (**Only the school principal**)
       
       • Access Database (**Only the school principal**)
       
       • Report generator
       
       • Sign off


      **External users:** 
       
       • Start
       
       • Log in
       
       • Results Consultation
       
       • Sign off
       

  **Log in**

   - The user must enter a username and password previously registered by an administrative user.

   - The password must have no less than 8 characters and include uppercase, lowercase and numbers. No symbols or other character.

   - The username will be formed by the initials of the names of the person, followed by the first surname and the last two digits of the year of birth.

    Example: Erika Itzel Rosales Lopez, 1999.        Username: eirosales99
  
  ## Functional requirements
  
   In this section, the functional requirements must be classified depending on the type of user that the system has, because each profile will have different functions within the LTC system.
   
   **Academic user:** 
      
  • Start and end of session.
  
  • User and password authentication.
  
  • Password restoration.
  
  • Test realization.
  
  • Results consultation.

   **Administrative user:** 
       
  • Start and end of session.
  
  • User and password authentication.
  
  • Password restoration.
  
  • A search engine to filter system information.
  
  • Students and groups consultation (profiles and statistics).
  
  • Results consultation.
  
  • Make changes in the system (welcome message, student channeling, users names, etc.).
  
  • Generate reports.

   **External users:** 
   
  • Start and end of session.
  
  • User and password authentication.
  
  • Password restoration.
  
  • Results consultation.
  
  
  ## Non functional requirements
  
  - The most important requirement that the LTC system must have is stability, that is, ensuring the integrity of the data that is entered into it.

  - That the program has availability to access it at any time that the user wants.

  - The documentation of the project must be sufficient to solve doubts about the use of the system but not so extensive so that it is easy to understand.

  - The LTC must be efficient in any computer equipment (fast or slow).

  - It must be safe to protect the personal data of the users and not use them for their criminal purposes (computer crimes).

  - It must include user support, a phone number to contact the system administrator in case a user has a problem.

  - The system must ensure quality, to prevent the increase of maintenance costs in the future.

  - Some parts of the system will need maintenance, so the proper functioning of the LTC must be ensured before and after this process.
  
 
## Additional comments
  
  The requirements can change according to the needs that are presented to the school system of the institution. The LTC system can adapt to them.
  

# Supporting Information

  ## Table of Contents and Index
- [Introduction](#Introduction)
  - [Purpose](#Purpose)
  - [Scope](#Scope)
  - [Definitions, acronymus, and abbreviations](#Definitions,-acronymus,-and-abbreviations)
  - [References](#References)
  - [Overview](#Overview)
- [Overall Description](#Overall-Description)
  - [Product Perspective](#Product-Perspective)
  - [Product Functions](#Product-Functions)
  - [User Characteristics](#User-Characteristics)
  - [Contraints](#Constraints)
  - [Assumptions and dependencies](#Assumptions-and-dependencies)
- [Specific requirements](#Specific-requirements)
  - [Functional Requirements](#Functional-Requirements)
  - [External interface requirements](#External-interface-requirements)
  - [Non functional requirements](#Non-functional-requirements)
  - [Additional comments](#Additional-comments)
- [Supporting Information](#Supporting-Information)
  - [Table of contents and index](#Table-of-contents-and-index)
  - [Appendixes](#Appendixes)
 
 ## Appendixes
