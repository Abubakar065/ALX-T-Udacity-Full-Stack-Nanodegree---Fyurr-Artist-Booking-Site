# ALX-T-Udacity-Full-Stack-Nanodegree---Fyurr-Artist-Booking-Site

Introduction/Background
Fyyur is a musical venue and artist booking site that facilitates the discovery and bookings of shows between local performing artists and venues. This site lets you list new artists and venues, discover them, and list shows with artists as a venue owner.

The app is able to do the following operations:

1) creating new venues, artists, and creating new shows.
2) searching for venues and artists.
3) learning more about a specific artist or venue.

SQLAlchemy ORM to be our ORM library of choice
PostgreSQL as our database of choice
Python3 and Flask as our server language and server framework
Flask-Migrate for creating and running schema migrations
HTML, CSS, and Javascript for our website's frontend

Overall:

1) Models are located in the MODELS section of app.py.
2) Controllers are also located in app.py.
3) he web frontend is located in templates/, which builds static assets deployed to the web server at static/.
4) Web forms for creating data are located in form.py

Development Server Setup
First of all, install Flask.

$ cd ~
$ sudo pip3 install Flask
To start and run the local development server,

Initialize and activate a virtualenv:
$ cd PROJECT DIRECTORY PATH/
$ virtualenv --no-site-packages env
$ source env/bin/activate

Install the dependencies:
$ pip install -r requirements.txt

Run the development server:
$ export FLASK_APP=myapp
$ export FLASK_ENV=development # enables debug mode
$ python3 app.py

Navigate to Home page http://localhost:5000

Regards>>>Abubakar Lawan
