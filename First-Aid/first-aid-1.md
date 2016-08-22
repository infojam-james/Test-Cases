[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Incident Logging - Submitting a non work-related incident

##Description
A user should be able to indicate that a new incident is non work-related.

##Preconditions
+ The user must already be registered with an email address and password.

##Assumptions
+ A supported browser is being used.

##Test Steps:

1 Log in to the system

2 Click the 'Log New Incident' button

3 Complete all mandatory questions in Sections 1-3 of the incident form

4 From the 'Category' question (in 'Section 4: Type'), select any option *except* 'Fatality'

5 Complete all other mandatory questions in Section 4

6 From the 'Was the incident work related?' question (in 'Section 5: Further Info'), select 'No'

7 Complete all subsequent mandatory questions in Section 5

8 Click the 'Submit' button

##Expected Results

+ A new incident is logged with the status 'Not Work Related'
