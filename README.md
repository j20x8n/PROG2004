java cAssessment Brief
PROG2004 ObjectOriented Programming
Module 4 – Advanced exception handling
The following part of the assessment coversthe content in Module 4.
Part 4 – Implementing exception handling
At the moment, you have not implemented any exception handling in your program. For this part of the assignment:
• Where applicable, make sure that all setters in your program confirm that the values they are writing to your instance variables are valid. If they are
not, throw an IllegalArgumentException and print an appropriate error message.
• Add any other exception handling that you feel is appropriate to your program.
Demonstration
In the partFour method in the AssessmentTwo class:
• Using one of the setters that you added exception handling to:
o Pass a valid value to the method and show that the instance variable is set
o Pass an invalid value to the method and show that the exception is caught
Title Assessment 2 (Continue from Project 2 from theprevious Assessment)
Deadline 11:30 AM, 16 December 2024
Submission Code + Video using a USB drive
2
Assessment Brief
Module 5 – Input/output
The following part of the assessment coversthe content in Module 5.
An important part of many programs is the ability to back up data to a file and then restore it as needed. In this section of the assignment, we will add this
ability to our program.
Hint for exporting and importing data
A common way to store data in a file that needs to be imported later is to use comma-separated values (csv). This means that we store a record on a single
line, and we separate values using a comma (,). For example, imagine an object for a class called Animal has the following information:
• species: Dog
• breed: Poodle
• colour: Brown
• name: Fido
• age: 7
You could store the Animal object in the file on a single line like:
Dog, Poodle, brown, Fido, 7
When you read the file, each line in the file will contain the details for a single Animal object. You can then use the split() method from the String classto split
the line into the individual values and then use the values to create a new Animal object.
Part 5 – Writing to a file
The Classroom classis missing the ability to back up the Members who have signed up for the Classroom. Forthis part of the assignment:
• Add a method to the Classroom class that writes the details of all of the Members that have signed up for the Classroom (i.e. stored in the
LinkedList) to a file. The details for each Member should be written on their own line.
• Youmust make sure to add all appropriate exception handling and error messages.
Demonstration
In the partFive method in t代 写PROG2004、Java
代做程序编程语言he AssessmentTwo class:
3
Assessment Brief
• Create a new Classroom.
• Add a minimum of 5 Members to the Classroom (i.e., the LinkedList).
• Export the Members to a file.
Part 6 – Reading from a file
The Classroom class is also missing the ability to restore the members who have signed up for the Classroom. For this part of the assignment:
• Add a method to the Classroom class that can read the file that was created in the previous section.
• When reading the file, you need to sign up all members for the Classroom (i.e., add them to the
LinkedList). You must make sure to add all appropriate exception handling and error messages.
Note: If you cannot enrol the Members in the Classroom (i.e., add them to the LinkedList), you will still get marks for reading the file.
Demonstration
In the partSix method in the AssessmentTwo class:
• Create a new Classroom.
• Importthe file you created in the previous part of the assignment.
• Print the number of Members in the LinkedList to confirm that the correct number of Members were imported.
• Print all Members in the LinkedList to confirm that the details of each Member were imported correctly.
Module 6 – Concurrency
The following part of the assessment coversthe content in Module 6.
Part 7 – lock() and unlock() methods
You are using a LinkedList to store the Members signed up for a Classroom. However, a LinkedList is not thread-safe. This meansthat if multiple threads were
performing operations on the Members signed up for a Classroom you could encounter issues. For this part of the assignment:
• Use the lock() and unlock() methods to protect any critical sections of code in the Classroom class that perform any operations on the LinkedList
that stores the Members signed up for a Classroom.
• Youmust make sure to add all appropriate exception handling and error messages.
4
Assessment Brief
Resources
To complete the task, you are recommended to:
• Study modules 1 - 6 materials and complete all learning activities
• Take an active role in the weekly tutorial and workshop.
Task Submission
You are required to submittwo items for this assessment, including:
• Your Java project 2 (after updating it)
• A 5 minutes video explain the new parts.
Assessment Criteria
Please refer to the rubric provided in the assessment folder for the assessment criteria. Marking criteria include:
• Java code compiles with Java 17 LTS
• Use of correct coding style, including the use of comments
• Accuracy of coding
• Use ofsuitable coding structures
• Correctsubmission and naming conventions of assessment items asrequired

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
