[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Pre-populating the First Aid form

##Description
When a Confidential First Aid form is generated, the following fields should be pre-populated with information previously entered at the time of the incident's recording.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have system administrator permissions.
+ The categorisation for the incident prompted the 'Was First Aid administered?' question.
+ The 'Was First Aid administered?' question for the incident was answered 'Yes'.

##Assumptions
+ A supported browser is being used.
+ All mandatory questions were completed when recording the incident in question.

##Test Steps:

1 Navigate to the 'My Tasks' screen of the incident in question

2 Click the 'Options' button

3 Select 'Print Incident Only' (this will open a new browser window containing the Incident Report Form)

4 Click the 'Options' button

5 Select 'Print First Aid Form'

6 Select the new browser window containing the First Aid form

5 Ensure the text entered matches that entered into the equivalent field from the Incident Report Form:

|First Aid Form field|Equivalent Incident Report Form field|Incident Report Form section|
|--------------------|:------------------------------------|:---------------------------|
|Name of Casualty|Forename *&* Surname|2: Their Details|
|Job Title|Job Title|2: Their Details|
|Incident Location|Incident Address|3: Where & When|
|Age|Age|2: Their Details|
|Employee|*Insert tick if* Are you/Are they *is* **'Employee'**|1: Who|
|Pupil|*Insert tick if* Are you/Are they *is* **'Pupil'**|1: Who|
|Member of public|*Insert tick if* Are you/Are they *is* **'Member of Public'**|1: Who|
|Customer/Resident|*Insert tick if* Are you/Are they *is either* **'Customer'** *or* **'Resident'**|1: Who|
|Other (specify)|Are you/Are they *(text) if* Are you/Are they *is not* **'Employee','Pupil','Member of Public','Customer'** *or* **'Resident'**|1: Who|
|Incident date|Date of Incident|3: Where & When|
|Incident time|Time of Incident|3: Where & When|
|Nature of injury|Injury Detail / Treatment|5: Further Info|
|Treatment administered/advice given|Advice given / received|5: Further Info|
|Referred for medical attention (Yes/No)|Were they referred for medical attention?|5: Further Info|
|Time of treatment: (24 hour clock)|Time of Treatment?|5: Further Info|
|Name of first aider or approved person:|Name of First Aider?|5: Further Info|

##Expected Results
+ The First Aid form should be pre-populated with the exact information entered into the incident form.
+ It should be possible to edit the information pre-populating the fields in the First Aid form.
