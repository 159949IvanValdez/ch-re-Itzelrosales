  
  <h3 align="center"> Universidad Autónoma de Ciudad Juarez</h3>
  <h3 align="center"> División Multidisciplinaria de Ciudad Universitaria </h3>
  <h3 align="center"> Departamento de Ingeniería Electricidad y Computación </h3>
  <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/Images/LOGO%20UACJ.png" height="260" width="260"></img></p>
  <h3 align="center">Learning Types Classifier Project</h3>
  <h3 align="center">Erika Itzel Rosales Lopez</h3>
  <h3 align="center">169842</h3>
  
  <h3 align="center">Development of Software Requirements</h3>
  <h3 align="center">May 2019</h3>
  
  ## Table of Contents and Index
 - [Table of contents and index](#Table-of-contents-and-index)
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
  - [Appendixes](#Appendixes)

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
  
  • Password restoration.
  
  • Test realization.
  
  • Results consultation.

   **Administrative user:** 
       
  • Start and end of session.
  
  • Password restoration.
  
  • A search engine to filter system information.
  
  • Students and groups consultation (profiles and statistics).
  
  • Results consultation.
  
  • Make changes in the system (welcome message, student channeling, users names, etc.).
  
  • Generate reports.

   **External users:** 
   
  • Start and end of session.
  
  • Password restoration.
  
  • Results consultation.
  
  Then the system functions according to users are represented and described with UML use case diagrams.
  
   ### General Use Case 
   
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/LTC%20-%20UML%20Use%20Cases/LTC-General%20Use%20Case.png" height=100% width=100%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Name: </td><td>Learning Types Classifier (LTC) </td></tr>
      <tr><td>Author: </td><td>Erika Itzel Rosales Lopez</td></tr>
      <tr><td>Date: </td><td>04/23/19</td></tr>
      <tr><td>Brief Description: </td><td>Accounts will be created with restrictions and specific functions for each of the user types.
The main function of the LTC system will be to classify the type of learning of the student who performs the test, store the results in the school database and be available to consult by the teacher, school principal and parents. </td></tr>
      <tr><td>Actors: </td><td> School Principal, Teacher, Student, Parent (or guardian). </td></tr>
      <tr><td>Preconditions: </td><td>Before using the system, the teacher must explain to the student and parents how it works so that both have knowledge of how to use it.</td></tr>
      <tr><td>Normal Flow: </td><td> <table align = "center">
    <thead>
      <tr><td>Student</td><td>Teacher</td><td>School Principal</td><td>Parent</td></tr>
    </thead>
    <tbody>
      <tr><td>3- Take the test.</td><td>2- Explain to the students/parents how the system works.</td><td>1- Create the users accounts.</td><td>4.1- Check his child results.</td></tr>
      <tr><td>4- Check results.</td><td>5- Check student results and channel the necessary help for him.</td><td>7- Receives and review the general report.</td><td></td></tr>
      <tr><td></td><td>6 -Generate a general report of results</td><td></td><td></td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table></td></tr>
      <tr><td>Alternative flow: </td><td> <table align = "center">
    
   <thead>
      <tr><td>Teacher</td></tr>
    </thead>
    <tbody>
      <tr><td>2- If necessary, make a tutorial for the student about the use of the system.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table></td></tr>
  <tr><td>Postconditions</td><td>The results are private and the only one who has total access to all the students results is the school principal.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
  
  ### Specific Use Case - Create Profiles
  
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/LTC%20-%20UML%20Use%20Cases/UML%20-%20SPRL1.png" height=100% width=100%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Use Case: </td><td>Create Profiles</td></tr>
      <tr><td>Date: </td><td>04/23/19</td></tr>
      <tr><td>Actors: </td><td> School Principal </td></tr>
      <tr><td>Purpose: </td><td>Create a profile for each user.</td></tr>
      <tr><td>Resume/Function: </td><td>Each profile will have a unique username and password for personal and private use.</td></tr>
      <tr><td>Preconditions: </td><td>Use the name and surname of the person to create the username.</td></tr>
      <tr><td>Normal Flow: </td><td>1- Access to the personal data of students, parents and teachers to register their user accounts.    2- Use the first and last name to create the username.    3- Create a personal password for each user.</td></tr>
  <tr><td>Exceptions: </td><td>If there are the same user names, add a number at the end of each one starting with 1, 2, 3 and so on.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
  
  ### Specific Use Case - Access Database
  
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/LTC%20-%20UML%20Use%20Cases/UML%20-%20SPRL2.png" height=100% width=100%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Use Case: </td><td>Access Database</td></tr>
      <tr><td>Date: </td><td>04/23/19</td></tr>
      <tr><td>Actors: </td><td> School Principal </td></tr>
      <tr><td>Purpose: </td><td>Make changes in the students data of the database.</td></tr>
      <tr><td>Resume/Function: </td><td>If there are results, personal data or school data that need some modification, the school director is the only one who can access the database and change them according to the case.</td></tr>
      <tr><td>Normal Flow: </td><td>1- Access to the system with their user.    2- Access to the database.    3- Make changes in the data.    4- Save changes.</td></tr>
  <tr><td>Exceptions: </td><td>Every change in the database is reflected in the system profiles.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
  
  ### Specific Use Case - Search
  
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/LTC%20-%20UML%20Use%20Cases/UML%20-%20SPTRL3.png" height=100% width=100%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Use Case: </td><td>Search</td></tr>
      <tr><td>Date: </td><td>04/24/19</td></tr>
      <tr><td>Actors: </td><td> School Principal and Teacher </td></tr>
      <tr><td>Purpose: </td><td>Perform searches in the system and filter information.</td></tr>
      <tr><td>Resume/Function: </td><td>The actors of administrative type (teacher and school principal) can carry out searches by name of student or username, by results, by type of learning or by group to more easily access the information of the students profiles.</td></tr>
      <tr><td>Normal Flow: </td><td>1- Access to the system with their user.    2- Click to search.    3- Make a search by username, results, learning type, etc.    4- Access to information.</td></tr>
  <tr><td>Exceptions: </td><td>The information in the search box must be well written, otherwise if it does not match, it will show "no results".</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
    
  ### Specific Use Case - Generate Reports
  
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/LTC%20-%20UML%20Use%20Cases/UML%20-%20SPTRL4.png" height=90% width=90%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Use Case: </td><td>Generate Reports</td></tr>
      <tr><td>Date: </td><td>04/24/19</td></tr>
      <tr><td>Actors: </td><td> School Principal and Teacher </td></tr>
      <tr><td>Purpose: </td><td>Generate general reports about the results of the students, either individual or group.</td></tr>
      <tr><td>Resume/Function: </td><td>The actors of administrative type (teacher and school principal) can generate individual or group reports, which include personal data of the students and their results.</td></tr>
      <tr><td>Normal Flow: </td><td>1- Access to the system with their user.    2- Click to generate reports.    3- Choose individual or group report.    4- Write the student's name or grade and group as the case may be.    5- Access information.    6- Print or exit.</td></tr>
  <tr><td>Exceptions: </td><td>The information in the text box must be well written, otherwise if it does not match, it will show "no results found".</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
      
  ### Specific Use Case - Results Consultation
  
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/LTC%20-%20UML%20Use%20Cases/UML%20-%20SPTSP5.png" height=100% width=100%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Use Case: </td><td>Results Consultation</td></tr>
      <tr><td>Date: </td><td>04/24/19</td></tr>
      <tr><td>Actors: </td><td> School Principal, Teacher, Parents and Student. </td></tr>
      <tr><td>Purpose: </td><td>Consult the results by group, student or learning type. </td></tr>
      <tr><td>Resume/Function: </td><td>The administrative actors (teachers and school principal) can consult results by student or group while the external (parents) and academics (students) can only access the results of the student in question. All this users also can access the information of each type of learning.</td></tr>
      <tr><td>Normal Flow: </td><td>1- Access to the system with their user.    2- Click to Results Consultation.    3- Choose individual or group, or learning types(information of each one) option.    4- Write the student's name or grade and group as the case may be.    5- Access information.    6- Exit. </td></tr>
  <tr><td>Exceptions: </td><td>The information in the text box must be well written, otherwise if it does not match, it will show "no results found".</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
        
  ### Specific Use Case - Log In / Log Out
  
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/LTC%20-%20UML%20Use%20Cases/UML%20-%20SPTSP6.png" height=90% width=90%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Use Case: </td><td>Log In / Log Out</td></tr>
      <tr><td>Date: </td><td>04/24/19</td></tr>
      <tr><td>Actors: </td><td> School Principal, Teacher, Parents and Student. </td></tr>
      <tr><td>Purpose: </td><td>Log in/out user and recover passwords. </td></tr>
      <tr><td>Resume/Function: </td><td>Users can start or close session and each account will have its own functions according to the type of user that it is (administrative, external, academic).</td></tr>
      <tr><td>Normal Flow: </td><td>1- Write their username.    2- Write the correct password.    3- Click on the option to login.    5- Give use to the system.    4- Click on the option to log out.</td></tr>
  <tr><td>Exceptions: </td><td>The information in the text box must be well written, otherwise if it does not, it will show "incorrect username or incorrect password". If the user does not remember the password of his account, it is possible to recover it by clicking on the option "recover password" and the system will send an email to the administrator with his request.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
          
  ### Specific Use Case - Take Test
  
   <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-Itzelrosales/blob/master/SRS%20-%20English/LTC%20-%20UML%20Use%20Cases/UML%20-%20S6.png" height=95% width=95%></img></p>
   
   <table>
    <caption></caption>
    <thead>
    </thead>
    <tbody>
      <tr><td>Use Case: </td><td>Take Test</td></tr>
      <tr><td>Date: </td><td>04/24/19</td></tr>
      <tr><td>Actors: </td><td> Student. </td></tr>
      <tr><td>Purpose: </td><td>Classify your learning style based on the response of your preferences.</td></tr>
      <tr><td>Resume/Function: </td><td>Answer the test questions to classify his learning type and obtain a result.</td></tr>
      <tr><td>Normal Flow: </td><td>1- Write their username.    2- Write the correct password.    3- Click on the option to login.    5- Click on the option Take Test.    4- Answer the questions.    5- Save answers or Finish Test.    6- Obtain a result.    7- Log out.</td></tr>
  <tr><td>Exceptions: </td><td>The information in the text box must be well written, otherwise if it does not, it will show "incorrect username or incorrect password". If the answers are not saved, finish the test and inform the teacher to carry out the test again.</td></tr>
    </tbody>
    <tfoot>
    </tfoot>
  </table>
  
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

 ## Appendixes
 
  ### Elicitation Process
  
This process was carried out through a conversation-interview, that was held with the administrative staff of Plan de Iguala Elementary School to identify what were their needs and wishes regarding the construction of the LTC system.

**Interview-Conversation about the steps of the process in question.**

Since the main problem that solves this project is the classification of the children's learning styles, the teacher was contacted first, because he is the one in charge of this process during the first classes of the school year.

The teacher Erika Lopez was asked to describe the classification process step by step and then the pros and cons of it. 
This is what she said:

   *« First, it is explained to the student that there are different types of learning and 
    that each one has specific characteristics and tasks that benefit them better 
    depending on the type that is.*

   *Then, the student is given a questionnaire previously made and reviewed by the SEP, which 
    contains multiple choice questions related to preferences in different aspects of daily life.*

   *During the application of the questionnaire, if any student has any questions he can 
    ask me what he wants. At the end of the questionnaire, they give it to me to review 
    and classify them myself.*

   *The revision process is simple because it is of multiple choice, the tedious is the time 
    it takes to review 30 to 35 questionnaires one by one.*

   *After having reviewed them all, I must classify the students according to their 
    learning style, register them in an excel table and finally add the questionnaire 
    to the student's file in case we wish to consult it someday.*

   *With the results registered in the excel table, I have to submit a general group report 
    to the school principal including the tables, conclusions and statistics of the types 
    of learning identified within my group.*

   *At the end of the process, it only remains to adjust the activities of my school planning 
    to benefit each and every one of the students in their learning process and to avoid 
    desertion within the group.*

   *A process of two or three days does not seem very long, however in the educational field it is, 
    because the estimated time to cover all the subjects of a school year is just and adding 
    extra processes makes it slow. »*
    
Then, the school principal Brenda Magallanes was also contacted and I asked to her to describe the process that follows the classification and delivery of the report. This is what she said:
    
  *« When the professor gives me the report, I read it, I check it, I stamp it and send it to SEECh to be filed.*

  *After this process, at each parent meeting I join the teachers to recommend activities that benefit the learning of each of the          students and I talk to them about the supports to which the students have access, for example: mathematics, special education,          advanced, etc.* 

  *If during the school year there are highs and lows of students I have to register that and update their school file, which contains      personal documents, papers, questionnaires made to the student, etc. »*

**Conversation about requirements for the LTC System**
    
*« We look for the system to help us to make the process of classification and generation of reports faster, also that is understandable for the students, with an educational and formal aspect and a welcome message.*

*It must include the official questions sent by the SEP from SEECh, have multiple options as in the written questionnaires.
We would also like it to be available to parents in case they ever wanted to make inquiries or follow up on the cases of the students, however, that would be all they had access to.*

*It should also provide a function of information about the types of learning so that within the community of parents they know the different types that exist and how to help the students with each one.*

*Instead of managing written files and recording them on paper, it would be very useful to connect to our school database, so we would better track each student's history.*

*It is essential that students can be made high or low to keep the file updated and in this way generate reports in a correct and formal manner. »*

**Conclusion**

After these conversations, I was able to identify the requirements of the project, which are listed below:

  - **Educational aspect:** soft colors, pleasing to the eye, no fluorescent colors.

  - **Understandable:** Without ambiguity in the texts, correctly written words, without complexity in the vocabulary.

  - **Quick system:** Content that occupies little memory to be effective and efficient.

  - **Content:** That includes the questionnaire made by the SEP, multiple choice questions. With a welcome message for the user.

  -	Being a data storage system, it must be connected to the school database of the primary school and have personal user accounts.

  -	**Functions:** 
    
      * *For the student:* Take test and consult results. 
    
      * *For the parents:* Consult results and information about the types of learning.
    
      * *For the teacher and school principal:* High and low students, creation of profiles, results consultation, report generator, access to    the database for modifications.

  - **Main specific functions:** Classify the type of learning based on the answers of the students in the test, store the results in the student's profile and be available for consultation at any time, generate group or individual reports, which include the results of the students, statistics and recommendations of activities.

