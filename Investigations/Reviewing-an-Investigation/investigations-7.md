[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Reviewing an Investigation - Notification to Health & Safety Allocated Person

##Description
A user should receive an email confirming when a completed investigation form is submitted on an incident for which they are the health & safety allocated person.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The incident in question must have a health & safety allocated person.
+ The Case Status for the incident in question must be 'Investigation (Open)'.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the health & safety allocated person of the incident in question.

##Test Steps:

1 Navigate to the 'Investigation' tab of the incident in question.

2 Answer all mandatory questions.

3 Click the 'Complete Investigation' button.

##Expected Result
The health & safety allocated person receives an email containing the following message:

>**YorSafety: Investigation questions completed - awaiting review**

>The Investigations questions associated with this incident have been completed by the Case Lead.  You are now required to review the investigation and either amend or finalise.

##Concurrent Expected Results

See [Status Change](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-8.md)

See [Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-9.md)
