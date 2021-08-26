## Blog Website

### Author: MARY KAMAU
### Description
This application enables individual to read different blogs written by different people. Also one can register as the writed and will be posting blogs As a user of the web application you will be able to:

 1.View posted blogs
 2.Comment on posted blog
 3.Subscribe for notifications
As the writer, you will be able to

 1.Register and sign in to the application
 2.Post a blog
 3.Delete insulting comments
### Setup and installations
 .Clone Project to your machine
 .Activate a virtual environment on terminal: source       virtual/bin/activate
 .Install all the requirements found in requirements file.
 .On your terminal run python3.8 manage.py runserver
 .Access the live site using the local host provided
## Getting started
## Prerequisites
python3.8
virtual environment
pip
## Clone the Repo and rename it to suit your needs.
git clone https://github.com/marykamau2/Blog
Initialize git and add the remote repository
git init
git remote add origin <your-repository-url>
## Create and activate the virtual environment
python3.8-venv virtual
source virtual/bin/activate
### Install dependancies
Install dependancies that will create an environment for the app to run pip install -r requirements.txt

### Make and run migrations
python3.6 manage.py check
python manage.py makemigrations news
python3.6 manage.py sqlmigrate news 0001
python3.6 manage.py migrate
Run the app
python3.6 manage.py runserver
Open localhost:5000

### Testing the Application
python3.8 manager.py tests

## Built With
Python3.8
Flask
Boostrap
HTML
CSS
### Licence
This project is under the MIT licence