#Incident Screen - Confirm incident is non work-related

##Description
A Case Lead should be able to confirm that an incident logged as non work-related is non work-related.

##Preconditions
+ The user must already be registered with an email address and password.
+ The incident in question must be newly recorded.
+ The incident in question must have the case Status 'Not Work Related'.
+ The incident in question must not involve a fatality.
+ The user must be the Case Lead of the incident in question.

##Assumptions
+ A supported browser is being used.
+ The user has received a notification alerting them to the newly-recorded incident, and prompting them to log in to review it.
+ The second question in the 'My Tasks' box of the incident in question reads, "Confirm incident is not work related".

##Test Steps:

1 Navigate to the 'My Tasks' screen of the incident in question

2 In the 'Have you reviewed the incident?' field, select 'Yes'

3 In the 'Confirm incident is not work related' field, select 'TRUE'

3 Select a response to all other questions

4 Click the ‘Update’ button

##Expected Results
+ A dialogue box confirms the update, and that this action will close the case
+ The Case Status changes to 'Not Work Related (Closed)'
+ The First Aid form becomes available

[Return to Contents](Contents.md)
