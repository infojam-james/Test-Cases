[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Confirming an incident is non work-related

##Description
A Case Lead should be able to confirm that an incident recorded as non work-related is indeed non work-related.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must be the Case Lead of the incident in question.
+ The Case Status of the incident in question must be 'Not Work Related'.

##Assumptions
+ A supported browser is being used.

##Test Steps:

1 Navigate to the 'My Tasks' screen of the incident in question

2 In the 'Have you reviewed the incident?' field, select 'Yes'

3 In the 'Confirm incident is not work related' field, select 'TRUE'

3 Select a response to all other questions

4 Click the ‘Update’ button

##Expected Results
+ A dialogue box confirms the update, and that this action will close the case
+ The Case Status changes to 'Not Work Related (Closed)'
