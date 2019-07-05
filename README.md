Software Requirements Specification
For
Reminder System

Prepared by

1.	A. K. M. Mahbub Ullah       1520383042
2.	Rezwana Shama      1410062642
3.	Rumki Hossain      1330258042






Northsouth University

3 July, 2019











Contents

Revision History 

1 Introduction                                                                                                                           1
1.1 Purpose …………………………………………………………………………. 1
1.2 Intended Audience …………………………………………………………...…. 1
1.3 Intended Use ……………………………………………………………………. 1
1.4 Product Scope…………………………………………………………………….1
1.5 Risk Definition …………………………………………………………….……..1

2 Overall Description                                                                                                                2
2.1User Classes and Characteristics…………………………………………………..2
2.2 User Needs ………………………………………………………………………..2
2.3 Operating Environment ………………………………………….………………. 3
2.4 Constraints ………………………………………………………….……………..3
2.5 Assumptions …………………………………………………….………………...3

3 Requirements                                                                                                                           4
3.1 Functional Requirements …………………………………….……………………4
3.2 Non Functional Requirements ……………………………………………….……4

Appendices                                                                                                                                 5

A Glossary                                                                                                                                  6








 
Introduction

1.1	  Purpose
The purpose of this document is to compile all documentation on the Preliminary Project Phase II, or the Senior Reminder System Project. This documentation will include the Requirements Specification containing the functional and nonfunctional requirements for this Project, the Program Specification containing the implementation of the project, the Process Specification and the User Manual. Having all of this documentation will outline for the reader the motivations and decisions that shaped the development of this project.

1.2	  Intended Audience
The main audience of the Project will be all people of the world. All kind of people can use it. Specially the people who often forget their work time or date. Our app will help them to remind their work time date and also place. And at the time of work and study the app will block phone’s game and other entertaining system. So all kind of people will be benefited by our app.
1.3	 Intended Use
As a group we have decided that our two main goals are to create an App that is effortless to access and very intuitive to use. If the user can’t remember the exact workings of the app, we want it to be intuitive and natural to use so they are still able to use it. This will be a tremendous goal because it means that the user only needs to remember they have the App and none of the details of use. Some of our lesser goals are: creating object persistence that supports useful features, giving a caregiver an easy to way to supplement the user’s use of the App, and easy ways to navigate the app like voice search.

1.4	  Product Scope
The project is defined by the boundaries of the selection process and our narrowing of the
Project definition. Project selection was completed by meeting together and each person suggesting an idea. After discussion of the upsides and downsides of the various ideas, our team came to a unified agreement on a reminder system. Review of the project goals, deliverables, tasks to complete, their associated costs and deadlines, further narrowed our project to a precise application idea.

1.5	Risk Definition
There won’t be much risk using our app. But there can be some problem if there is any bug in our app. We will try to decrees our problems. Otherwise there will be no privacy problems while using our app. This app won’t ask any kind of storage access, so no data risk.

Overall Description

 2.1. User Classes and Characteristics

• Log in
• Set traffic constraints
• Make a new reminder
• Set transportation
• Set notification buffer time
• Access location
• View reminder
• Edit reminder
•Delete reminder
• Emergency notification
• SMS emergency contact
• Create new deadline
• Set deadline date-time
• Set max required time
• Set min required time
• Link shared routine
• Notify routine update
• Disable applications
• Log out

2.2. User Needs

Users of the system should be able to get notifications reminding them to set off based on the distance between the gps location of the phone and their destination, their preferred mode of transportation they provide and assumed traffic limitations of the time or day. Users need the system to take control over certain applications to disable or draw over them for a specific period of time so that they cannot be accessed, or notify emergency contact if they are accessed after warning notification. The system should have access to the messages the user receives and be able to parse them for keywords. The users need to be notified about the isolated information of the messages from certain contacts if the messages contain specified keywords. The users should be able to input deadlines and time constraints and be given color-coded reminders to urge them until the work is marked as done. The users need a network in the system that can link their routines or reminders so that they can get notified simultaneously for group projects. The user needs to be able to customize routines around months or even years that gets triggered monthly, yearly or a specified time in between.





2.3. Operating Environment

The android application can ideally be developed on any of the following platforms: 

1. Windows 
2. OS X 
3. Linux 

Software requirements 

1. Java Development Kit (JDK) 7 or later version 
2. Android SDK 
3. Android Studio 

Hardware requirements

1. 2 GB RAM minimum, 4 GB RAM recommended 
2. 400 MB hard disk space 
3. At least 1 GB for Android SDK, emulator system images, and caches 
4. 1280 x 800 minimum screen resolution

2.4. Constraints

There are a number of constraints around the execution of this system. The system needs full access over the running of different apps to be able to disable them, which could require the phone to be rooted. It requires network access and permission over almost all data on the system to function at its best. The system also needs to be provided a variety of information meticulously to be able to show dynamic notification for an event with customized policies and settings. 

2.5. Assumptions

Let us assume the user will stay located in a single country and have only certain modes of transportation and certain traffic time limits. We also assume that the information about plan changes will be coming through phone messaging apps only.





Functional Requirements

1.	For games disable- System permission to view running processes in the system and check there is any game is already running, if running it will send notification to the users to remind the user about studies.
2.	For tracking location- Database (Firebase)
For location, traffic reminder- Maps API provided by google and we need to send push notifications in android
3.	For group project notification- Need to add other users and set reminder
4.	For user routine- Need to save database according to calendar and it will give reminder. On Functional Requirements 



1. Availability 
2.  Reliability 
3. Recoverability 
4. Security 
5. Capacity
6. Scalability

