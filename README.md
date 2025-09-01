Flask & SQL_Lite
To Do List App

Backend: Flask (Python)

Database: SQLite (via SQLAlchemy ORM)

Frontend: HTML, CSS (Jinja2 templates + custom styles)


Virtual Environment Structure
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

Make sure to do this in a virtual environment to keep it portable. Also use absolute paths.

