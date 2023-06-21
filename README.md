# This is a To-do application

# steps to setup:
python -m venv venv
.\venv\Scripts\activate
pip install Flask

# To run the application without app.run(debug=True)
export/set FLASK_APP=app.py
export/set FLASK_ENV=development
flask run

# Install SQL Alchemy
pip install Flask-SQLAlchemy

