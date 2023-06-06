# Lab Report 5
This lab report includes creating a debugging scenario I have to simulate a bug and working with a TA to test what is causing the big and then eventually fixing it. 

# Part 1: The Symptom
Included in this section is an example of a symptom produced by a bug in a code and a student asking on EdStem how to work through the issue. The example EdStem post will be following the template that is given on the website when trying to make a post to make it as realistic as possible. This code is not my own but actually the ListExamplesGrader repository from one of the previous labs. I just changed some of the code to produce an error. For simplicity's sake I'm going to take the position that it is my code since it's just an example. Taking the postition of the student, the EdStem post would look something like the following:

I'm using VSCode on my laptop and I'm running a scipt called grade.sh using bash. 

The image below depcits the symptom I'm experiencing. The issue comes from the output line after `ListExamples.java found'. The line after should be `All tests passed` and then `4/4`. Instead, I'm getting several error messages that I'm not very familiar with. It seems that there could be an issue within multiple lines of my code. 
![Symptom](terminal1.png)

The program is supposed to take in a student submission for a coding assignment and then evaluate the correctness of their code. This is done by running a bash script of grade.sh which checks for the correctness and then outputs the score the student receives. I've included the code in an image down below so you can see what I've done so far. The code is supposed to check that the student's submission actually exists and then it clones correctly. Then the program is supposed to run the JUnit Tests I've created to make sure the code works correctly. At some point in that process I'm getting an error. I'm assuming that I used one of the commands in the script incorrectly between line 7-19 as that is where the error is shwoing up. 

![Code](code1.png)

# Part 2: TA Response
