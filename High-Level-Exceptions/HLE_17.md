[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Reputational Damage: Do not send notification if 'Update' not clicked

##Description
No High-Level Alert email should be sent if a case is flagged as causing reputational damage, but the 'Update' button is not clicked.

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

2 Navigate to the 'My Tasks' tab

3 Click the drop-down box for 'Will this cause reputational damage?'

4 Select 'Yes'

5 Do *not* click the 'Update' button

##Expected Results

+ No email notifications should be received
