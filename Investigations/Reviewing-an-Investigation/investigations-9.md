[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Reviewing an Investigation - Notification to Case Lead

##Description
A Case Lead should receive an email notification when they have submitted a completed Investigations Form.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The incident in question must have a Case Lead.
+ The Case Status for the incident in question must be 'Investigation (Open)'.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the Case Lead of the incident in question.

##Test Steps:

1 Navigate to the 'Investigation' tab of the incident in question.

2 Answer all mandatory questions.

3 Click the 'Complete Investigation' button.

##Expected Result
The Case Lead receives an email containing the following message:

>**YorSafety: Investigation questions completed - awaiting review**

>Thank you for completing all the mandatory investigation questions. The case is now under review with the Health & Safety Team. You will be notified by email if you are required to amend any of the details you have entered. If no amendments are required the Senior Accountable Person (e.g. AD/Head Teacher) will be contacted to authorise the investigation and associated action plan. 

##Concurrent Expected Results

See [Status Change](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-8.md)

See [Notification to Health & Safety Allocated Person](https://github.com/infojam-james/test-cases/edit/master/Investigations/Reviewing-an-Investigation/investigations-7.md)
