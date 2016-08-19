[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Authorising an Investigation - Authorise Button not visible

##Description
An 'Authorise' button should *not* appear on an Investigation Form once it has been finalised unless the user is the Accountable Person for that incident.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The person the incident happened to must have an Accountable Person (e.g. Assistant Director).
+ The Case Status for the incident in question must be 'Investigation (Review)'

##Assumptions
+ A supported browser is being used.
+ The tester has access to the system account for the Case Lead of the incident in question.
+ The tester has access to the system account for the Health & Safety Co-ordinator of the incident in question.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the incident in question.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Finalised)'.

6 Click the 'Save changes' button.

##Expected Results
+ An 'Authorise' button does *not* appears in the bar at the top of the investigation form.
