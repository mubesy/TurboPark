# Turbo Park
 
## Inspiration
We were inspired to create this project by realizing the difficulty of finding parking at popular places and events, such as concerts, sports events, malls, and restaurants, etc.

## What it does
Our website allows the user to input an address and will show the nearest parking structures. The website also displays relevant details about each parking structure, such as its name and photo, how many parking spaces are available, and how likely you are to find an available parking spot.

## How we built it
For the frontend, we used Adobe XD, HTML/CSS, React.js, and Redux.
For the backend, we used Flask Python, INRIX's Off Street Parking API, and Position Stack's Geocoding API.

## Challenges we ran into
We struggled to find a free API for geocoding and how to extract the JSON data in Python. We ran into a lot of bugs when integrating the frontend with the backend such as the JSON data not being serialized. In addition, we wanted to make our code that calls the APIs run faster.

## Accomplishments that we're proud of
After hours of struggling, we got the UI to cooperate with the backend seamlessly.

## What we learned
We learned how to integrate APIs into our full-stack website and how to effectively problem solve issues related to collecting data using APIs.

## What's next for Turbo Park
We'd like to improve the UI and response time of our website's search function. We also like to add more features, such as allowing the user to change the radius parameter for the parking results.
