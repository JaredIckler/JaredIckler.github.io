# **Enhancement Two: Algorithms and Data Structures**

This artifact was created for the CS-320 course and is designed to form the backend of an interface that lets people schedule appointments, including the collection of user related information such as names, addresses, phone numbers, etc.  The application also needed to have testing, in the form of JUnit tests, to make sure that the information entered was correct.

This artifact was selected as it is a good example of how testing of data structures and especially algorithms are done in a real world setting.  While JUnit Tests are not themselves an algorithm or data structure, they do provide a very useful framework for testing either of those.  In the case of this artifact the testing was done to ensure that the collected information about the different appointments was accurate.  The enhancements done improve this by changing the testing methods as well as expanding on the existing tests.
The original artifact was using JUnit tests that used the ‘asserttrue’ and ‘assertfalse’ methods to determine if variables were within the defined parameters.  In the enhancement the tests methods were changed to ‘assertequals’, as that is a more versatile method.  Additionally, test methods for adding and removing data were implemented as they were not being tested in the original code.  The change in test method resulted in a reformatting of the test classes as ‘asserttrue/false’ were boolean methods and so were very simple to implement, however ‘assertequals’ is more complex and needed to have more structure to the code in order to support it.

I feel that I have accomplished course objectives that I set out to complete with this artifact.  I improved the functionality of the base code to expand upon the tests done on the application, as well as reformatting the code base to support a more flexible way of testing the code.  I do not currently have plans to update my outcome-coverage plans.

When enhancing this code something that stuck with me is that while changing something in a piece of code to make it more versatile might be better in the long term, it can drastically lengthen development time for potentially negligible benefits.  This was a very simple application with few functions that needed to be tested so it was a manageable task to reformat the test classes to handle the ‘assertequals’ method, but in a larger project that might not be so feasible.  ‘Asserttrue/false’ are methods that in practice do much the same job as the ‘assertequals’ method, so if a code base uses one then it is likely not worth the effort to start using the other, unless the code base was being reworked already.


### **Repository Link**

- [Enhancement Two Repository](https://github.com/JaredIckler/CS499-EnhancmentTwo)
