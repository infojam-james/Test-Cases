[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Opening an Investigation - Notification to Case Lead

##Description
A Line Manager should receive an email informing them when an investigation has been opened on an incident for which they are the Case Lead.  The email should also inform them they are required to log in and complete the Investigations questions.

##Preconditions 
+ The user must already be registered with an email address and password.
+ The user must have system administrator permissions.
+ An investigation has not previously been instigated for the incident in question.
+ The incident in question must have the Line Manager as the Case Lead.

##Assumptions
+ A supported browser is being used.
+ The Line Manager has access to the inbox for the email address they registered onto the system with.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Open)'.

6 Click the 'Save changes' button.

##Expected Result
The Case Lead receives an email containing the following message:

##Concurrent Expected Results
See [Opening an Investigation - Notification to Assistant Director](https://github.com/infojam-james/test-cases/blob/master/Investigations/investigations-2.md)

See [Opening an Investigation - Notification to Health & Safety Co-ordinator](https://github.com/infojam-james/test-cases/blob/master/Investigations/investigations-4.md)

>**YorSafety: Investigation questions initiated**

>An investigations questions procedure has been initiated.  As the individual designated as responsible for this case, you are required to complete these questions.  Please log into YorSafety and visit the 'Investigation' tab in the relevant Incident Dashboard.
