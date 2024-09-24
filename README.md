Signup Form Project


 Signup Form Project
Project Overview
This project is a simple user signup form using Node.js and Express.js for the backend, and a HTML form for the frontend. User data (name, username, email, password) is collected from the form and stored in a JSON file (users.json). The project also retrieves and displays the list of registered users.

Technologies Used
Node.js
Express.js
fs (File System)
CORS
HTML/CSS
JavaScript (Fetch API)

POST /api/signup
Handles user signup. Accepts user data and stores it in users.json.

GET /api/users
Fetches all registered users from users.json.


folder strucuter
/db
    users.json    
/public
    index.html    
index.js          
package.json     



Usage
Start the server using npm start.
Open index.html in a browser to access the signup form.
