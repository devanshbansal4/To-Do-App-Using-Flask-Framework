To Do List App

## Features
Add new tasks
View all tasks in a table
Update existing tasks
Delete tasks
SQLite database (instance/test.db)
Basic styling via static/css/main.css
Templates built using Jinja2 (base.html, index.html, update.html)


## Project Structure
.
├── app.py                 # Main Flask app
├── static/
│   └── css/
│       └── main.css       # Stylesheet
├── templates/
│   ├── base.html          # Base template
│   ├── index.html         # Home page (list + add tasks)
│   └── update.html        # Update page
├── test.db                # SQLite database (created automatically)
└── README.md              # Project documentation



## Installation & Setup ##

## Create and activate a virtual environment.
Install dependencies:
pip install flask flask_sqlalchemy

## Run the application:
python app.py
Access the app at:
http://127.0.0.1:5000/


## Tech Stack
Python
Flask
Flask-SQLAlchemy
SQLite


## License
This project is open-sourced under the MIT License.
