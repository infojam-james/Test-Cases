[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Submitting an Investigation - Status Change

##Description
The Case Status of an incident should change when a completed Investigation form is submitted.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety administrator permissions.
+ The Case Status for the incident in question must be 'Investigation (Open)'.

##Assumptions
+ A supported browser is being used.
+ The test has access to the user account of the Accountable Person for the incident in question.

##Test Steps:

1 Navigate to the 'Investigation' tab of the incident in question.

2 Answer all mandatory questions.

3 Click the 'Complete Investigation' button.

##Expected Results
+ The Case Status of the incident in question changes to 'Investigation (Review)'.

##Concurrent Expected Results

See [Notification to Health & Safety Allocated Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-7.md)

See [Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Reviewing-an-Investigation/investigations-9.md)

