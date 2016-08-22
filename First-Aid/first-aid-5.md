[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Updating the First Aid form

##Description
The user should be able to automatically update the First Aid form if changes are made to incident form that affect the content of the First Aid form.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The categorisation for the incident prompted the 'Was First Aid administered?' question.
+ The 'Was First Aid administered?' question for the incident was answered 'Yes'.

##Assumptions
+ A supported browser is being used.
+ The tester has already amended some of the pre-populated content of the First Aid form.

##Test Steps:

1 Navigate to the First Aid form

2 Delete all pre-populated content from the form

3 Click the 'Update from incident form' button *(this will prompt a pop-up box asking 'Are you sure you wish to update?  All current content will be overwritten.')*

4 Click the 'Confirm update' button in the confirmation box

##Expected Results
+ The pop-up confirmation box should disappear
+ The First Aid form should be populated with content from the relevant fields of the incident form (see [Pre-populating the First Aid form](https://github.com/infojam-james/test-cases/blob/master/First-Aid/first-aid-3.md) 
