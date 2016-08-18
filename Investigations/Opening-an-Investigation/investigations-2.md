[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Opening an Investigation - Notification to Accountable Person

##Description
A user should receive an email informing them when an investigation has been opened on an incident for which they are the Accountable Person.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The person the incident happened to must have an Accountable Person (e.g. Assistant Director).
+ The incident in question must not have a Status of 'Delete'.
+ An investigation has not previously been instigated for the incident in question.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the Accountable Person of the incident in question.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Open)'.

6 Click the 'Save changes' button.

##Expected Result
The Accountable Person of the person the incident happened to receives an email containing the following message:

>**YorSafety: Investigation questions initiated**

>An investigations questions procedure has been initiated.  You will be notified by email again when this case requires review and authorisation.  You can monitor the progress of this incident by logging in to [Yorsafety](https://www.yorsafety.org.uk).

##Concurrent Expected Results

See [Notification to Health & Safety Allocated Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-1.md)

See [Notification to Health & Safety Co-ordinator](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-4.md)

See [Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-5.md)

See [Notification to Injured Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-6.md)
