# Notes-API

REST API for Notes

This is a simple REST API built with Flask to manage notes. It allows you to:

- Create, read, update, and delete notes
- Uses SQLite as the database
- Documentation via Swagger (using FastAPI, if preferred)

## Setup

1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Initialize the database: 
   python
   from app import db
   db.create_all()
   
4. Run the application: `python app.py`

## Endpoints

- `GET /notes` - Retrieve all notes
- `POST /notes` - Create a new note
- `GET /notes/{id}` - Retrieve a specific note
- `PUT /notes/{id}` - Update a note
- `DELETE /notes/{id}` - Delete a note
