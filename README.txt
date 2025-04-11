CSI 2132 W-2025 (uOttawa) Project
Hotel Management System

Project made with flask and PostgreSQL

SQLAlchemy is used to send/receive db calls, but all db calls are made using queries (no ORMs, as per project rules)

Database is remotely hosted on neon db

CSS handled by bootstrap

Collaborators:

Kevin Zheng (front end & backend)

Sijun Liu (server & queries)




REQUIREMENTS

python3

* if 'pip install <...>' doesn't work, try 'pip3 install <...>'

psycopg2
    - pip install psycopg2

flask
    - pip install flask

sqlalchemy
    - pip install sqlalchemy

Flask-SQLAlchemy
    - pip install Flask-SQLAlchemy SQLAlchemy

requests
    - pip install requests

flask-wtf
    - pip install flask-wtf

Also need this below:
    - pip install email_validator 


*** The Github public version of this project uses python-dotenv


To run flask app:
    - Open terminal/cmd and go to directory
    - python3 app.py
    - Copy port number and paste onto web browser
