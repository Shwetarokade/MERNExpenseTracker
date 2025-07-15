# MERN Expense Tracker

A full-stack Expense Tracker application built with MongoDB, Express.js, React.js, and Node.js.

## Features
- User authentication (signup, login)
- Add, edit, and delete expenses
- View expenses in a table and detailed view
- Responsive and user-friendly UI

## Tech Stack
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/Shwetarokade/MERNExpenseTracker.git
cd MERNExpenseTracker
2. Backend setup
bash
Copy
Edit
cd backend
npm install
npm start
3. Frontend setup
bash
Copy
Edit
cd ../frontend
npm install
npm start
4. Environment Variables
Create .env files inside both backend and frontend directories and add necessary environment variables (like database URI, JWT secret, etc.).

Example .env for backend:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
Example .env for frontend (if needed):

ini
Copy
Edit
REACT_APP_API_URL=http://localhost:5000
How to Use
Register or login to your account.

Add new expenses with details like amount, category, and description.

Edit or delete existing expenses.

View all expenses in a structured table.

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License.
