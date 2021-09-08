# Guessing-Game

A simple Number Guessing Game web application which provides the following functionality:  
• The Computer randomly selects a number between 1 and 10  
• The player can input a number between 1 and 10 as a guess  
• The game allows for 3 attempts before game over 
• Refresh button to restart the app (still has bugs)  

The project makes use of Python3, Flask, SQLite, HTML5, CSS, JavaScript Bootstrap and JQuery.

## Getting Started

git clone https://github.com/xavier-1-tech/Guessing-Game.git && cd guess_app

##### Create virtualenv and activate

pip install -r requirements.txt

Linux & Mac:
export FLASK_APP=app.py  
flask run  #flask run --host=0.0.0.0 (if require server to be publicly accessible)  

Windows:
set FLASK_APP=app.py
flask run  #flask run --host=0.0.0.0 (if require server to be publicly accessible) 

Navigate to: http://localhost:5000/

##### The code

First we must import the modules that we will be working with in flask:
```python
import random

from flask import Flask, render_template, request

application = app = Flask(__name__)
```

## Authors

**Xavier Henry**

## License

This project is licensed under the MIT License
