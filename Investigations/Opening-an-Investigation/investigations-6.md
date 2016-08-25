[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Opening an Investigation - Notification to Injured Person

##Description
A user should receive an email confirming when an investigation is opened on an incident that happened to them.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ An email address must have been entered into the 'Email' field on the incident form.
+ The incident in question must not have a Status of 'Delete' or 'Investigation (Open)' or 'Investigation (Review)'.
+ An investigation has not previously been instigated for the incident in question.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the person that the incident in question happened to.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Change the Status to 'Investigation (Open)'.

6 Click the 'Save changes' button.

##Expected Result
The user receives an email containing the following message:

>**YorSafety: Investigation questions initiated**

>Further investigation is being carried out on your incident.  You will be able to review the details of the incident once the case has been closed.  If you required any further information in the meantime, contact your Line Manager or the Health & Safety Team.

##Concurrent Expected Results

See [Notification to Health & Safety Allocated Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-1.md)

See [Notification to Accountable Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-2.md)

See [Notification to Health & Safety Co-ordinator](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-4.md)

See [Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-5.md)
