# Django-Practise

Here are basic projects that I've made in the process of learning Django. I'll be uploading more into the repo as I progress.
## Environment Setup:
  To use same version of tools as were used during development please setup your virtual environment with the settings in requirements.txt to make sure things don't break with a different version.
  - $ pip install -r requirements.txt    
   
## STEPS to run for each project:
  - clone the repository in your local device
  - Head towards the particular project folder
  - navigate to the folder containing manage.py for that project
  - $ python manage.py runserver
  - navigate to localhost:8000
  (some projects' entry app may be in different routes, see more in project description below)
  
## Project 1: Airlines project
Description: It is a simple app that helps keep records of passengers in a particular flight. It shows info of a single flight like it's flight route, names of passengers and time. Also it lists all the plane routes that are assigned to a single passenger. The frontend is trash.
  - navigate to localhost:8000/flights to find the actual app

![airlines](./images/airlines_1.jpg)

## Project 2: Real Estate Listing

  Description: It is a real estate property listing site which has following features:
  
    - List all the properties with their images on the landing page
    - Add new entry to the listing
    - View details for each listing
    - Edit details for each listing
    - Delete listing
  -Steps to run: Clone locally and runserver

## Project 3: Book Shelf (Option to upload image left...)
  Description: It is a website to list books. With this application one can create/retrieve/update/delete the existing books in the shelf.

  - steps to run: Clone locally and runserver through the venv as specified in requirements.txt
