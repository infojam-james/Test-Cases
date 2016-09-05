[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#High Severity: Do not send notification if 'Close' button clicked

##Description
No High-Level Alert email should be sent if a case is flagged as High Severity, but the 'Close' button is clicked instead of the 'Save Changes' button

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have edit permissions to the case in question.
+ The tester is logged in.
+ A suitable test case has been created.
+ The 'Will this cause £10k+ in lost revenue?' question for the case is *not* set to 'Yes'.
+ The 'Will this cause reputational damage?' question for the case is *not* set to 'Yes'.
+ The 'Severity' of the case is set to 'Medium', 'Low', or is blank.
+ The 'High-Level Email Sent' flag in the database is *not* set to 'Yes'.
+ The case in question has an Accountable Person.
+ The case in question has a Health & Safety Allocated Person.
+ The tester has access to the email inbox associated with the Accountable Person's user account.
+ The tester has access to the email inbox associated with the Health & Safety Allocated Person's user account.
+ The tester has access to the Health & Safety Team email inbox.

##Assumptions
+ A supported browser is being used.

##Test Steps
1 Navigate to the test case

2 Click the 'Options' button

3 Select 'Status / Allocation Update'

4 From the 'Severity' drop-down, select 'High'

5 Click the 'Close' button

##Expected Results

+ No email notifications should be received
