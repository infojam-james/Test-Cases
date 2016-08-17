[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Submitting an Investigation - Status Change

##Description
The Case Status of an incident should change when a completed Investigation form is submitted.

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
+ The Status of the incident in question changes to 'Investigation (Review)'.

##Concurrent Expected Results

See [Reviewing an Investigation - Notification to Health & Safety Team](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-7.md)

See [Reviewing an Investigation - Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-9.md)
