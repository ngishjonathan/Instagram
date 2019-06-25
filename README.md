## Instagram-Clone-
Intagram-Clone- is a app where users can post pics, comment, like and follow their friends.

By
Andrew Mwangi
## User stories
The user should be able to:

 Sign in to the application to start using.
 Upload my pictures to the application.
 See my profile with all my pictures.
 Follow other users and see their pictures on my timeline.
 Like a picture and leave a comment on it.

## Prerequisites
 Python3.6

## Features In Instagram-Clone-
 search functionality based on user profile
 Image models for uploading a user status
 Create and display photos,like comment and share

## Installation
To install, follow the following instructions;

    $ git clone https://github.com/ngishjonathan/Instagram-Clone-.git
    $ Navigate to the root folder using terminal.. //cd Instagram-Clone-
    $ Create a virtual and activate it.
    Install all the necessary requirements by running pip install -r requirements.txt (Python 3.6).
    $ ./manager.py runserver

## How to Prepare enviroment variables
Create a .env file in the root folder and add the following variables

    SECRET_KEY= #secure your app with a tight hash secret key
    DEBUG= #set to false in production.True in development
    DB_NAME= #database name
    DB_USER= #database user
    DB_PASSWORD=#database password
    DB_HOST="127.0.0.1"
    MODE= # dev or prod , set to prod during production
    ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'

## Known Bugs
Full functionalability not met. i.e users can not follow each other.

## Technology used
Python3.6.7
Django 1.11
Heroku
Bootstrap

## License (MIT License)
This project is licensed under the MIT Open Source license, (c) Andrew mwangi