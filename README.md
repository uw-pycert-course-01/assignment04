# Assignment 4: Validating data

## Objectives
In this assignment you will learn how to validate data in your
automated interview.

## Instructions
1. Start by reviewing the problem described below.
1. When you are familiar with the requirements, start to plan how you will write the Python code.
1. As you write the code be sure to test it frequently.
1. Submit your complete assignment when you are sure you have implemented all of the requirements.

### Basics
You will recall that from last weeks' assignment we have two files:

Firstly

questionid, sequencenumber, question,deletedflag

10,1,”What is your email”, False

And then

questionid,nameofpersoninterviewed,answer

2,”Andy”,”akmiles@uw.edu”

In this weeks' assignment we are going to add validation and exception tracking code to last
week's submission.

Here are the steps you need to follow:

1. Introduce validation to your logic that asks if the question needs to be deleted.
1. Write new funtionality that will read through the questions file one record at a time.
1. For each record, validat ethat all the data is in the ocrrect format. Display a message or messages that
ask the user if they wish to correct any errors. Then capture corrected values as needed.
1. As you find records marked for deletion, remove them from the file after asking
the user if they are sure the record needs to be deleted. Then either remove or restore the record. Make
sure there are adequate ocntrols to ensure the program does what the user needs.


1. Add code to make sure that the email address is provided and that it is in a valid
email format. 
1. Make sure that if the email fails any validation that the incorrect value is displayed, and
that the user is asked to provide the email address again.
