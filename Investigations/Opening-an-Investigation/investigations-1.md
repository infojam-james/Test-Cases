[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Opening an Investigation - Notification to Health & Safety Team

##Description
A system administrator should receive an email confirming when they open an investigation on an incident.

##Preconditions 
+ The user must already be registered with an email address and password.
+ The user must have system administrator permissions.
+ An investigation has not previously been instigated for the incident in question.

##Assumptions
+ A supported browser is being used.
+ The user has access to the inbox for the email address they registered onto the system with.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Open)'.

6 Click the 'Save changes' button.

##Expected Result
The user receives an email containing the following message:

>**YorSafety: Investigation questions initiated**

>You have changed the status to 'Investigation (Open)'.  This has initiated the Investigations questions, and the Case Lead has been notified.

##Concurrent Expected Results

See [Opening an Investigation - Notification to Assistant Director](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-2.md)

See [Opening an Investigation - Notification to Health & Safety Co-ordinator](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-4.md)

See [Opening an Investigation - Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-5.md)

See [Opening an Investigation - Notification to Injured Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-6.md)