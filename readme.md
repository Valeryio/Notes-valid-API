# Notes API

A simple REST API for managing notes, developed with Express and using a JSON file as a database.

## Installation

1. Clone this repository:
   ```sh
   git clone <repo-url>
   cd <repo-name>
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

## Usage

1. Start the server:
   ```sh
   node app.js
   ```
2. The API will run on `http://localhost:3000` by default.

## Project Structure

- `controllers/` : Handles business logic
- `routes/` : Defines API routes
- `middleware/` : Contains Express middlewares
- `services/` : Manages note operations
- `data/` : Stores the JSON file containing notes
- `app.js` : Entry point of the application

## Available Routes

- `GET /notes` : Retrieve all notes
- `POST /notes` : Add a new note
- `PUT /notes/:id` : Update a note
- `DELETE /notes/:id` : Delete a note

## Technologies Used

- Node.js
- Express.js
- JSON for storage

## Author

Linson DMT

---