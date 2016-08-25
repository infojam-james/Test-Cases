[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Authorising an Investigation - Authorise Button for Accountable Person

##Description
An 'Authorise' button, visible only to the Accountable Person (e.g. Assistant Director) should appear on an Investigation Form once it has been finalised.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The tester must be logged in.
+ The person the incident happened to must have an Accountable Person (e.g. Assistant Director).
+ The Case Status must be 'Investigation (Review)'

##Assumptions
+ A supported browser is being used.
+ The tester has access to the system account for the Accountable Person.

##Test Steps:

1 Navigate to the 'My Tasks' tab of the case.

2 Click the 'Options' button.

3 Select 'Status / Allocation Update'.

4 Click the 'Status' field.

5 Select 'Investigation (Finalised)'.

6 Click the 'Save changes' button.

##Expected Results
+ The Accountable Person can see an 'Authorise' button appears in the bar at the top of the investigation form.
