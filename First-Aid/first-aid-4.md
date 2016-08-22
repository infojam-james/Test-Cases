[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Saving changes to the First Aid form

##Description
The user should be able to save changes they make to the First Aid form

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The categorisation for the incident prompted the 'Was First Aid administered?' question.
+ The 'Was First Aid administered?' question for the incident was answered 'Yes'.

##Assumptions
+ A supported browser is being used.
+ The tester has already opened the First Aid form.

##Test Steps:

1 Navigate to the First Aid form

2 Enter new content in any field(s)

3 Click the 'Save' button

4 Close the browser tab containing the First Aid form

5 Navigate to the incident in question

6 Click the 'Options' button

7 Select 'Open First Aid form'

##Expected Results
+ The newly-entered content should be displayed in the First Aid form
