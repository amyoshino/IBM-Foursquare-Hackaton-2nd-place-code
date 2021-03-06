# Cognitive Builder Faire Hackaton - 2nd Place project code

### This is the code submitted on IBM/Foursquare hackaton on Cognitive Builders Faire (may/12 - may/14, 2017)

The project is a web application that get two (or more) address and Foursquare users and return reccomendations of restaurants or bars based on the preferences, previous check-ins and comments of users. The reccomendations are located around the midpoint between the addresses to make it easy and convenient to everybody get at the location.

![](Application.png)

The code is divided in two parts:
- Web app that accept addresses and users and export a JSON file that is read by the python code;
- Python code read JSON file with users information, calculate midpoint between addresses, explore places around midpoint and choose among those points the top 5 places to reccomend to users based on their check-ins, comments, semantic analysis of their comments and the general comments of places.

Here is the workflow of the project:

![](Workflow.png)

The presentation is on: https://docs.google.com/presentation/d/1L7cVrcKWZM9n89gYR4jicc-czYcIfTIgMEhFC0X9LpE/edit?usp=sharing

Team members:
- https://github.com/KT12
- https://github.com/TryHarder01
- https://github.com/QuanAVuong
- https://github.com/amyoshino

And, this is the picture of the team + instructors and organizers of the hackaton.

![](team.JPG)
