# 🍽️ TASTY-TRACK: The Social Food Delivery Network

## 📖 Overview
**TASTY-TRACK** is an innovative online food ordering and delivery system designed to simplify and enhance the food-ordering experience. It provides a convenient web platform where customers can browse menus, customize orders, make secure payments, and track deliveries in real time. The system also streamlines restaurant order management and delivery coordination, offering efficiency, speed, and reliability.

Developed using **ReactJS, Node.js/Express, and MongoDB**, TASTY-TRACK ensures a smooth, interactive, and responsive user experience while maintaining security and scalability.

---

## ✨ Key Features
- 🔐 **User Registration & Authentication:** Secure login and signup for customers and restaurants.  
- 📜 **Menu Browsing:** View detailed restaurant menus with prices and images.  
- 🛒 **Order Placement & Customization:** Select and customize dishes easily.  
- 📦 **Real-Time Order Tracking:** Monitor your food preparation and delivery status live.  
- 💳 **Secure Payments:** Integrated and encrypted payment gateway for safe transactions.  
- 🍴 **Restaurant Management:** Manage menus, availability, and orders efficiently.  
- ⭐ **Customer Ratings & Reviews:** Share feedback and help others choose better.  
- 📱 **Responsive Design:** Built with Material UI and Bootstrap for a mobile-friendly interface.  

---

## 🧰 Tech Stack

| Layer | Technologies Used |
|:------|:------------------|
| **Frontend** | ReactJS, HTML5, CSS3, JavaScript, Material UI, Bootstrap |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Tools & IDEs** | VS Code, MongoDB Compass, Postman |
| **Testing Tools** | JUnit 4.0 |
| **Version Control** | Git & GitHub |

---

## ⚙️ System Requirements

### 🖥️ Hardware
- Processor: 32/64-bit, 2.5GHz or higher  
- RAM: 250MB minimum  
- Storage: 20GB or higher  

### 💽 Software
- OS: Windows / Linux / macOS  
- Browser: Chrome / Mozilla / Opera  
- Dependencies: Node.js, MongoDB  

---

## 📁 Project Structure

TASTY-TRACK/
│
├── backend/
│ ├── db/
│ │ └── connect.js
│ ├── routes/
│ │ ├── authRoutes.js
│ │ └── hotelRoutes.js
│ ├── middleware/
│ │ ├── not-found.js
│ │ └── error-handler.js
│ ├── server.js
│ └── .env
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── context/
│ │ └── assets/
│ ├── public/
│ └── package.json
│
└── README.md

yaml
Copy code

---

## 🧩 Modules

- 👤 **User Module:** Handles registration, login, and user profiles.  
- 🍽️ **Restaurant Module:** Manages menus, updates availability, and processes orders.  
- 🧾 **Order Module:** Handles order creation, tracking, and history.  
- 🚴 **Delivery Module:** Assigns deliveries and provides navigation.  
- 💳 **Payment Module:** Enables secure online transactions.  
- 🛠️ **Admin Module:** Oversees user, restaurant, and delivery data.  

---

## ⚙️ Installation & Setup

Follow these steps to set up the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/tasty-track.git
cd tasty-track
2️⃣ Install Dependencies
bash
Copy code
npm install
3️⃣ Setup Environment Variables
Create a .env file in the root directory and include:

env
Copy code
PORT=5000
MONGO_URL=mongodb://127.0.0.1:27017/tastytracker
JWT_SECRET=your_secret_key
JWT_LIFETIME=1d
4️⃣ Start the Backend Server
bash
Copy code
npm start
5️⃣ Run the Frontend
bash
Copy code
cd frontend
npm start
Once both servers are running, open http://localhost:3000 to access the application.

🧪 Testing
Backend APIs are tested using Postman.

Unit testing performed with JUnit 4.0.

UI testing for responsiveness and functionality validation.

🔒 Security
JWT-based user authentication

Encrypted password storage

Secure payment processing

Protected API routes

Data privacy compliance

🧠 Methodology
The development follows the Waterfall Model:

Requirement Analysis

System Design

Implementation

Testing

Deployment

Maintenance

🧾 Project Planning Highlights
Scope: Food ordering, menu management, and delivery tracking.

Stakeholders: Customers, Restaurants, Delivery Personnel, and Admins.

Risks Managed: Technical issues, resource allocation, and schedule delays.

Tools Used: VS Code, MongoDB Compass, Postman, Git.

💡 Future Enhancements
🤖 AI-based food recommendations

🔔 Push notifications for order status updates

🌐 Multi-language and regional support

🧭 Integration with third-party delivery APIs

💬 Live chat support

👩‍💻 Contributors
Project Team: Dept. of CSE, GPT Tumakuru (2022–23)

Developed Using: ReactJS, Node.js, MongoDB, Express, Material UI

Mentorship: Under the guidance of project coordinators and faculty advisors

🏁 Conclusion
TASTY-TRACK bridges the gap between customers, restaurants, and delivery personnel through a fast, reliable, and user-friendly digital platform.
It redefines food delivery with modern technology—offering convenience, transparency, and satisfaction for all stakeholders.
This project stands as a step towards digital transformation in the food service industry.



