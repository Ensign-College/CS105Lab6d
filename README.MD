Lab 6d
======

Submit your finished code to the Dropbox. You will need to pass off the lab with the TA or tutor during their office hours (their information is in the CS 105 Course Information section 
of the Class Resources module), or the instructor in class. Follow the CS 105 Formatting Guide which is also found in the CS 105 Course Information section.

Read the instructions carefully. Make sure your output matches the example run.

Objectives:
===========

In this lab, you will learn how to do the following:

-   Parse through a string one character at a time
-   Use a DECREMENTING for-loop
-   Use a control variable in a while-loop that is DECREMENTED in the body of the loop
-   Compare and contrast the benefits of using different types of loop structures

Structure:
==========

Create the following structure in Eclipse for this lab.

**Package Name:** week6\
**Class Name:** Lab6d

Program: reverse() Methods
==========================

Write a program that asks the user to enter something. Do NOT perform input validation on what the user entered.

###  reverseWithForLoop()

Have your main() method call a second method that you write called reverseWithForLoop(), passing the user's input as an argument. Your reverseWithForLoop()method will use a decrementing 
for-loop to reverse the string and return the reversed string back to main(). The call to the reverseWithForLoop() method inside of main() should be embedded inside a 
System.out.println() statement that says "Using the for-loop: The reverse of XXXXX is : XXXXX", as shown in the Example Run.

### reverseWithWhileLoop()

Have your main() method call a third method that you write called reverseWithWhileLoop(), passing the user's input as an argument. Your reverseWithWhileLoop() method will use a control 
variable that is decremented in the body of the while-loop to reverse the string and return the reversed string back to main(). The call to the reverseWithWhileLoop() method inside of 
main() should be embedded inside a System.out.println() statement that says "Using the while-loop: The reverse of XXXXX is : XXXXX", as shown in the Example Run.

After the program has finished, ask the user if they would like to play again. Use input validation to ensure the user answered with a 'Y' or 'N'. Keep the program running in an 
infinite loop until the user indicates they want to quit.

#### **Note:**

To access a particular character in a String of characters, use the s.charAt(i) method where:

-   s is a String
-   The length of the String can be found with s.length()
-   i is an index into the String where the first letter of the String is an index of 0 and the last letter of the String is an index of s.length() - 1

Key program requirements:
=========================

-   You must use a DECREMENTING for-loop inside of thereverseWithForLoop() method
-   You must use a control variable in a while-loop that is DECREMENTED inside reverseWithWhileLoop()
-   Call both methods from within System.out.println() statements inside of main()
-   You must complete the Ponder activity below.
-   Submit the following .java file:
    -   Lab6e.java

Ponder:
=======

Discuss the following with your partner. **Failure to do this activity and discuss these questions before you attempt to pass off your program will result in a failed pass off**.

-   Discuss the differences between writing the reverse function with a for-loop and a while-loop.
-   Discuss which loop structure you prefer IN THIS CASE and why?
-   Discuss the different ways methods can be called from within your code and in what situations you would want to use the various ways.

Example Run:
============

*This program will ask the user to enter something and then print out a reversed version of the user's input.*

*Please enter something: I hope they call me on a Mission!*\
*Using the for loop: The reverse of 'I hope they call me on a Mission!' is: !noissiM a no em llac yeht epoh I*\
*Using the while loop: The reverse of 'I hope they call me on a Mission!' is: !noissiM a no em llac yeht epoh I*

*Would you like to play again? (Y/N): n*

*\
*
