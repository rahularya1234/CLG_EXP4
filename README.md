User Signup and Management API
This project is a simple web-based API built using Node.js and Express.js to handle user signups and manage registered users. It stores user data (name, username, email, and password) in a local JSON file.

Features
User Signup: Allows users to sign up via a POST request, storing their data in a JSON file.
Fetch Registered Users: Fetches a list of all registered users through a GET request.
File Storage: All user data is saved in users.json.
Technologies Used
Node.js: Backend server runtime.
Express.js: Web framework for handling routes and requests.
File System (fs): Used for reading/writing user data to the JSON file.
CORS: Middleware for enabling cross-origin resource sharing.
HTML/CSS: Frontend form and basic styling.
JavaScript (Fetch API): For submitting form data and making requests from the frontend.
Project Structure
bash
Copy code
/db
    └── users.json      # Stores user data
/public
    └── index.html      # Frontend signup form
index.js                # Main server file
package.json            # Project metadata and dependencies
Installation
To get this project running locally, follow the steps below:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/repository-name.git
Navigate to the project directory:

bash
Copy code
cd repository-name
Install dependencies:

bash
Copy code
npm install
Usage
Start the server:

Run the following command to start the Node.js server:

bash
Copy code
npm start
The server will start on the default port (e.g., http://localhost:3000).

Access the frontend:

Open index.html located in the public directory in your browser to access the signup form.

API Endpoints
POST /api/signup

Description: Accepts user data (name, username, email, password) and stores it in users.json.

Example Request:

bash
Copy code
POST /api/signup
Content-Type: application/json
{
   "name": "John Doe",
   "username": "john_doe",
   "email": "john@example.com",
   "password": "password123"
}
GET /api/users

Description: Fetches and returns a list of all registered users.

Example Request:

bash
Copy code
GET /api/users
Contributing
If you wish to contribute to this project, feel free to submit a pull request or open an issue for any suggestions or bug fixes.
