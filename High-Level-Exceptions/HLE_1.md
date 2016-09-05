[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#10k+: Notification to Accountable Person

##Description
The Accountable Person on a case should receive an email if a case is flagged as causing £10,000 or more in lost revenue.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have edit permissions to the case in question.
+ The tester is logged in.
+ A suitable test case has been created.
+ The 'Will this cause £10k+ in lost revenue?' question for the case is not set to 'Yes'.
+ The 'Will this cause reputational damage?' question for the case is not set to 'Yes'.
+ The 'Severity' of the case is set to 'Medium', 'Low', or is blank.
+ The 'High-Level Email Sent' flag in the database is *not* set to 'Yes'.
+ The case in question has an Accountable Person.
+ The tester has access to the email inbox associated with the Accountable Person's user account.

##Assumptions
+ A supported browser is being used.

##Test Steps
1 Navigate to the test case

2 Navigate to the 'My Tasks' tab

3 Click the drop-down box for 'Will this cause £10k+ in lost revenue?'

4 Select 'Yes'

5 Click the 'Update' button

##Expected Results

+ The Accountable Person receives the following email:

>**[Case ID] Yorsafety: Incident Alert**

>An incident has been reported which you are connected to that has triggered an alert.  This will be for one of the following reasons:

>+ The H&S team have categorised the severity of the incident as 'high' (this will include all incidents that are RIDDOR reportable)

>+ The incident has the potential to cause reputational damage

>+ The incident has, or is likely to cause, damage of £10,000 or above

>You can monitor the progress of this incident by logging in to Yorsafety.

+ The 'High-Level Email Sent' flag in the database is changed to 'Yes'.
