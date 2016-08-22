[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Undoing changes to the First Aid form

##Description
The user should be able to undo unsaved changes they make to the First Aid form

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

3 Click the 'Undo' button *(this will prompt a pop-up box asking 'Are you sure you wish to undo?  All unsaved changes will be lost.')*

4 Click the 'Confirm undo' button in the confirmation box

##Expected Results
+ The pop-up confirmation box should disappear
+ All changes made since the previous save should be undone
