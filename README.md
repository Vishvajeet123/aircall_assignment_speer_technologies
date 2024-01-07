deployement link --> https://659a49456270e65b5e275341--ubiquitous-cascaron-09bab0.netlify.app/

Speer_technologies assignment 


screenshot shot of my project --->

![{95DDF6A8-6EE4-45E7-9BE1-A917BC9D2C6A}](https://github.com/Vishvajeet123/aircall_assignment_speer_technologies/assets/109080799/2a0e32d0-8313-42ba-97a1-b317ba30dcc7)
![{8AC870A0-E14C-4AFB-8FCA-7CB511EA4CDF}](https://github.com/Vishvajeet123/aircall_assignment_speer_technologies/assets/109080799/8f57fc14-f1b8-4c7b-b117-81d648381d29)

Here is the API address: https://cerulean-marlin-wig.cyclic.app/
If you run into a CORS error, please prepend the base URL with this CORS Anywhere server URL: https://charming-bat-singlet.cyclic.app/
The prepended base URL will look like this https://charming-bat-singlet.cyclic.app/https://cerulean-marlin-wig.cyclic.app/

The API is hosted on a free server, which is why the first time you call the API, it will throw an error. The server goes to sleep if there hasn't been any activity for a while, but after 30-60 seconds of the first call, it should work as expected. Please reach out to us in case it doesn't.

GET - BASE_URL/activities: get calls to display in the Activity Feed
GET - BASE_URL/activities/<call_id> retrieve a specific call details
PATCH - BASE_URL/activities/<call_id> update a call. The only field updatable is is_archived (bool). You'll need to send a JSON in the request body:
