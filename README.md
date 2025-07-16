# Sweet Shop Management

A modern, interactive web application to manage your sweet shop inventory, built with Node.js, Express, and a beautiful responsive frontend.

## Features
•⁠  ⁠Add, edit, delete, and search sweets
•⁠  ⁠Purchase and restock inventory
•⁠  ⁠Responsive, mobile-friendly UI with pastel theme
•⁠  ⁠Animated modals, toasts, and loading spinners
•⁠  ⁠Real-time feedback and error handling
•⁠  ⁠Persistent data storage with SQLite
•⁠  ⁠Simple RESTful API

## Tech Stack
•⁠  ⁠*Backend:* Node.js, Express, SQLite
•⁠  ⁠*Frontend:* Vanilla JS, HTML, CSS (no framework)
•⁠  ⁠*Testing:* Jest (for backend)

## Getting Started

### Prerequisites
•⁠  ⁠[Node.js](https://nodejs.org/) (v14 or higher recommended)
•⁠  ⁠npm (comes with Node.js)

### Installation
1.⁠ ⁠*Clone the repository:*
   ⁠ bash
   git clone <your-repo-url>
   cd <project-folder>
    ⁠
2.⁠ ⁠*Install dependencies:*
   ⁠ bash
   npm install
    ⁠
3.⁠ ⁠*Start the server:*
   ⁠ bash
   npm start
    ⁠
   The server will run on [http://localhost:3000](http://localhost:3000) by default.

4.⁠ ⁠*Open the app:*
   - Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Folder Structure

project/
├── controllers/         # Express route controllers
├── data/                # SQLite database file
├── models/              # Database and ORM models
├── public/              # Frontend (HTML, CSS, JS)
├── routes/              # Express route definitions
├── src/                 # (Optional) React starter files (not used)
├── tests/               # Jest tests for backend
├── server.js            # Main Express server
├── package.json         # Project metadata and scripts


## Usage
•⁠  ⁠*Add Sweet:* Click "Add Sweet" and fill out the form.
•⁠  ⁠*Edit/Delete:* Use the Edit/Delete buttons on each sweet.
•⁠  ⁠*Purchase/Restock:* Use the respective buttons to update stock.
•⁠  ⁠*Search/Filter:* Use the controls at the top to filter sweets by name, category, or price.
•⁠  ⁠*Mobile:* All features work on mobile devices.

## Running Tests
•⁠  ⁠To run backend tests:
  ⁠ bash
  npm test
   ⁠
•⁠  ⁠Tests are located in the ⁠ tests/ ⁠ directory.

## Credits
•⁠  ⁠UI inspired by modern sweet shop themes
•⁠  ⁠Built with ❤️ by your team

## License
This project is open source and free to use under the [MIT License](LICENSE).
