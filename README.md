# Contact-Management-API

This project sets up a RESTful API to manage contacts. It allows performing CRUD (Create, Read, Update, Delete) operations on a contact list.

Installation
To run this project locally, follow these steps:

Clone the repository.
Install dependencies using npm install.
Usage
Running the Server
Start the server using:

bash
Copy code
npm start
The server will be running at http://localhost:3000.

API Endpoints
GET /api/contacts: Retrieves all contacts.
GET /api/contacts/:id: Retrieves a specific contact by ID.
POST /api/contacts: Adds a new contact.
PUT /api/contacts/:id: Updates a specific contact by ID.
DELETE /api/contacts/:id: Deletes a specific contact by ID.
Example Usage
GET all contacts: GET http://localhost:3000/api/contacts
GET contact by ID: GET http://localhost:3000/api/contacts/:id
POST a new contact: POST http://localhost:3000/api/contacts
PUT update contact by ID: PUT http://localhost:3000/api/contacts/:id
DELETE contact by ID: DELETE http://localhost:3000/api/contacts/:id
Contact Object Structure
A contact object consists of the following properties:

id: Unique identifier for the contact.
name: Contact's name.
email: Contact's email address.
phone: Contact's phone number.
Dependencies
Express: Fast, unopinionated, minimalist web framework for Node.js.
Morgan: HTTP request logger middleware for Node.js.
Cors: Middleware for enabling CORS (Cross-Origin Resource Sharing) in Express.
API Structure
The API is structured to handle various HTTP methods on the /api/contacts endpoint. Each method corresponds to a specific action on the contact list.

Contact Functions
listContacts: Retrieves all contacts.
addContact: Adds a new contact to the list.
getContactById: Retrieves a specific contact by ID.
removeContactById: Removes a contact by ID.
updateContactById: Updates a contact by ID.
Contributing
Feel free to contribute by opening issues or creating pull requests.
