# Assignments & Labs

Assignment | Description | Due Date
---------- | ----------- | --------
Assign #1 | pg 52 Exercises 1.3, 1.14, 1.15, 1.17, 1.20 | Jan 13
Worksheet #1 | Java code and Answers to questions | Jan 18
Lab #1 | pg 56 Project 1.10 (initials) | Jan 18
Assign #2 | pg 106 Exercises 2.4, 2.7, 2.9, 2.10, 2.17 | Jan 23
Worksheet #2 | Java code and Answers to questions | Jan 23
Lab #2 | pg 110 Project 2.14 (Snowman) | Jan 25
Assign #3 | pg 155 Exercises 3.1, 3.2, 3.5, 3.7, 3.9 | Jan 27
Worksheet #3 | Java code and Answers to questions | Jan 30
Lab #3 | pg 157 Project 3.1** (User name) | Feb 1
Assign #4 | pg 200 Exercises 4.1, 4.2, 4.5 & SR 4.10, 4.13 | Feb 3
Worksheet #4 | Java code and Answers to questions | Feb 6
Lab #4 | pg 202 Project 4.4** (Dog class) | Feb 8
Assign #5 | pg various SelfReview 4.20, 4.24, 4.30, 4.32, 4.34 | Feb 10
Worksheet #5 | Java code and Answers to questions | Feb 13
Lab #5 | pg 203 Project 4.12** (Crayons ) | Feb 15
Assign #6 | pg 201 Exercises 4.6, 4.7, 4.8, 4.10, 4.11 | Feb 17
Worksheet #6 | Java code and Answers to questions | Feb 22
Lab #6 | pg 263 Projects 5.1 and 5.2 combined (Gregorian calendar) ** | Feb 22
Assign #7 | pg 260 Exercises 5.1, 5.4, 5.9, 5.13 ,5.15 | Feb 24
Worksheet #7 | Java code and Answers to questions | Feb 27
Lab #7 | pg 265 Project 5.12 ** (Golf) | Mar 1
Assign #8 | pg 294 Exercises 6.1, 6.7, 6.10, 6.14, 6.16 | Mar 3
Worksheet #8 | Java code and Answers to questions | Mar 6
Lab #8 | pg 298 Project 6.18 ** (Quilt) | Mar 8
Assign #9 | pg 433 Exercises 8.1, 8.2, 8.3,8.4,8.7 | Mar 10
Worksheet #9 | Java code and Answers to questions | Mar 13
Lab #9 | pg 435 Project 8.1 ** (Array) | Mar 15
Extra Credit Lab | pg 299 Project 6.23 (dialog boxes) | Mar 17

**Final Exam**
Monday, March 20, 3:00–4:50 P.M. in T-119.

# Additional Instructions

## Submitting Assignments

You must turn in:

1. An electronic copy of all of your code in a folder created on your LBCC Student Google Drive and shared with your instructor. Name your folder with your last name, first name, and class name in parenthesis. For each assignment create a new folder inside this one and name if after the assingment, lab, or worksheet you are submitting.

## Header

You must include the following header at the top of all file you submit.

``` java
// **************************************************************
// Name:
// CS161 Winter 2017
// Assignment/Lab/Worksheet #
// Class time:
// Date:
// Program Name:
// Program Description:
// Test Oracle:
//*********************************************************************

public class NAME_OF_YOUR_FILE
{ public static void main(String[] args)
 { // your code goes here……make sure your code will compile
   // before you turn it in!
 }
}
```

## Test Oracle

A Test Oracle is a chart or table that lists possible inputs, and the output you would expect from your code for that input. You are predicting what your program will do when given the particular input. The Test Oracle should be created before you write the code. If you write your Test Oracle AFTER writing the code (ie – use the running code to create the output values) you will not be able to tell if your code is producing correct results.

## Lab Details

### Lab #1 Initials

Instead of printing your initials, you may choose to print any picture that can be created with System.out.println() statements.

### Lab #2 Snowman

Be sure to turn in and print out both your .java file and your .html file. Also: change the color of the "ground" to be either green or orange.

### Lab #3

Your Test Oracle should list several first and last names, and the corresponding username your program should generate (you may use XX for the random integers). For example:

First Name | Last Name | UserName
---------- | --------- | --------
Daniel | Wilson | dwilsoXX
Joan | Anderson | janderXX
Betsy | Cartright | bcartrXX

### Lab #4

Write your own class `Dog` and a driver class `Kennel`.

A) In your `Dog` class:

1. Create a method called `PeopleYears()`, which calculates and returns the age of the dog in "people years (`DogAge * 7`).
1. Use only two instance variables: `Name` and `Age`.
1. Create one constructor that receives two arguments: a `string` and an `integer`.

B) In your `Kennel' class:

1. Declare at least 4 dog objects.
1. Update three different instance variables (different objects) using setter methods.
1. Call at least two "getter" methods.
1. Call the `PeopleYears` method for each object.
1. Print the description of each `Dog` object you have created (using your `toString()` method).

C) Create a test oracle for the method `PeopleYears()`.

### Lab #5

Use the example that starts on pg 184 in your textbook as a place to start (listing #4.7: the classes Splat, SplatPanel and Circle). You will write three separate classes:

A) A “driver” program called CrayonBox

1. Create the `frame`, with the words "Crayon Box" in the Title Bar.
1. Create a `Crayon Panel` object and call the constructor for `Crayon Panel`.
1. Add the `CrayonPanel` object to the `Frame`.

B) A separate `panel` class called `CrayonPanel`.

1. Will instantiate at least 6 `Crayon` objects.
1. With each object, call the `Draw()` method to draw it on the screen.
1. Draw a box over the crayons.
1. Draw your name somewhere on the screen.

C) A class called `Crayon`

1. The constructor will set the height, color and X,Y coordinates for each `Crayon` object.
1. The class `Crayon` will need the method `Draw` to draw each `Crayon` object on the screen. The `Draw()` method will use the `height`, and `X`, `Y` coordinates for the `Crayon` objects’ position on the screen.
1. Write setter and getter methods for each instance variable.

D) No test oracle required.

E) Extra credit: create a method called `RandomColor` which returns a `Color` object. The method will randomly generate the red, green and blue values for the `Color`. Write a setter method that will call `RandomColor` to set the `Color` for a crayon.

### Lab #6

Leap years... Combine the instructions for programming projects 5.1 and 5.2. Your program will include a flag loop (not a sentinel loop) that will allow the user to continue entering years until they say they are done. You will also include a verification of input loop that will produce an error message if the year entered is less than 1582, and ask for another input. When you ask for input from the user, be sure to tell the user what years are acceptable. After each year is entered, your program should produce a message telling the user if the year was a leap year or not.

Test oracle: show the expected output for a number of different years: for example, before 1582, after 1582 that are leap years, after 1582 that are not leap years, and after 1582 that are also century marks (1900, 2000…).

### Lab #7

Create a Text file with golf scores. Each line in the file will contain five integer values – the first value is par for that hole, the next four values are scores for each of the four golfers. The file will contain a total of 18 lines (18 holes). **Do not use an ArrayList** for this lab. Your program will:

1. Read information from the file, add the scores from each hole for each golfer.
1. Dtermine each golfers final score and print those scores.
1. Determine the winner of this golf game and print a message saying who won.
1. Produce a table showing how each golfer’s score compares to par. (ie: 5 over par, 2 under par, etc).
1. Test oracle will use a sample file of only 3 or 4 holes to test for accuracy of your code.
1. Extra Credit: create the file you will be reading from by randomly generating the integers needed and writing them to the file. See page 555 for an example of writing to a file. Be sure to turn in the printed code for this program also, and mark it as "Extra Credit."

### Lab #8

You must create a `Pattern` class and declare two instances of the class. The constructor for the `Pattern` class will accept a parameter that sets the characteristics of the object (like the color and width). Alternate those objects when drawing the quilt. Make sure that your quilt contains at least 5 blocks across and 7 down; i.e. your grid must be at least 5 x 7 squares. Your `Pattern` class should include a method called `Draw()` that draws the pattern on the screen at a specific location. The `Draw()` method must receive the `x` and `y` coordinates of the location. You must use nested loops to draw the quilt. Test oracle not needed. (Hint: use the `Splat`, `SplatPanel`, and `Circle` classes as an example of how to write a `Quilt`, `QuiltPanel`, and `Pattern` classes for this project.

### Lab #9

Generate 1000 random integers in the range 0-50. Use an array to hold the count of how many times each of the values in the range comes up as a random number (hint: do not use an array of 1000!). Print the contents of the array in a table that lists the value (0-50) and then the contents of that array element. Test oracle: generate 25 random integers in the range 0-10 and print how many times each value was generated.
