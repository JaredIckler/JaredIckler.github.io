# **CS-499 ePortfolio**


## **Introduction & Self-Assessment**
My experiences completing the Computer Science Program at Southern New Hampshire University has given me a deeper appreciation for the field as a whole.  The courses that I have taken have given me experience and exposure to many different faces of the field, from the basics of Java, C, and Python, to more advanced topics such as app development, microcontroller interfacing, and database management.  This ePortfolio displays some of the skills, though not all, that I have acquired during my time at Southern New Hampshire University.  Despite this not being a complete reflection of my abilities, it does showcase my knowledge in three main categories: Software Design and Engineering, Algorithms and Data Structures, and Databases.  The three artifacts shown are all in different programming languages, C, Java, and Python respectively, and this shows off some of the flexibility that I have gained while completing this program.

Throughout this program I have come to appreciate the importance of other, non-Computer Science related topics, the biggest one being communication with stakeholders.  Many of the final projects in the courses I have taken were based on real-life scenarios, especially once I started getting into the higher level courses.  These projects would be framed as a company giving a list of requirements that they want an application to be able to achieve.  Specifically, I had a course centered around Agile and the software development lifecycle where throughout the course the assignment instructions would be framed as team meetings where aspects of the project were discussed and certain goals for the week were lined out.  Security is also a topic that several of the courses have been about including Software Security, Client/Server development and Full Stack Development I &II.  Secure Coding in particular taught about creating secure policies and some basics about identifying and mitigating vulnerabilities in software.  Software engineering, data structures, algorithms, and database management have all been staples of the courses throughout the program.  These are general principles that are used constantly in many of the possible occupations that a  Computer Science degree can lead to.  This means that most of the courses in the program focus on one or more of these topics.  Outside of standard course work, as a personal project I have used the knowledge I have gained through these courses, especially the Emerging Systems Architecture and Design class, to effectively digitize an old broken version of the 1972 tabletop game Séance.  This involved using a microcontroller to replace the internal functionality of the games table, as well as wiring a speaker, button, and power supply together with the microcontroller.

This first Artifact is a program that will cause an LED on a provided microcontroller to flash specific Morse Code messages, as well as allowing the user to cycle through the messages.  This is written in C and displays both competency with the language as well as the ability to create something that is useful in a physical manner as opposed to just being a virtual product.  The second Artifact is a display of JUnit tests.  This is written in Java and displays my proficiency working with Object-Oriented programs, as well as showing how important testing is in Computer Science.  The final Artifact is the backend functionality of a website that improves upon the basic CRUD, create, read, update, delete, functions of the original.  This artifact is written in Python and interacts with a database in order to allow the website to display specific information.  


## **Artifacts**

# **Enhancement One: Software Design and Engineering**

This artifact is from the course CS-350 and was completed originally at the end of August 2024.  The artifact interfaces with a microcontroller from Texas Instruments to make an LED on the board flash the morse code for SOS. 

This artifact was chosen as it is a unique project among the courses through this program, as well as being a good example of basics such as commenting, the use of functions, etc.  This artifact expanded on the existing functionality by both expanding the amount of words that the LED can flash as well as utilizing the buttons on the board to cycle through the options.  The original project was a simple application to allow for the students to get used to the LED controlling functions.  The enhancement expanded this functionality by adding other basic morse code words like ok, yes, and no, as well as allowing the user to cycle through them.  While this functionality is essentially a proof of concept when used with the provided board, a little tweaking would allow for this code to be used to interface with a much larger piece of technology and actually allow for basic communication in an emergency situation. 

I feel that I have accomplished course objectives that I set out to complete with this artifact.  I improved the functionality of the base code to expand upon the messages that can be sent, as well as developing a way to cycle through the provided messages.  I do not currently have plans to update my outcome-coverage plans.

This artifact is very unique from the other projects that I have had to do in this program, and as such even the original artifact taught me alot.  CS-350 is the only  Computer Science class that I took that actually displayed a real life tangible product with the projects that it had the student complete.  Other classes had the students set up websites or databases, or even develop apps, but this was the only one where the end product was something physical.  It really showed that the field of Computer Science is not limited to just the virtual space and it can have effects on the real world in certain settings.  The enhancements allowed me to appreciate adding and expanding on a simple project in order to make it more realistically useful.  


### **Repository Link**

- [Enhancement One Repository](https://github.com/JaredIckler/CS499-EnhancementOne)


# **Enhancement Two: Algorithms and Data Structures**

This artifact was created for the CS-320 course and is designed to form the backend of an interface that lets people schedule appointments, including the collection of user related information such as names, addresses, phone numbers, etc.  The application also needed to have testing, in the form of JUnit tests, to make sure that the information entered was correct.

This artifact was selected as it is a good example of how testing of data structures and especially algorithms are done in a real world setting.  While JUnit Tests are not themselves an algorithm or data structure, they do provide a very useful framework for testing either of those.  In the case of this artifact the testing was done to ensure that the collected information about the different appointments was accurate.  The enhancements done improve this by changing the testing methods as well as expanding on the existing tests.
The original artifact was using JUnit tests that used the ‘asserttrue’ and ‘assertfalse’ methods to determine if variables were within the defined parameters.  In the enhancement the tests methods were changed to ‘assertequals’, as that is a more versatile method.  Additionally, test methods for adding and removing data were implemented as they were not being tested in the original code.  The change in test method resulted in a reformatting of the test classes as ‘asserttrue/false’ were boolean methods and so were very simple to implement, however ‘assertequals’ is more complex and needed to have more structure to the code in order to support it.

I feel that I have accomplished course objectives that I set out to complete with this artifact.  I improved the functionality of the base code to expand upon the tests done on the application, as well as reformatting the code base to support a more flexible way of testing the code.  I do not currently have plans to update my outcome-coverage plans.

When enhancing this code something that stuck with me is that while changing something in a piece of code to make it more versatile might be better in the long term, it can drastically lengthen development time for potentially negligible benefits.  This was a very simple application with few functions that needed to be tested so it was a manageable task to reformat the test classes to handle the ‘assertequals’ method, but in a larger project that might not be so feasible.  ‘Asserttrue/false’ are methods that in practice do much the same job as the ‘assertequals’ method, so if a code base uses one then it is likely not worth the effort to start using the other, unless the code base was being reworked already.


### **Repository Link**

- [Enhancement Two Repository](https://github.com/JaredIckler/CS499-EnhancmentTwo)

# **Artifact Three: Databases**

This artifact uses the project from CS-340 completed in August of 2024.  The original artifact is a python file that was to serve as the backend of an animal shelters database by using PyMongo to interface with the database.  This basic file only has simple functionality of CRUD, create, read, update, and delete, and only for single files at a time, while the enhanced artifact has more in depth SQL functionality.

This artifact was selected as it is a fantastic example of the construction of databases on the backend.  CRUD is the basis of how databases are made to be more useful than just as large storage mediums.  These basic functions provide the read/write functionality that allows for analysis to be done on the information stored in a database.  With the improvements I made such as the ability to add, delete, and update multiple items with a single command, the functionality of the code has been noticeably increased.  These additional functions show my ability to expand upon existing SQL and python code.
I feel that I have accomplished  course objectives that I set out to complete with this artifact.  I improved the functionality of the base code to allow for the addition, deletion, and updating of multiple files in the database with a single command, as opposed to using a single command for each individual change that needs to be done.  I do not currently have plans to update my outcome-coverage plans.

When enhancing this artifact I really got an appreciation of how simple implementing basic CRUD functionality for a database is.  Just those four functions allow for the creation of simple, but fairly comprehensive, database manipulation.  Adding the ability to change multiple files at a time, while on the surface does not really change much in the broad functionality of the python code, does allow for much more efficient use of time when modifying the data in the database.  Instead of having to change individual files one command at a time, with the additions I made a user would be able to change whole swaths of files at a time, assuming that the changed data is the same for all of them.  Similarly, mass deletion becomes very easy as it is just a single command as opposed to one per file.  It really shows how fairly minimal changes can have huge impacts on the user friendliness of a project, especially when working with a database.

### **Repository Link**

- [Enhancement Three Repository](https://github.com/JaredIckler/CS499-EnhancmentThree)

### **GitHub Pages Link**

- [CS-499 ePortfolio](https://jaredickler.github.io/)

