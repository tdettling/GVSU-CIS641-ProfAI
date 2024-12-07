# Prof AI
ProfAI is a web application that utilizes generative AI to create curated dynamic content for faculty at Grand Valley State University. ProfAI will first request faculty members to generate a realistic avatar of themselves. After an avatar has been created, the proposed application will then generate a script based on the faculty member's topic of choosing. Upon receiving approval of the script from the faculty member, the web application will then generate a video of the avatar speaking the approved script, alongside a slideshow in a downloadable 2-5 minute video. Faculty members may then upload the video in whichever way they would like to deploy to students. After the initial launch of the project, IT Innovation and Research will conduct student interviews with the students that have seen the video of their faculty member to determine the value and authenticity of the content.


## Team Members and Roles


* L Dettling (Product Manager, Backend Developer)


## Prerequisites
Please note, the source code for this project is currently private as requested by GVSU IT Innovation and Research.


You first need to install Django and React locally onto your machine.

Django (Python Backend):
`pip install django djangorestframework django-cors-headers python-pptx psycopg2 requests djangorestframework-simplejwt`


React (JavaScript Frontend)
`npm install react react-router-dom axios bootstrap jwt-decode`


## Run Instructions
Please note, the source code for this project is currently private as requested by GVSU IT Innovation and Research.


This MVP application is meant to be a working prototype for review. As such, the application does not have a live, valid domain. The project is currently self hosted.


To start your backend server, navigate to the backend directory.
Next, run the following command, which will start the server side of this application.
`python manage.py runserver`

Now, please navigate to the frontend of this application.
Next, please run the following command, which will launch the client side server for this application.
`npm run dev`


After running these commands, the project will be hosted on a local server. 


