[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Updating the First Aid form

##Description
The the First Aid form should automatically update if changes are made to fields in the incident form that pre-populate the First Aid form.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The tester is logged in.
+ The categorisation for the incident prompted the 'Was First Aid administered?' question.
+ The 'Was First Aid administered?' question for the incident was answered 'Yes'.
+ The Case Status must be 'Closed'.

##Assumptions
+ A supported browser is being used.
+ All mandatory questions were completed when recording the incident in question.

##Test Steps:

1 Navigate to the case in question

2 Navigate to the 'My Tasks' tab

3 In the 'Documents' section, Select 'Open Link in New Tab' *(this will open a new browser window containing the First Aid Form)*

4 Make a note of the text pre-populating one or more fields in the form

5 Close the First Aid form

6 Navigate to the 'Incident' tab

7 Click the 'Edit Incident' button

8 Change the information entered into the fields known to pre-populate the First Aid question fields noted in Step 4 (see [Pre-populating the First Aid form](https://github.com/infojam-james/test-cases/edit/master/First-Aid/first-aid-3.md))

9 Click the 'Update' button

10 Navigate to the 'My Tasks' tab

11 In the 'Documents' section, Select 'Open Link in New Tab' *(this will open a new browser window containing the First Aid Form)*

12 Compare the text pre-populating the fields with the changes made in the Step 8.

##Expected Results
+ The text pre-populating the First Aid form should match the changes just made when editing the incident form.
