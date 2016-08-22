[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Cancelling an undo to the First Aid form

##Description
The user should be able to cancel an update when making changes to the First Aid form

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

3 Click the 'Undo' button *(this will prompt a pop-up box asking for confirmation)*

4 Click the 'Cancel' button in the confirmation box *(this will prompt the pop-up confirmation box to disappear)*

##Expected Results
+ All content in the First Aid form remains as it was before clicking the 'Undo' button.
