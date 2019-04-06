# Table of Contents
- [Introduction](#Introduction)
  - [Purpose](#Purpose)
  - [Scope](#Scope)
  - [Definitions, acronymus, and abbreviations](#Definitions,-acronymus,-and-abbreviations)
  - [References](#References)
  - [Overview](#Overview)
- [Overall Description](#Overall-Description)
  - [Product Perspective](#Product-Perspective)
    - [System Interfaces](#System-Interfaces)
    - [User Interfaces](#User-Interfaces)
  - [Product Functions](#Product-Functions)
  - [User Characteristics](#User-Characteristics)
  - [Contraints](#Constraints)
  - [Assumptions and dependencies](#Assumptions-and-dependencies)
- [Specific requirements](#Specific-requirements)
  - [External Interfaces](#External-Interfaces)
  - [Functions](#Functions)
  - [Performance requirements](#Performance-requirements)
  - [Logical database requirements](#Logical-database-requirements)
  - [Design constraints](#Design-constraints)
    - [Standar compliance](#Standar-compliance)
  - [Software system attributes](#Software-system-attributes)
    - [Realibility](#Realibility)
    - [Availability](#Availability)
    - [Segurity](#Segurity)
    - [Maintiability](#Maintiability)
    - [Portability](#Portability)
  - [Organizing the specific requirements](#Organizing-the-specific-requirements)
    - [System mode](#System-mode)
    - [User class](#User-class)
    - [Objects](#Objects)
    - [Feature](#Feature)
    - [Stimulus](#Stimulus)
    - [Response](#Response)
    - [Functional hyerarchy](#Functional-hyerarchy)
  - [Additional comments](#Additional-comments)
- [Supporting Information](#Supporting-Information)
  - [Table of contents and index](#Table-of-contents-and-index)
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
  
  - SRS: Software Requirements Specification.
  
  
  ## References
  ## Overview
  
  The SRS document for the TLC project is divided into the following sections:
  
  • The introduction section that focuses on the explanation, objectives and description of the document.
  
  • The overall description section oriented to the general description of the system, where the information is directed to the client or potential user.
  
  • The specific requirements section that talks about the specific requirements. This includes technical terms directed principally to the developers and programmers of the project.
  
  • The support information section contains the appendices and links of information related to the topic for general interest.

  
# Overall Description

In this section we identify the factors that affect the product and its requirements, as well as the context of the development of the system. These can be related to the development time by phases, costs and customer involvement.


  ## Product Perspective
  
  The TLC system is made up of different functions, among them a classifier that will give a result depending on the descriptive data (name, age, preferences (answers to previously asked questions)) that the user enters in it.

This software will also allow the management of student information, in this case the learning profiles, advice and study techniques suitable for this, for which it will need to communicate with a database to which would only have access the director of the institution or the teacher.


   ### System Interfaces
   ### User Interfaces
   
  ## Product Functions
  
  • Classification of learning styles based on user preferences.
  
  • Creation of descriptive profiles of each user.
  
  • Storage of information in an external database. (Can be the institutional database).
  
  • Provide information about the learning styles according to the user's when obtaining a result of the classifier.

  
  ## User Characteristics
  
  The system will have three types of user: Academic, Administrative and External.
  Of these three types, users are divided into final and potential according to the use they give the system.
  
  The system will have two final users, who will interact with TLC directly.
  
  | Users| Description|
| ------------- |:-------------:| 
| Student| Is the one who will introduce his data, answers about his preferences and interests and will obtain the appropriate result for him.|
| Teacher| Will have access to the system to analyze the results of each student and thus channel it to activities that favor their learning.| 

The TLC will have two more users, who will interact with the main users in the classification process and with the system only if necessary.

| Users| Description|
| ------------- |:-------------:| 
| Parent or Guardian| Access the TLC to enter data if the student cannot or knows how to operate the system.|
| School Principal| Will have access to the system to analyze the information together with the teacher, in case there is a need to channel students to some kind of special help. Will also receive the results of the system in the school database.| 
  
  ## Constraints
  
  - Data exchange protocols must be used via the internet during the storage process in the database.
  
  - Regarding security, the use of the system by sessions should be considered to limit access to main users only.


  ## Assumptions and dependencies
  
  
# Specific requirements
  ## External Interfaces
  ## Functions
  ## Performance requirements
  ## Logical database requirements
  ## Design constraints
   ### Standar compliance
  ## Software system attributes
   ### Realibility
   ### Availability
   ### Segurity
   ### Maintiability
   ### Portability
 ## Organizing the specific requirements
   ### System mode
   ### User class
   ### Objects
   ### Feature
   ### Stimulus
   ### Response
   ### Functional hyerarchy
 ## Additional comments
# Supporting Information
 ## Table of contents and index
 ## Appendixes
