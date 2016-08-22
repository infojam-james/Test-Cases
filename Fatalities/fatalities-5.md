[Return to Contents](https://github.com/infojam-james/test-cases/blob/master/Contents.md)

#Making the 'Fatal Accident Response Team Meeting Record' available

##Description
The 'Fatal Accident Response Team Meeting Record' should become available to health & safety system administrators when an incident concerning a fatality is recorded.

##Preconditions
+ The tester must already be registered with an email address and password.
+ The tester must have health & safety administrator permissions.
+ The Category Type of the incident question must have been recorded as 'Fatality'.

##Assumptions
+ A supported browser is being used.

##Test Steps:

1 Log in to the system

2 Navigate to the incident in question

3 Click the 'Options' button

4 Select 'Open Fatal Accident Response Team Meeting Record'

##Expected Results
+ A new browser window should open containing the Fatal Accident Response Team Meeting Record

##Concurrent Expected Results
EITHER
+ [Health & Safety Team notification of a non work-related fatality](https://github.com/infojam-james/test-cases/blob/master/Fatalities/fatalities-1.md)

OR

+ [Health & Safety Team notification of a work-related fatality](https://github.com/infojam-james/test-cases/blob/master/Fatalities/fatalities-2.md)

AND

+ [Making the 'Fatality Action Plan' available](https://github.com/infojam-james/test-cases/blob/master/Fatalities/fatalities-3.md)
+ [Making the 'Fatal Site Checklist' available](https://github.com/infojam-james/test-cases/blob/master/Fatalities/fatalities-4.md)
+ [Making the 'Health & Safety Manager's Action Card' available]
+ [Making the 'Educational Visits Critical Incident Checklist' available]
