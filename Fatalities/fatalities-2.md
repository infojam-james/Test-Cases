[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Health & Safety Team notification of a work-related fatality

##Description
The Health & Safety team should receive a notification when a work-related incident has resulted in a fatality.

##Preconditions
+ The tester must already be registered with an email address and password.

##Assumptions
+ A supported browser is being used.
+ The tester has access to the central email inbox for the Health & Safety Team.

##Test Steps:

1 Log in to the system

2 Click the 'Log New Incident' button

3 Complete all mandatory questions in Sections 1-3 of the incident form

4 From the 'Category' question (in 'Section 4: Type'), select 'Fatality'

5 Complete all other mandatory questions in Section 4

6 From the 'Was the incident work related?' question (in 'Section 5: Further Info'), select 'Yes'

7 Complete all subsequent mandatory questions in Section 5

8 Click the 'Submit' button

##Expected Result

The Health & Safety Team mailbox receives an email containing the following message:

>**YorSafety: Fatality reported (work-related)**

>
