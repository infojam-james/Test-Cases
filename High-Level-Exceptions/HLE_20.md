[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#High Severity: Notification not to be sent more than once

##Description
No High-Level Alert email should be sent if a case is flagged as High Severity if a High-Level Alert email has been sent previously.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have edit permissions to the case in question.
+ The tester is logged in.
+ A suitable test case has been created.
+ The 'Will this cause £10k+ in lost revenue?' question for the case is *not* set to 'Yes'.
+ The 'Will this cause reputational damage?' question for the case is *not* set to 'Yes'.
+ The 'Severity' of the case is set to 'Medium', 'Low', or is blank.
+ The case in question has an Accountable Person.
+ The case in question has a Health & Safety Allocated Person.
+ The tester has access to the email inbox associated with the Accountable Person's user account.
+ The tester has access to the email inbox associated with the Health & Safety Allocated Person's user account.
+ The tester has access to the Health & Safety Team email inbox.
+ The 'High-Level Email Sent' flag in the database is set to 'Yes'.

##Assumptions
+ A supported browser is being used.

##Test Steps
1 Navigate to the test case

2 Click the 'Options' button

3 Select 'Status / Allocation Update'

4 From the 'Severity' drop-down, select 'High'

5 Click the 'Save Changes' button

##Expected Results

+ No email notifications should be received
