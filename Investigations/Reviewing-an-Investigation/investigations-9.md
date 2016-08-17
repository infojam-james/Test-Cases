[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Reviewing an Investigation - Notification to Case Lead

##Description
A Case Lead should receive an email notification when they have submitted a completed Investigations Form.

##Preconditions 
+ The user must already be registered with an email address and password.
+ The user must be Case Lead for the incident in question.
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

>You have completed all required Investigation questions.  The case is now under review with the Health & Safety Team.  You will be notified by email if you are required to amend any of the details you have entered.  

##Concurrent Expected Results

See [Submitting an Investigation - Status Change](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-8.md)

See [Reviewing an Investigation - Notification to Health & Safety Team](https://github.com/infojam-james/test-cases/edit/master/Investigations/Reviewing-an-Investigation/investigations-7.md)
