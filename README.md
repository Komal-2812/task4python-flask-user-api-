**task4python-flask-user-api-**

🧠 User Management REST API using Flask

✅ Objective
A simple REST API built with Flask for managing user data using in-memory storage (Python dictionary). 
Tested using Postman.

🔧 Tech Stack
- Python
- Flask
- Postman (for testing)

📌 Features
- `GET /` → API health check
- `GET /users` → Get all users
- `GET /users/<user_id>` → Get user by ID
- `POST /users` → Add new user
- `PUT /users/<user_id>` → Update user
- `DELETE /users/<user_id>` → Delete user

🔄 Sample JSON Body for POST/PUT 

{
  "id": "1",
  "name": "Komal Suthar",
  "email": "komal@example.com"
}

📸 Testing

All endpoints were tested using Postman with proper headers:

Content-Type: application/json

📁 How to Run

pip install flask

python app.py

