[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Opening an Investigation - Notification to Health & Safety Co-ordinator

##Description
A user should receive an email informing them when an investigation has been opened on an incident for which they are the Health & Safety Co-ordinator.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The Service/Team selected in the incident form must have a Health & Safety Co-ordinator.
+ The incident in question must not have a Status of 'Delete' or 'Investigation (Open)' or 'Investigation (Review)'.
+ An investigation has not previously been instigated for the incident in question.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the Health & Safety Co-ordinator of the Service/Team of the incident in question.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Change the Status to 'Investigation (Open)'.

6 Click the 'Save changes' button.

##Expected Result
The Health & Safety Co-ordinator receives an email containing the following message:

>**YorSafety: Investigation questions initiated**

>An investigation has been initiated. You can monitor the progress of this incident by logging in to [Yorsafety](https://www.yorsafety.org.uk).  You will be notified by email again when this case has been authorised.  

##Concurrent Expected Results

[Notification to Health & Safety Allocated Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-1.md)

[Notification to Assistant Director](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-2.md)

[Notification to Case Lead](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-5.md)

[Notification to Injured Person](https://github.com/infojam-james/test-cases/blob/master/Investigations/Opening-an-Investigation/investigations-6.md)
