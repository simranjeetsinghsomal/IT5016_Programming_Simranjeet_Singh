#Code Organization

The typing test logic is contained within a single function Typing_Test(), which is the structure of the whole code. This is an example of encapsulation, whereby a single und of code (the function) is charjed with a given task.

#Functionality

There is typing test where the user is given a string to type, time is recorded, number of keystrokes made and words per minute are calculated from the number of keystrokes.

#Input/Output

The input() function asks the user for a string while the print() function displays a string to the user. This as an act of input/output handling.

#Algorithm

It implements a trivial procedure to determine how accurate the person is, as well as their cpm and wpm. This algorithm is the type of procedural algorithm that was defined in the previous lecture; the code is a set of instructions to achieve the goal.

#Variables and Data Types

All the variables used in the code include; sen (the typing test message), start and end (starting and ending point of the typing test), given_sen (Input from the user), total_characters and total_correct_characters (total characters present in the typing type and the input typed by the user respectively), correct_characters (The total number of characters typed correctly by the user), cpm and wpm (Characters per minute or words per minute of the

#Software Design Principles

Here are some software design principles that are relevant to this code:

Single Responsibility Principle: The Typing_Test() function can of course only contain one function and that function is to handle the typing test logic.
Don't Repeat Yourself (DRY): They also did not made the code redundant in nature, where the entire typing test is done with the help of just one function.


separation of concerns.

KISS (Keep it Simple, Stupid): The code is more alike a plain code with no much hardness incorporated in it.
Separation of Concerns: The implementation breaks the typing test functionality and all its required logic into a single function for a better construct and improved manageability.
Readme File Explanation

Here is an explanation of the code in a README file format:

#Typing Test

This is a typing tutor where one types from a piece of text and the speed at which they type and the accuracy is determined.

#How to Use

Execute the code to run the program.
Enter the given sentence into the computer.
At the end of the lesson the program will show how fast you type and how accurate you are.
Algorithm

The program has basic scoring format that tell the number of accuracy, cpm, and wpm of the text inputted by the user. The algorithm counts the so many characters that a user has typed correctly when compared with the original sentence that was written.

#Design Principles

The following software design principles have to do with the presented code: single responsibility principle, DRY, KISS, and separation.
