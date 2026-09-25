🛒 MERN E-Commerce Website

A full-stack E-Commerce Website developed as the Major Project for the Skill Nexus MERN Full Stack Internship.

The project is built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) and provides a complete online shopping experience with product browsing, user authentication, cart management, and order-related functionality.

---

📌 Project Overview

This project is designed to demonstrate practical knowledge of MERN Stack development by creating a responsive and user-friendly e-commerce platform.

Users can browse products, view product details, add products to their cart, manage their cart, and place orders.

---

🚀 Features

👤 User Features

- User registration and login
- User authentication
- Browse products
- View product details
- Add products to cart
- Update cart quantity
- Remove products from cart
- Place orders
- View order details

🛍️ Product Features

- Product listing
- Product categories
- Product images
- Product price and description
- Product search/filter functionality

🎨 UI Features

- Responsive design
- Clean and user-friendly interface
- Navigation bar
- Product cards
- Shopping cart interface
- Responsive layout for different screen sizes

---

🛠️ Tech Stack

Frontend

- React.js
- JavaScript
- HTML5
- CSS3
- React Router
- Axios

Backend

- Node.js
- Express.js
- REST API

Database

- MongoDB
- Mongoose

Tools

- Git & GitHub
- VS Code
- npm

---

📂 Project Structure

MERN-E-Commerce/
│
├── client/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── assets/
│       ├── App.jsx
│       └── main.jsx
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── .gitignore
├── package.json
└── README.md

«The folder structure may vary depending on the final implementation of the project.»

---

⚙️ Installation & Setup

1. Clone the Repository

git clone https://github.com/your-username/your-repository-name.git

2. Navigate to the Project

cd your-repository-name

3. Install Frontend Dependencies

cd client
npm install

4. Install Backend Dependencies

cd ../server
npm install

5. Configure Environment Variables

Create a ".env" file inside the "server" folder.

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Do not upload your actual ".env" file or secret keys to GitHub.

---

▶️ Run the Project

Start Backend

cd server
npm start

Start Frontend

Open another terminal:

cd client
npm run dev

The application will then be available on the local development URL shown by Vite.

---

🔗 API

The backend provides REST APIs for operations such as:

- User authentication
- Products
- Cart
- Orders
- User management

Example:

GET    /api/products
POST   /api/users/login
POST   /api/users/register
GET    /api/orders

-

🔮 Future Enhancements

- Online payment integration
- Admin dashboard
- Product reviews and ratings
- Wishlist functionality
- Advanced product filtering
- Order tracking
- Email notifications
- Cloud deployment

---

🎓 Internship Project

Internship: Skill Nexus – MERN Full Stack Internship
Project: MERN E-Commerce Website
Project Type: Major Project
Technology: MERN Stack

This project was developed to gain practical experience in full-stack web development, REST APIs, database management, authentication, and frontend-backend integration.

---

👩‍💻 Author

Isha Yadav

B.Tech – Computer Science & Engineering (AI & ML)

GitHub: Isha240886

---

⭐ Acknowledgement

Thanks to Skill Nexis for providing the opportunity to work on this project and gain practical experience in MERN Stack development.

---

📄 License

This project is developed for educational and internship purposes.
