# The Automatic Scheduler Program (TASP)

## Demo
![TASP Demo Gif](https://user-images.githubusercontent.com/55507356/99181838-07cad900-26e6-11eb-8ec1-d4da66189f1f.gif)

## About

TASP takes the user availability schedule and creates a study plan that helps them prepare for Assignments, Projects, or Exams.
The program prioritizes certain tasks depending on their Due Date & Due Time.
The calculated schedule is then imported to Google Calendars automatically upon task input/submission. 
The user may then refer to the Google calender at any given time.

## Usage

1. Run `pip install tkcalendar` to install tkcalendar module

2. Follow steps [here](https://www.developers.google.com/calendar/quickstart/python) to install Google Calendar API
	* Rename downloaded `credentials.json` file to "client_secret.json" and include it in your directory

3. Run `UI.py`
	* New window will prompt you to login to a google account, Login
	* If 2 step verification is enabled, accept the sent email

4. Once User interface is shown, rerun `UI.py`

## Directions for using Program
	
	1. Enter current availability schedule (availability for the term) & Select "Save Time"
	2. Enter Course Name
	3. Enter description of task for given class
	4. Select Due Date & Due Time for task
	5. Select Difficulty for task (easy, moderate, hard)
	6. Enter Weightage (%) the task has towards final grade 
	7. Select readiness for the given task (not prepared, somewhat prepared, fully prepared)
	8. Click "Generate Summary and Add to Calendar"

Once all steps are completely, user may ignore step 1 and continue to add tasks if needed. 
Once the user has entered all information about particular tasks, the system calculates the suggested time for the user
to spend on the given task. The task is then added to the users Google Calendar with the suggested time of study.

## Work Flow

	- Project rolled out using agile methodology with 2 sprints
	- 1st sprint was focused on creating the task class and ui and then understanding how to work with the Google API 
	- 2nd sprint was focused on integrating all parts and creating a task allocation algorithm 

## Future Improvements

	1. System learns from User to create better required study time equation.
	2. Improved UI design.
	3. Optimizing algorithms to improve efficieny and space.
	4. Deploying the program online so that program is more easily accessable .

## Sources

* [tkcalendar](https://www.youtube.com/watch?v=A0gaXfM1UN0&list=PLQVvvaa0QuDclKx-QpC9wntnURXVJqLyk&index=2)
* [tkcalendar](https://www.youtube.com/watch?v=YXPyB4XeYLA&t=14076s)
* [Google Calendar API](https://developers.google.com/calendar/quickstart/python)
* [Google Calendar API](https://www.youtube.com/watch?v=1JkKtGFnua8&t=1s)
* [Google Calendar API](https://www.youtube.com/watch?v=j1mh0or2CX8&ab_channel=IndianPythonista)
