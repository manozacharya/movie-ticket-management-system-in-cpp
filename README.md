CHAPTER 1
INTRODUCTION
This Movie Ticket Management System is a simple console application built in C++ without the use of graphics. This is the basic user interface for ticket managing without going to the actual depart. This project is created in order to fulfill the gap between customer and the movie-counter for managing the tickets. Using this system, customers can book their seat without any obligation, at any time. This system is an attempt to provide the advantage for systematic ticket management for customers to creating the user friendly environment to facialite customer services, this system would play immense role for the better customer satisfication. In order to make a program possible, we use stream of class and file handling in C++ programming language. Two classes, class ticket and class amount can be found in this project in which class ticket is inherited from the class amount. The project is simple to understand, and the source code has been presented in an understandable manner. We use DevC++ as an IDE for better code compilation & debugging as it is modern and standard editor.

1.1	Background
Cinema Hall is an emerging field that applies different tools and techniques to give entertainment and analyse the customer’s view. Cinema Hall is evolving and also helping from different aspects like providing a public awareness and also increasing the human imagination power, and also it adapts new techniques and implement them to get more satisfaction from customers from different point of view, this may be entertainment, self-educating, encouraging or inspiring and many more. This system is an attempt to provide the systematic ticket management to customers via creating the user friendly environment. This system is created in order to fulfil the gap between customer and the movie-counter for managing & providing the tickets. The main purpose of  Movie Ticket Management system is to provide another way for the customer to buy & manage movie ticket. The development of standard platform approaches to the management of ticket management services is emerging as a key focal point for business re-engineering in the entertainment or cinema industry. 

1.2 Problem Statement
There was a time, where people are used to exchange their information with letters - it takes so many days to communicate. To overcome with these problem email and social networking sites are invented. Similarly, looking at the same concept, buying ticket for movie is exactly the same, it takes time to buy ticket from the counter via hand written method and many times we will find the seat is already packed and some spam may occured. It waste our time. so, to avoid all this factors, this system is created so that the people will able to buy the tickets from anywhere at any time and can check their account and edit the ticket details. This is what actually the system does.
It also reduces the fraudulent that usually happens.

1.3 Objectives
The primary purpose of this project is to serve customers through online service. The major objective is to develop this project is that;
•	To facilate people to save their time.
•	To discover new generation in Movie Ticket Management system.
•	To enhance the organization service platform.
•	To provide a anytime anyplace service for the customer
 
CHAPTER 2
LITERATURE REVIEWS
More than many numbers of online based application are developed till today. But among these all, this system is somehow different from others.  The concept of building the movie ticket booking system with the recommendation system using association algorithm have been derived from the several research projects, journals, books etc.
[1] virtual and new systems or tools are expanding fast in cinema sites, more services and tickets are need to be added, the amount of data has increased multifold resulting in complex heterogeneous network, with fewer operational commands is inadequate and could not provide scalability.
[2] The development of standard platform approaches to the management of ticket management services is emerging as a key focal point for business re-engineering in the entertainment or cinema industry. The main purpose of Movie Ticket Management System is to provide another way for the customer to buy & manage movie ticket. The development of standard platform approaches to the management of ticket management services is emerging as a key focal point for business re-engineering in the entertainment or cinema industry. 
[3] "Movie Ticket Management system ", is an extraordinary platform for the people and the organizations for the enhance of their better performance.
[4] Cinema Hall is evolving and also helping from different aspects like providing a public awareness and also increasing the human imagination power, and also it adapts new techniques and implement them to get more satisfaction from customers from different point of view, this may be entertainment, self-educating, encouraging or inspiring and many more. This system is an attempt to provide the systematic ticket management to customers via creating the user friendly environment


CHAPTER 3
ALOGRITHM

The simple basic algorithm for Movie Ticket Management System is given below;

1.  Start
2.  First, Admin Panel is open
     2.1 If username & password matched
           2.1.1 Go to step-3
     2.2 Else
           2.2.1 Display Incorrect username & password combination
3.  Secondly, Main Menu is open where choice is available
     3.1 If choice == 1
           3.1.1 Go to step-4
     3.2 Else If choice == 2
           3.2.1 Go to step-5
     3.3 Else If choice == 3
           3.3.1 Go to step-6
     3.4 Else
           3.4.1 Go to step-7
4.  Here it goes to cart details, where choice are available
     4.1 If choice == 1
           4.1.1 Show all the ticket details
     4.2 Else 
           4.2.1 Back to main menu
5.  Here it goes to main section, where choice are available
     5.1 If choice == 1
           5.1.1 It adds ticket details
     5.2 Else If choice == 2
           5.2.1 It edits the ticket details
     5.3 Else If choice == 3
           5.3.1 It delete the ticket details
     5.4 Else
           5.4.1 Back to main menu
6.  Here program shows the individual ticket details referencing the ticket number
7.  Terminate the program      	
           

CHAPTER 4
SYSTEM DEVELOPMENT

4.1 Project Management
A project is a sequence of unique, complex, and connected activities having one goal or purpose and that must be completed by a specific time, within budget, and according to specification. Projects also differ. Understanding how projects differ and what that difference means to the management of the project is critical to successfully managing a project. ―Project management is the application of knowledge, skills, tools, and techniques to project activities to meet the project requirements. [6] A project is said to be well managed if and only if it meets the client requirements. According to the Project Management Institute, the processes are guided through five stages: initiation, planning, executing, controlling, and closing. Project management can be thought of in terms of organizational, lifecycle, and functional area prospective. 
The core components of project management are: 

	Defining the reason why a project is necessary?
	Capturing project requirements, specifying quality of the deliverables, estimating resources and timescales,
	Preparing a business case to justify the investment, 
	Securing corporate agreement and funding, 
	Developing and implementing a management plan for the project,
	Managing the risks, issues and changes on the project, 
	Monitoring progress against plan and 
	Managing the project budget.

4.2 Project Workflow and Schedule
 - Team Size: [3] 
- Total effective project duration: [10] weeks 
- Effort required per person: [6] hours per week 
 	Gantt chart is also known as Time Line Charts. A Gantt chart can be developed for the entire project or a separate chart can be developed for each function. 

A tabular form is maintained where rows indicate the tasks with milestones and columns indicate duration (weeks/months).
 
                                           Fig: Gantt Chart

4.3 Project Team
Leading By	Role
Mr.chiranjibi sitaula 	Supervisor 
Dhiraj Kedar Pandey	Instructor
Manoz Acharya	Programmer
Sudeep Timsina	Programmer
Pukar Niroula	Programmer
                  
                           Table 4.3: Resources and their Roles



4.4 Responsibilities
Each individual involved in projects has their own responsibilities and are specified as below;
 
Table 4.4: Responsibilities

4.5 System Analysis
System analysis is a detailed study of various operations performed by a system. It is a process of collecting and analyzing facts with respect to the existing system operation of the situation so that an effective computerized system may be designed and implemented if proved feasible. It is a structural process related to four significant phases. They are study phase, design phase, development phase and implementation phase. A good analysis is essential for the development of a new improved system. The major objectives of systems analysis are to find answers for each business process: What is being done, How is it being done, who is doing it, When is he doing it, Why is it being done and How can it be improved.




4.6 System Design
Design is the first step into the development phase for any engineered product or system. Design is a creative process. A good design is the key to effective system. The term “design” is defined as “the process of applying various techniques and principles for the purpose of defining a process or a system in sufficient detail to permit its physical realization”. It may be defined as a process of applying various techniques and principles for the purpose of defining a device, a process or a system in sufficient detail to permit its physical realization. Software design sits at the technical kernel of the software engineering process and is applied regardless of the development paradigm that is used. The system design develops the architectural detail required to build a system or product. As in the case of any systematic approach, this software too has undergone the best possible design phase fine tuning all efficiency, performance and accuracy levels. The design phase is a transition from a user oriented document to a document to the programmers or database personnel.
The simple design process block diagram is shown below;
 
Fig: Block diagram for design process




4.7 Context Flow Diagram 


 CHAPTER 5
IMPLEMENTATION AND TESTING

5.1 Implementation
This is a simple system developed by using C++ as a programming language, DevCPP as an IDE (Integrated development environment) or simply Code editor. We can make this system in work using the following tools and platform;
•	Software Tool: DevCPP as an IDE
                 
•	Platform: Windows platform like: 2000 professional, XP & Vista and modern like windows 8.1,10,10s.

•	Hardware Specification: Intel Pentium and Celeron class processor
              Processor Speed – 1.2 GHz or above
              RAM - 512 MB
              Monitor- 14” SVGA
              Mouse- Normal
              Keyboard- Normal


5.2 Testing
Before launching any program, we need to analyse & testing it properly. After implementation of algorithm and selection of the module. It is to be tested using the simple mechanism like debugging, trying as a client and other simple approaches. Testing is the integral part of the software development process. Software system testing identifies important defects, flaws, or errors in the application code that must be fixed. The modifier ―important in the previous sentence is, well, important because defects must be categorized by severity. Validation refers to the process of using the new software for the developed system in a live environment i.e., new software inside the organization, in order to find out the errors. The validation phase reveals the failures and the bugs in the developed system. It will be come to know about the practical difficulties the system faces when operated in the true environment. By testing the code of the implemented software, the logic of the program can be examined. A specification test is conducted to check whether the specifications stating the program are performing under various conditions. During the designing process, this project has so many bugs which were debugged one by one analyzing the problem occurred on each steps. This project has gone through following testing procedure.



CHAPTER 6
CONCLUSION AND FUTURE LOOKS

6.1 Conclusion
This project is developed to fulfil the needs of a customer in a Entertainment sector by embedding all the tasks of online booking and managing tickets taking place in a movie threater. Future version of this project will still be much enhanced than the current version. Going cinema hall to allow ticket for movie are perhaps the worst method nowadays. All cinema hall have rules about how long it takes to access your ticket, how many users are allowed for a single movie, and how much cash you should pay. It is a successful strategic weapon for movie threater to remain profitable and making fully satisfy to the customers in a volatile and competitive marketplace of today. Thus the Movie Ticket Management System it is developed and executed successfully.

6.2 Future Look
The project Movie Ticket Management System for Cinema Hall is flexible enough to meet the requirements of the Customers. This project also has the scope of enhancements like:
1- Home delivery of tickets may be provided.
2 -Online Booking of Purchases of eatables (cold drinks, popcorn etc) can be provided.
3-Corporate booking: Multimedia support for corporate presentation can be provided. Conference facility can be provided for corporate meetings in the hall. This will increase the profit of cinema halls as well      as the company organizing event.
4 Group booking: Any institute/company can book the tickets for students/clients and special discount will be provided to them.




 
References 
[1] 	“Perception Towards Movie Ticket Management System: An empirical study” by Zia UI Haq (2008) from Journal of Research in Commerce and Management Vol 1.
[2] 	Hitachi Review Vol. 48 (1999), No. 4
[3] 	International Journal of Computer science & Information Technology (IJCSIT), Vol 1, No 2, November 2009, Mike
[4] 	Robert Lafore, C++ 4th edition, Text Book
[5] 	Asemi, A., & Safari, A., & Zavareh, A.A. (2011). The Role of Management Information System (MIS) 
[6] 	International Journal of Scientific & Technology Research,Ebubeogu Amarachukwu Felix volume 4, ISSUE 08, AUGUST 2015


Appendix – Screenshots
1.	Login Section
 
2.	Main Menu
 

3.	Main Section
 
4.	Cart Details
 
5.	Ticket Details
 




























