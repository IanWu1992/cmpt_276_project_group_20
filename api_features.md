

Api's
1. Google Calendar Api
Allows to plan future events and look at past events
https://developers.google.com/calendar/api/v3/reference
2. Strava Api
Allows for creation of running workout stores time,distance
https://developers.strava.com/docs/reference/#api-Activities-getActivityById



The two chosen api's to implement are, the google calendar and strava. These apis form a symbiotic relationship for our applications. The google calendar api gives a way to make future events in the user google calendar. Mean while the strava api records the information of the workout and also posting to strava. Using the google calendar api to store the date, time and strava events ID. Using the latter to recall the information of the workout.

The first feature is the ability to plan future workouts. The user can input the time and date which will get stored in google calendar

The second feature is to see up coming events. Since we inputed the events into google calendar we can see in the actual calendar app or by going to our application. The calendar stores the date and time of the specified workout after getting input from user.

The third feature is inputting workouts into strava. Users can either input from list of scheduled workouts or create new workout that was not scheduled. Users input distance and time of workout along with date and time if not scheduled. A strava event is created the id for this event is stored in the google calendar event for recall.

The fourth feature is the recall of past workouts. Using the google calendar api we can see all past workouts. If we store the strava id number in the google calendar event, we can recall the information of the workouts.

	