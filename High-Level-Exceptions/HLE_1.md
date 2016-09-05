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
+ No High-Level Alert email associated with this case has previously been sent.
+ The case in question has an Accountable Person.

##Assumptions
+ A supported browser is being used.

##Test Steps:
1 Navigate to the test case

2 Navigate to the 'My Tasks' tab

3 Click the drop-down box for 'Will this cause £10k+ in lost revenue?'

4 Select 'Yes'

5 Click the 'Update' button

##Expected Results
