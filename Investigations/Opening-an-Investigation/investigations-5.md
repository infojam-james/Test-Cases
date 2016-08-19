[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Opening an Investigation - Notification to Case Lead

##Description
A user should receive an email informing them when an investigation has been opened on an incident for which they are the Case Lead.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The incident in question must have a Case Lead.
+ The incident in question must not have a Status of 'Delete'.
+ An investigation has not previously been instigated for the incident in question.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the Case Lead of the incident in question.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Open)'.

6 Click the 'Save changes' button.

##Expected Result
The Case Lead receives an email containing the following message:

>**YorSafety: Investigation questions initiated**

>An investigation has been initiated.  As the individual designated as responsible for this case, you are required to complete further questions.  Please log into [Yorsafety](https://www.yorsafety.org.uk) and visit the 'Investigation' tab in the relevant Incident Dashboard.

##Concurrent Expected Results

See [Notification to Health & Safety Allocated Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-1.md)

See [Notification to Accountable Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-2.md)

See [Notification to Health & Safety Co-ordinator](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-4.md)

See [Notification to Injured Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-6.md)
