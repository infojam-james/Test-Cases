#First Aid form - pre-population

##Description
When a Confidential First Aid form is generated, the following fields should be pre-populated with information previously entered at the time of the incident logging.

##Preconditions
+ The user must already be registered with an email address and password.
+ The user must have system administrator permissions.
+ All mandatory questions were completed when recording the incident in question.
+ The incident in question has the Status 'Not Work Related (Closed)'.

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

| First Aid Form field|Equivalent Incident Report Form field
|--------------------|:------------------|
|Name of Casualty|
|Job Title|
|Incident Location|
|Age|
|Did the incident occur to: (multiple choice)|
|Incident date|
|Incident time|
|Nature of injury|
|Treatment administered/advice given|
|Referred for medical attention (Yes/No)|



##Expected Result
A page displaying the gmail user’s inbox should load, showing any new message at the top of the page.
