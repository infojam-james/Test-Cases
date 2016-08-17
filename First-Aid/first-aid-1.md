#Incident Logging - Submit non work-related incident

##Description
A user should be able to indicate that a new incident is non work-related.

##Preconditions
+ The user must already be registered with an email address and password.

##Assumptions
+ A supported browser is being used.
+ The user has completed all other mandatory fields in the incident reporting form.
+ The incident did not involve a fatality.

##Test Steps:

1 Navigate to screen 5 ('Further Info') of the incident form

2 In the 'Was the incident work related?' field, enter 'No'

3 Click the ‘Submit’ button

##Expected Result
A new incident is logged with the status 'Not Work Related'

[Return to Contents](Contents.md)
