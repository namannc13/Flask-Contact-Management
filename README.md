# Flask Contact Management

This is a simple Flask application for managing contacts. It demonstrates basic CRUD (Create, Read, Update, Delete) operations using SQLAlchemy for database management and Flask for building RESTful APIs.

## Features

- **View Contacts**: Retrieve a list of all contacts stored in the database.
- **Create Contact**: Add a new contact with a first name, last name, and email address.
- **Update Contact**: Update the details of an existing contact.
- **Delete Contact**: Remove a contact from the database.

## Technologies Used

- Flask: Micro web framework for building web applications in Python.
- SQLAlchemy: SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- Flask-SQLAlchemy: Flask extension for integrating SQLAlchemy with Flask applications.
- Flask-CORS: Flask extension for handling Cross-Origin Resource Sharing (CORS) to allow requests from other domains.

## Setup 

## Usage

- Use the provided RESTful endpoints to perform CRUD operations on contacts:
  - `GET /contacts`: Retrieve all contacts.
  - `POST /create_contact`: Create a new contact.
  - `PATCH /update_contact/<user_id>`: Update an existing contact.
  - `DELETE /delete_contact/<user_id>`: Delete a contact.

## Contributing

Contributions are welcome! If you find any bugs or want to add new features, feel free to submit a pull request.
