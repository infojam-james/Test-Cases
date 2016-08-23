[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Finalising an Investigation - Notification to Case Lead

##Description
A user should receive an email informing them when an investigation has been finalised on an incident for which they are the Case Lead.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The case in question must have a Case Lead.
+ The Case Status must be 'Investigation (Review)'.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the Case Lead.

##Test Steps:

1 Navigate to the case in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Finalised)'.

6 Click the 'Save changes' button.

##Expected Result
The Case Lead of the incident receives an email containing the following message:

>**YorSafety: Investigation finalised**

>This investigation has been finalised by the Health & Safety Team.  You will notified again when it has been authorised.

##Concurrent Expected Results

See [Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Finalising-an-Investigation/investigations-11.md)
