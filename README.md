# Business-Hours-Scheduling-Calendar

Calendar for scheduling events during 9-5 business hours.

Title: Business-Hours-Scheduling-Calendar

Introduction: The goal of this refractor was to create a grid-layout calendar which was to be displayed in the browser window. The user could enter events for given time by hour thoughout the day, while being able to tell what slots were still left in the day based on color and local storage displayed.

Technologies: HTML, JavaScript, JQuery, Moment, Bootstrap, CSS

Launch: The page is launched on it's own. The user can interact and change events for time slots. To 'launch' a save, the 'Save" button in column 3 must be selected for the associated time slot to be saved.

Scope of Functionalities: The calendar displays operating hours from 9AM to 5PM. Ther user can ineract with the website by clicking within a given text area of a given hour, inputing the schedule for that hour, and then clicking to save this data into local storage. The calendar is also dynamic in that it changes color based on the current time. If a time slot textarea has already passed during the giving day, then the background color for the row is grey. If the current time is before a given time slot row, that time slot textarea with show up green. The row that falls within the current time will be displayed green. Upon refresh of page, calendar textarea entries are loaded from local storage and place into their time slots, if applicable.

Problems Faced: Initially started this with dynamic variables, but switched to JQuery for ease of use.

Potential Future Plans: The calendar could be accessible from outside sources, such as email, and be programmed to automatically update your calendar based on accepted events.

Table of Contens: The code follows this structure:

Head
Body
Script

Additional Notes: The final author of this is Joey davidson. He can be reached at j.davidson18@gmail.com
