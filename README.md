# CMPS-12A-Programming-Assignment-1-solution

Download Here: [CMPS 12A Programming Assignment 1 solution](https://jarviscodinghub.com/assignment/cmps-12a-programming-assignment-1-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

In this assignment you will write a Java program that will interact with the user by taking input from the
keyboard, performing some simple calculations, then printing its output to the terminal. Program input will
consist of five numbers: the length and width of a rectangular lot, the length and width of a rectangular
house situated on that lot (all linear distances are measured in feet), and the rate at which a lawn on that lot
will be mowed (measured in square feet per second.) Assume that all area not occupied by the house is
covered by grass. The program will print out two quantities: the lawn area (in square feet), and the mowing
time (in hours, minutes, and seconds, rounded to the nearest second.) The Java commands that get user
input, do the necessary calculations, and print the output, will be discussed in class. See the example
Area.java on the class website for an illustration of some of these commands.
A sample run of your program will appear as follows.
Enter the length and width of the lot, in feet: 150 250
Enter the length and width of the house, in feet: 100 75
The lawn area is 30000.0 square feet.
Enter the mowing rate, in square feet per second: 4.5
The mowing time is 1 hour 51 minutes 7 seconds.
Notice that the program interaction is both informative, and grammatically correct. The first line prompts
the user for the length and width of the lot. At this point program execution pauses while the user enters
this data. The user may enter the two numbers separated by a space, followed by the return key, or the user
may follow each number with a separate return. The length and width of the lot are then stored in variables
of type double. Likewise for the length and width of the house. The program then calculates the area of
the lawn, and prints that quantity to the screen. The next line prompts the user for the mowing rate, which
is then stored as type double. The mowing time is calculated, and printed in the form of three integer
quantities: hours, minutes, and seconds, rounded to the nearest second. Study the example HMS.java to see
how to handle these calculations. Notice that the words “hour”, “minute”, and “second” are properly
pluralized. Thus if the quantity is a single unit, there is no “s” at the end of the unit name, while for nonunit quantities (including zero), the unit name ends in “s”. See the example Plural.java for information on
how to do this properly, as illustrated in the following example.
Enter the length and width of the lot, in feet: 100 75
Enter the length and width of the house, in feet: 50 41.96
The lawn area is 5402.0 square feet.
Enter the mowing rate, in square feet per second: 2
The mowing time is 0 hours 45 minutes 1 second.
It is not required that your program check the input for logical consistency, such as whether or not a house
of the given dimensions will fit on the lot, or even whether or not the input quantities are positive. Such
checks may be required in future assignments.
Your source code file for this project will be called Lawn.java. Note that in all projects source file names
are not optional, and points may be deducted for misspellings. Thus “lawn.java”, “LAWN.java” and
“prog1.java” are all incorrect.
Your program will include the standard comment block described in lab1. Several acceptable forms of this
comment are included below.
2
// file_name.java
// your Name
// your CruzID
// assignment name
// a (very) short description of the program
or
//———————————————————–
// file_name.java
// your Name
// your CruzID
// assignment name
// a (very) short description of the program
//———————————————————–
or
/* file_name.java
* your Name
* your CruzID
* assignment name
* a (very) short description of the program */
or
/************************************************************
* file_name.java
* your Name
* your CruzID
* assignment name
* a (very) short description of the program
************************************************************/
What to turn in
Submit the file Lawn.java to the assignment name pa1. Thus your submit command will be
% submit cmps012a-pt.w17 pa1 Lawn.java
Start early, get help and ask questions in labs/office hours if anything is unclear.

