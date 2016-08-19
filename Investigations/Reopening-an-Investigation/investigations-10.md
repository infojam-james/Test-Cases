[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Re-opening an Investigation - Notification to Case Lead

##Description
A Case Lead should receive an email notification when they are required to make amendments to an investigation that has been previously submitted.

##Preconditions 
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The incident in question must have a Case Lead.
+ The Case Status for the incident in question must be 'Investigation (Review)'.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox for the Case Lead of the incident in question.

##Test Steps:

1 Navigate to the incident in question.

2 Click the 'Options' button.

3 Select 'Status/Allocation Update'.

4 From the 'Status' field, select 'Investigation (Open)'.

5 Click the 'Save Changes' button.

##Expected Result
The Case Lead receives an email containing the following message:

>**Yorsafety: Investigation questions returned to Case Lead**

>This investigation has been reviewed by the Health & Safety Team, and you are required to amend some of the details you previously entered.  Please log into [Yorsafety](https://www.yorsafety.org.uk) and visit the 'Investigation' tab in the relevant Incident Dashboard.
