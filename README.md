# FlaskSAP
Sap Interview

## Task:

Create a basic Flask web application:
- Root / is not important :)
- /<int:number> will display integers from 1 to that number
- /<int:number>/odd will display only odd numbers in that range
- /<int:number>/even will display only even numbers in that range
- /<int:number>/prime will display only prime numbers in that range

## Usage:

Use Python 3 and virtual environments.

To run docker:
- $ sudo docker run --name flasksap -p 5001:5001 flasksap

If Flask is not install:
Run:
- $ python3 -m venv venv
- $ . venv/bin/activate
- $ pip install Flask

Testing
- $ export FLASK_APP=hello.py
- $ flask run

If that does not work try:
- $ export FLASK_APP=hello.py
- $ export FLASK_ENV=development
- $ python -m flask run


