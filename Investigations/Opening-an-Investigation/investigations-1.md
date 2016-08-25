[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Opening an Investigation - Notification to Health & Safety Allocated Person

##Description
A user should receive an email confirming when an investigation is opened on an incident for which they are the health & safety allocated person.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The incident in question must have a health & safety allocated person.
+ The incident in question must not have a Status of 'Delete' or 'Investigation (Open)' or 'Investigation (Review)'.
+ An investigation has not previously been instigated for the incident in question.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the health & safety allocated person of the incident in question.

##Test Steps:

1 Navigate to the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Change the Status to 'Investigation (Open)'.

6 Click the 'Save changes' button.

##Expected Results
+ The health & safety allocated person receives an email containing the following message:

>**YorSafety: Investigation questions initiated**

>The status of the case has been changed to 'Investigation (Open)'.

+ The health & safety allocated person can see the case on their dashboard, with the status 'Investigation (Open)'.

##Concurrent Expected Results

See [Notification to Accountable Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-2.md)

See [Notification to Health & Safety Co-ordinator](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-4.md)

See [Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-5.md)

See [Notification to Injured Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-6.md)
