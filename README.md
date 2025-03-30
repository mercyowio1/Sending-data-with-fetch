# Sending-data-with-fetch## 🛠 Features
✔️ Sends a POST request to http://localhost:3000/users using fetch()
✔️ Handles server responses and appends the newly created user ID to the DOM
✔️ Implements error handling and displays error messages on the DOM if the request fails
✔️ Returns the fetch() promise to allow further chaining

## 📂 Project Structure
📁 fetch-post-request
│── 📄 index.html   # Basic HTML file to test fetch()
│── 📄 index.js     # JavaScript logic for fetch() POST request
│── 📄 db.json      # JSON server file to store users
│── 📄 README.md    # Project documentation

## 🔥 Function Explanation
submitData(name, email)
This function sends a POST request to http://localhost:3000/users with the provided name and email.
It:
✅ Sends a request with headers (Content-Type and Accept set to application/json)
✅ Converts the request body into JSON format
✅ Handles the response using .then() to extract the new user ID
✅ Appends the ID to the DOM
✅ Handles errors using .catch() and displays error messages on the DOM
✅ Returns the fetch() chain to allow additional chaining

## 🛠 Technologies Used
HTML

JavaScript (ES6)

Fetch API

JSON Server
