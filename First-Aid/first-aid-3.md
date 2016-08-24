[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Pre-populating the First Aid form

##Description
When a Confidential First Aid form is generated, the form should be pre-populated with information previously entered at the time of the recording the incident.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety system administrator permissions.
+ The tester is logged in.
+ The categorisation for the incident prompted the 'Was First Aid administered?' question.
+ The 'Was First Aid administered?' question for the incident was answered 'Yes'.
+ The Case Status must be 'Closed'.

##Assumptions
+ A supported browser is being used.
+ All mandatory questions were completed when recording the incident in question.

##Test Steps:

1 Navigate to the case in question

2 Navigate to the 'My Tasks' tab

3 In the 'Documents' section, select 'First Aid Form' *(this will open a new browser window containing the First Aid Form)*

4 Click the 'Options' button

5 Select 'Print Incident Only' *(this will open a new browser window containing the Incident Report Form)*

6 Select the browser window containing the First Aid form

7 Compare the text in the fields of the two forms in accordance with the below table:

|First Aid Form field|Matching Incident Report Form field|Incident Report Form section|
|--------------------|:------------------------------------|:---------------------------|
|Name of Casualty|Forename *and* Surname|2: Their Details|
|Job Title|Job Title|2: Their Details|
|Incident Location|Incident Address|3: Where & When|
|Age|Age|2: Their Details|
|Person Type|Person Type|1: Who|
|Incident date|Date of Incident|3: Where & When|
|Incident time|Time of Incident|3: Where & When|
|Follow up with Parent/Guardian?|Was there communication with Parent / Carer?|5: Further Info|
|Nature of injury|Detail of Incident|5: Further Info|
|Treatment administered/advice given|Injury Detail / Treatment *and* Advice given / received|5: Further Info|
|Referred for medical attention?|Were they referred for medical attention?|5: Further Info|
|If YES, give details:|Please give details *(prompted by answering 'Yes' to 'Were they referred for medical attention?')*|5: Further Info|
|Time of treatment: (24 hour clock)|Time of Treatment?|5: Further Info|
|Name of first aider or approved person:|Name of First Aider?|5: Further Info|
|IRF Ref. no.|Case Reference #|-|

##Expected Results
+ The First Aid form should be pre-populated with the exact information entered into the incident form.
+ It should be *not* be possible to edit the information pre-populating the First Aid form.
