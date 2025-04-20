# **CS-499 ePortfolio**



## **Introduction**

## **Education Review**

## **Artifacts**

# **Enhancement One: Software Design and Engineering**

This artifact is from the course CS-350 and was completed originally at the end of August 2024.  The artifact interfaces with a microcontroller from Texas Instruments to make an LED on the board flash the morse code for SOS. 

This artifact was chosen as it is a unique project among the courses through this program, as well as being a good example of basics such as commenting, the use of functions, etc.  This artifact expanded on the existing functionality by both expanding the amount of words that the LED can flash as well as utilizing the buttons on the board to cycle through the options.  The original project was a simple application to allow for the students to get used to the LED controlling functions.  The enhancement expanded this functionality by adding other basic morse code words like ok, yes, and no, as well as allowing the user to cycle through them.  While this functionality is essentially a proof of concept when used with the provided board, a little tweaking would allow for this code to be used to interface with a much larger piece of technology and actually allow for basic communication in an emergency situation. 

I feel that I have accomplished course objectives that I set out to complete with this artifact.  I improved the functionality of the base code to expand upon the messages that can be sent, as well as developing a way to cycle through the provided messages.  I do not currently have plans to update my outcome-coverage plans.

This artifact is very unique from the other projects that I have had to do in this program, and as such even the original artifact taught me alot.  CS-350 is the only  Computer Science class that I took that actually displayed a real life tangible product with the projects that it had the student complete.  Other classes had the students set up websites or databases, or even develop apps, but this was the only one where the end product was something physical.  It really showed that the field of Computer Science is not limited to just the virtual space and it can have effects on the real world in certain settings.  The enhancements allowed me to appreciate adding and expanding on a simple project in order to make it more realistically useful.  


### **Repository Link**

- [Enhancement Two Repository](https://github.com/JaredIckler/CS499-EnhancementOne)


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

- [Enhancement Two Repository](https://github.com/JaredIckler/CS499-EnhancmentThree)

### **GitHub Pages Link**

- [CS-499 ePortfolio](https://jaredickler.github.io/)

