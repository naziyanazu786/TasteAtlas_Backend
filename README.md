Recipe Sharing Backend

This is a Node.js backend for a recipe-sharing application. It provides user authentication using Express.js and MongoDB, with secure password hashing using bcryptjs.

🚀 Features

User Authentication

User Registration (/register)

User Login (/login)

Home Page API

Returns a welcome message.

Secure Password Handling

Passwords are hashed using bcryptjs.

MongoDB Database Connection

Connection URL stored in .env file.

JWT Authentication (Planned for future implementation)

📂 Project Structure

📦 recipe-sharing-backend
├── 📄 .env                # Environment variables (MongoDB URL)
├── 📄 .gitattributes      # Configures LF normalization for Git
├── 📄 User.js            # Mongoose User model (username, email, password)
├── 📄 package.json       # Project dependencies and scripts
├── 📄 server.js          # Main server setup (Express, MongoDB connection, routes)
└── 📄 bcrypt.ps1         # PowerShell script for bcryptjs

🛠️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/your-repo.git
cd recipe-sharing-backend

2️⃣ Install dependencies

npm install

3️⃣ Configure Environment Variables

Create a .env file and add your MongoDB connection string:

MONGO_URI=your-mongodb-connection-url
PORT=5000

4️⃣ Start the server

npm start

📌 API Endpoints

Method

Endpoint

Description

GET

/

Home page response

POST

/register

User registration

POST

/login

User login

🏗️ Technologies Used

Node.js

Express.js

MongoDB (via Mongoose)

bcryptjs (for password hashing)

dotenv (for environment variables)

cors (for handling CORS)

jsonwebtoken (for future authentication needs)

📌 Future Enhancements

Add JWT-based authentication

Implement user profile management

Add recipe CRUD operations

📜 License

This project is open-source and available under the MIT License.

