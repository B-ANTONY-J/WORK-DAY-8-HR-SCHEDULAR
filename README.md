# WORK-DAY-8-HR-SCHEDULAR

Criteria:

Create a simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery. The app should display standard business hours (9 a.m. to 5 p.m.). Each time slot should represent one hour and contain the following:

*The time

*A field to hold user input

*A save button

The Below Task are accomplished when interacting with the Work Day Schedular

GIVEN I am using a daily planner to create a schedule

WHEN I open the planner
 ==> You will have the saved events for my calendar for the current day
 
THEN the current day is displayed at the top of the calendar

WHEN I scroll down
==>  I can view the Time Block and interact with each Entry Block then Save(disc button) any where from 9 am - 5 pm

THEN I am presented with timeblocks for standard business hours

WHEN I view the timeblocks for that day
==> I can enter what needs to be sceduled for that time frame

THEN each timeblock is color coded to indicate whether it is in the past, present, or future

WHEN I click into a timeblock
==>The expired time will Highlight as Gray, The Current Time will Highlight as Red and the Future Time will Highlight as Green

THEN I can enter an event

WHEN I click the save button for that timeblock
==>Once the event is entered you can save and if you forget to save the save button generates a a flash popup to indicate an "unsaved" item

THEN the text for that event is saved in local storage

WHEN I refresh the page
==> The event is saved in Local Storage and when the creen is refreshed it retains it's value entered

THEN the saved events persist
==>Unless changed the entries will appear on the following day and continue to appear
