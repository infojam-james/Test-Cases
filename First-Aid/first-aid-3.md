#First Aid form - pre-population

##Description
When a Confidential First Aid form is generated, the following fields should be pre-populated with information previously entered at the time of the incident logging.

##Preconditions
+ The user must already be registered with an email address and password.
+ The user must have system administrator permissions.
+ All mandatory questions were completed when recording the incident in question.
+ The categorisation for the incident prompted the 'Was First Aid administered?' question.
+ The 'Was First Aid administered?' question for the incident was responded 'Yes'.

##Assumptions
+ A supported browser is being used.

##Test Steps:

1 Navigate to the 'My Tasks' screen of the incident in question

2 Click the 'Options' button

3 Select 'Print Incident Only' (this will open a new browser window containing the Incident Report Form)

4 Click the 'Options' button

5 Select 'Print First Aid Form'

6 Select the new browser window containing the First Aid form

5 Ensure the text entered matches that entered into the equivalent field from the Incident Report Form:

|First Aid Form field|Equivalent Incident Report Form field
|--|:--|
|Name of Casualty|Forename & Surname|
|Job Title|Job Title|
|Incident Location|Incident Address|
|Age|Age|
|Did the incident occur to: (multiple choice)|Are you/Are they|
|Other (specify)|Are you/Are they (if all previous blank|
|Incident date|Date of Incident|
|Incident time|Injury Detail / Treatment|
|Nature of injury|Advice given / received|
|Treatment administered/advice given|
|Referred for medical attention (Yes/No)|Were they referred for medical attention?|
|Time of treatment: (24 hour clock)|Time of Treatment?|
|Name of first aider or approved person:|Name of First Aider?|

##Expected Result
The First Aid form should be pre-populated with the exact information entered into the incident form.

[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)
