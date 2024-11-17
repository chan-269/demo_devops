docker-course-three-tier-web-app
A 3-Tier web app using Docker, Compose and Flask.

Docker Course
This is a 3-tier web app built in Python (Flask). There are three layers to this application; namely:

**API Layer
**Frontend Layer
**Database - MySQL Layer
We then use Docker Compose to run all of the containers at once.

How to run these containers (using Docker Compose)
Make sure you have Docker Desktop running

Run the $docker compose build      #command to build the containers
Run the $docker compose up -d       #command to run the containers all at once
Open "localhost:5001/api/quotes" to see all the pre-populated sample quotes in a JSON format (assuming this is the first time you are running this).
On another browser, navigate to "localhost:5002" to see the frontend layer - you can add a few quotes as well as seeing other quotes coming from the database.
