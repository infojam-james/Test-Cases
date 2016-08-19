[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Authorising an Investigation - Notification to Health & Safety Allocated Person

##Description
A user should receive an email informing them when an investigation has been authorised on an incident for which they are the health & Safety Allocated Person..

###Preconditions 
+ The tester is logged in as the Accountable Person for the incident in question.
+ The Case Status for the incident in question must be 'Investigation (Finalised)'.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the email inbox of the Health & Safety Allocated Person.

##Test Steps:

1 Navigate to the 'Investigation' tab of the incident in question.

2 Click the 'Authorise' button.

##Expected Result
The Health & Safety Allocated Person of the incident receives an email containing the following message:

>**YorSafety: Investigation authorised**

>This investigation has now been authorised by the Accountable Person and is now ready to be closed.
