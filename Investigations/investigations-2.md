[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Opening an Investigation - Notification to Assistant Director

##Description
An Assistant Director should receive an email confirming when an investigation has been opened on an incident happening to an employee in their directorate.

##Preconditions 
+ The user must already be registered with an email address and password.
+ The user must have system administrator permissions.
+ An investigation has not previously been instigated for the incident in question.
+ The person the incident happened to must be an employee or contractor.
+ The person the incident happened to must be linked to an Assistant Director in their Profile.

##Assumptions
+ A supported browser is being used.
+ The Assistant Director has access to the inbox for the email address they registered onto the system with.
+ The person the incident happened to is not themself an Assistant Director.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Open)'.

6 Click the 'Save changes' button.

##Expected Result
The Assistant Director of the person the incident happened to receives an email containing the following message:

>**YorSafety: Investigation questions initiated**

>An investigations questions procedure has been initiated.  You will be notified by email again when this case has been authorised.
