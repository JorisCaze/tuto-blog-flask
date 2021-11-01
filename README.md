# Blog tutorial with Flask

## Description 

This repo contains the code related to the Flask tutorial written by [Miguel Grinberg](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world). 

In this tutorial a basic blog platform is built with Flask. 

## Setup 

To install all required libraries it is recommended to use a python virtual environment:

    python3 -m venv venv
    
The newly created environment must be activated using:

    source ./venv/bin/activate

Dependencies can be installed:

    pip install -r requirements.txt

To run the app simply type:

    flask run

The web-app is available at http://127.0.0.1:5000/

By default, the app is set in debug mode, to change it the `FLASK_ENV` environment variable is directly defined into the `.flaskenv` file.