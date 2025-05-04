# Food Trucks App
## Project Overview

This project is a Flask application integrated with Elasticsearch to manage and display data about food trucks. The goal is to provide users with an easy-to-use interface to search for food trucks using fast and scalable Elasticsearch.

## Features
- Search food trucks by keywords.
- Display food truck data using Flask and Elasticsearch.
- Dockerized Flask app with Elasticsearch for isolated environment setup.

## Changes and Updates

1. **Added Required Packages:**
   - Two additional packages have been added to the `requirements.txt` file:
     - `Jinja2==3.0.3` for templating.
     - `Werkzeug==2.0.3` for HTTP utility functions.

2. **Flask Version Update:**
   - The Flask version has been updated to the latest stable version to ensure compatibility with new features and security patches.

3. **Dockerization:**
   - A **Dockerfile** has been added inside the Flask app directory to containerize the Flask application.
   - A **docker-compose.yml** file has been added at the project root to manage the Flask app and Elasticsearch containers.



### Steps to Run the Project:

1. **Build the Docker containers:**
   To build the Flask app and Elasticsearch containers, run the following command in the project root directory:

--    docker-compose build

2. **Start the Docker containers:**

--    docker-compose Up 

3. **Logging and Debugging**

docker-compose logs -f flask-app


