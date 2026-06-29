Day of Greatness — Weekly Planner
A minimal weekly planner that automatically displays public holidays and only shows the current week while letting you add and remove personal events 


How to Run:

Download both index.html and styles.css into the same folder
Open index.html in web browser


Data Source:

Holiday data is pulled from the Nager.Date Public Holidays API — a free, open rest API that returns public holidays by country and year.


AI Assistance Disclosure:

Local storage — Claude helped me write the logic to save and load events from localStorage so they persist between page refreshes
Timestamp keys — I was running into a bug where saving multiple events on the same day would overwrite each other. Claude helped me fix it by using Date.now() to make each event key unique
Holiday fetch response handling — Claude helped me with structuring the .then() chain after the API call so the data was indexed correctly before the grid rendered
