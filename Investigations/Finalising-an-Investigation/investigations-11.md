[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Finalising an Investigation - Notification to Accountable Person

##Description
A user should receive an email informing them when an investigation has been finalised on an incident for which they are the Accountable Person.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The person the incident happened to must have an Accountable Person (e.g. Assistant Director).
+ The Case Status for the incident in question must be 'Investigation (Review)'.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the Accountable Person of the incident in question.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Finalised)'.

6 Click the 'Save changes' button.

##Expected Result
The Accountable Person of the person the incident happened to receives an email containing the following message:

>**YorSafety: Investigation finalised**

>This investigation has been finalised and now requires authorisation.  Please log in to [Yorsafety](https://www.yorsafety.org.uk), where you will find the case on your dashboard.

##Concurrent Expected Results

See [Notification to Health & Safety Co-ordinator]

See [Notification to Case Lead]
