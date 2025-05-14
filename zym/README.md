# 🛍️ Shopper — E-commerce Platform

![MERN Stack](https://img.shields.io/badge/Stack-MERN-61DAFB)
![License](https://img.shields.io/badge/License-MIT-green)

Shopper is a fully functional e-commerce platform built using React.js, Node.js, Express, and MongoDB. It handles user registration, authentication, product management, filtering, and cart functionality with support for both guest and logged-in users.

## � Features

### 🔐 Authentication & Security
- User Authentication with JWT
- Password hashing with bcrypt
- Role-based route access (admin vs user)
- Environment variables for sensitive config

### 🛒 Shopping Experience
- Product listing with filters (color, size, price, category)
- Cart system for both guests & logged-in users
- Order placement and checkout logic (extendable)
- Sorting options (price, popularity)

### 🖥️ Admin Features
- Admin route protection
- MongoDB database with Mongoose models
- RESTful API structure

## 📸 Screenshots

| Page | Preview |
|------|---------|
| **Landing Page** | ![image](https://github.com/user-attachments/assets/d22c8504-4182-4a62-81a5-581613242b0f) |
| **Collections** | ![image](https://github.com/user-attachments/assets/9dae9241-5bbd-4e2b-a376-4cd5f9b806c8) |
| **Product View** | ![image](https://github.com/user-attachments/assets/30fd9a5f-8cea-4f9d-8770-d8455ba9b8ba) |
| **Admin Panel** | ![image](https://github.com/user-attachments/assets/cf8c5db8-bc24-4a12-8ba8-20538fc8f8c7) |

## 🚀 Getting Started
Function: Executing the npm run dev command will start the project's development server. This server will compile the project code and monitor changes to project files. Once a file is modified, the server will automatically update the page to display the latest effects. After startup, you can visit http://localhost:5173 in your browser to view and use the SimpleTodo to-do list manager. This process sets up a local development and usage environment for you, facilitating operations such as function testing, development, and debugging.

Verify the project startup
After opening http://localhost:5173 in your browser, if you can see the main interface of SimpleTodo with operation buttons for adding, editing, and deleting tasks, it means the project has been successfully launched. If you encounter any problems during startup, you can check the error messages in the terminal to locate the issue. Here are some common issues and solutions:

Blank page or error: This may be due to incomplete dependency installation or syntax errors in the code. You can try deleting the node_modules directory and then re-executing npm install to install the dependencies.
Port is occupied: If the project cannot be accessed normally at http://localhost:5173 and the prompt indicates that the port is occupied, you can modify the dev script configuration in package.json to specify another available port.
After the modification, re-execute npm run dev.

Start using the project
Once the project is successfully launched and opened in the browser, you can immediately start using the SimpleTodo to-do list manager. On the main interface, you can click the corresponding buttons to add new tasks. Enter the specific content of the task in the input box and press the confirmation key to add the task to the list. For completed tasks, simply click the check box in front of the task, and the task will be marked as completed. If a task is no longer needed, you can remove it from the list by clicking the delete button. All task data will be automatically saved in the browser's LocalStorage, which means that even if you close the browser and reopen it, the previously added, edited, and deleted task data will still be retained. Moreover, thanks to the responsive interface design, you can have a good user experience whether you access the project on your phone, tablet, or PC.
### Prerequisites
- Node.js (v14+)
- MongoDB (local or Atlas)
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/shopper.git

# Install dependencies
cd shopper
npm install
cd client
npm install
Configuration
Create a .env file in the root directory:

env
MONGO_URI=mongodb://localhost:27017/shopper
JWT_SECRET=your_jwt_secret_here
PORT=5000
Running the Application
bash
# Start backend server (from root directory)
npm start

# Start frontend (from client directory)
cd client
npm start
🛡️ Security Features
Password Protection: bcrypt hashing

Secure Authentication: JWT tokens

Access Control: Admin/user role separation

Safe Configuration: Environment variables

📌 Future Improvements
Payment gateway integration

Product review system

Order history & shipping tracking

Advanced analytics dashboard

👨‍💻 Author
Aakash Pawar
GitHub Profile | Portfolio | Contact