[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#10k+: Notification to Health & Safety Allocated Person

##Description
The Health & Safety Allocated Person on a case should receive an email if a case is flagged as causing £10,000 or more in lost revenue if the case does not have an Accountable Person.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have edit permissions to the case in question.
+ The tester is logged in.
+ A suitable test case has been created.
+ The 'Will this cause £10k+ in lost revenue?' question for the case is not set to 'Yes'.
+ The 'Will this cause reputational damage?' question for the case is not set to 'Yes'.
+ The 'Severity' of the case is set to 'Medium', 'Low', or is blank.
+ The 'High-Level Email Sent' flag in the database is *not* set to 'Yes'.
+ The case in question does *not* have an Accountable Person.
+ The case in question has a Health & Safety Allocated Person.
+ The tester has access to the email inbox associated with the Health & Safety Allocated Person's user account.

##Assumptions
+ A supported browser is being used.

##Test Steps
1 Navigate to the test case

2 Navigate to the 'My Tasks' tab

3 Click the drop-down box for 'Will this cause £10k+ in lost revenue?'

4 Select 'Yes'

5 Click the 'Update' button

##Expected Results

+ The Health & Safety Allocated Person receives the following email:

>**[Case ID] Yorsafety: Incident Alert (no Accountable Person)**

>An alert was triggered for this incident, but the case currently has no Accountable Person allocated to it.  You will need to identify the Accountable Person, notify them of the incident, and add them to the case Permissions.

>You should use the Notes section of the case to record this.

+ The 'High-Level Email Sent' flag in the database is changed to 'Yes'.
