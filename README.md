# Capstone 2 Project
## InspectMap - NYC Restaurant Health Violation Viewer
## Demo - ![DemoSite](https://adamant-vase.surge.sh/)

This project is my second capstone for the software engineering program on Springboard. The idea is to create a website in which user can browse NYC restaurants health violation painlessly.


The project will consist of:

1 external API:
  - NYC OpenData for violation data

1 map external library:
  - React Leaflet

NodeJS/Express backend, PostgreSQL for database.
Frontend using React and Formik.



The user flow consists of:

-User can drag the magnifier icon on map to locate surrounding restaurants. 
Marker are color coded according to their Health Grades.
Clicking Marker will display general info about that restaurant.
Clicking Detail will display all the violations restarurant had made in the past.

![Search by Dragging](https://media.giphy.com/media/LGO7RtPTgNuZUf5apQ/giphy.gif)

-User can register / Login and access more features.
As of this moment logging in will gain access to the search bar.

![User login](https://media.giphy.com/media/HMNedp1SMbtTOv724R/giphy.gif)

-Logged In user can search with full name of restaurant or partial. Borough must be specify.
Any restaurant matching search query would pop up.

![Search](https://media.giphy.com/media/fEe3mh691phBIKQWzm/giphy.gif)




