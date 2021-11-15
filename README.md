# Lab 8 - Starter
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
   
   Within a Github action that runs whenever code is pushed; We want our testing to be automated and also continuous in our CI/CD pipeline

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

    no, you would use unit testing fo individual parts of code

3) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.
   No because the "message" feature would need to emulate the user interface in going through the steps of writing and sending the message.

4) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.
   Yes, because a unit test can test this individual part of the code of a single variable.