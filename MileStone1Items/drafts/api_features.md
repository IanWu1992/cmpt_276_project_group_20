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

The fifth feature is Local Notification Sync. When users plan their workouts, they can opt-in to receive local notifications. This feature utilizes the Google Calendar API to create an event and then leverages the local storage to set up reminders. Users will receive alerts on their devices for upcoming workouts, enhancing their ability to stay on schedule.

The sixth feature is Activity Summaries. Our application integrates with the Strava API to provide users with a snapshot of their recent workouts directly on their dashboard. This summary includes key metrics such as distance, pace, and overall time, drawn from the latest synced data with Strava. By storing this data locally, users can access their activity overview quickly, offering insights into their performance without the need for constant data retrieval from a backend server.
