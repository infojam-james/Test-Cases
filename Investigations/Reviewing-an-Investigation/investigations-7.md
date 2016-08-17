[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Reviewing an Investigation - Notification to Health & Safety Team

##Description
A system administrator should receive an email confirming when a completed Investigation form is submitted.

##Preconditions 
+ The user must already be registered with an email address and password.
+ The user must have system administrator permissions.
+ The Case Status for the incident in question must be 'Investigation (Open)'.

##Assumptions
+ A supported browser is being used.
+ The user has access to the inbox for the email address they registered onto the system with.

##Test Steps:

1 Navigate to the 'Investigation' tab of the incident in question.

2 Answer all mandatory questions.

3 Click the 'Complete Investigation' button.

##Expected Result
+ The user receives an email containing the following message:

>**YorSafety: Investigation questions completed - awaiting review**

>The Investigations questions associated with this incident have been completed by the Case Lead.  You are now required to review the investigation and either amend or finalise.

##Concurrent Expected Results

See [Status Change](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-8.md)

See [Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-9.md)
