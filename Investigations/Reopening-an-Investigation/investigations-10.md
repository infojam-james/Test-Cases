[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Reopening an Investigation - Notification to Case Lead

##Description
A Case Lead should receive an email notification when an Investigation incident in Review is returned to them for further information.

##Preconditions 
+ The user must already be registered with an email address and password.
+ The user must have system administration permission.
+ The Case Status for the incident in question must be 'Investigation (Review)'.
+ All mandatory fields in the Investigation Form must be complete.

##Assumptions
+ A supported browser is being used.
+ The Case Lead of the incident in question has access to the inbox for the email address they registered onto the system with.

##Test Steps:

1 Navigate to the incident in question.

2 Click the 'Options' button.

3 Select 'Status/Allocation Update'.

4 From the 'Status' field, select 'Investigation (Open)'.

5 Click the 'Save Changes' button.

##Expected Result
+ The Case Lead receives an email containing the following message:

>**Yorsafety: Investigation questions returned to Case Lead**

>The Investigation questions have been reviewed by the Health & Safety, and you are required to amend some of the details you previously entered.  Please log into Yorsafety and visit the 'Investigation' tab in the relevant Incident Dashboard.
