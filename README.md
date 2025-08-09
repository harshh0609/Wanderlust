# 🏡 Wanderlust

A full-stack **Airbnb Clone** built to sharpen my web development skills.  
This project replicates the core functionalities of Airbnb — including property listings, booking, user authentication, and more — while being completely custom-built from scratch.

---

## ✨ Features

- 🔐 **User Authentication** – Sign up, log in, and secure sessions
- 🏠 **Property Listings** – Browse, search, and filter stays
- 📅 **Booking System** – Reserve dates for your chosen property
- 📍 **Interactive Maps** – View locations with map integration
- 📷 **Image Uploads** – Add property images via file upload
- 📱 **Responsive Design** – Works smoothly on mobile and desktop
- ⚡ **Real-Time Updates** – See new listings instantly (if implemented)
- 🗄 **Database Integration** – Persistent data storage

---

## 🛠 Tech Stack

**Frontend**
- HTML, JAVASCRIPT, CSS
- Tailwind CSS / CSS Modules / Styled Components

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB (Mongoose ORM)

**Other Tools**
- Cloudinary / AWS S3 (for image storage)
- Mapbox / Google Maps API (for maps)
- JWT (for authentication)

---

## 📂 Folder Structure

```bash
airbnb-clone/
│
├── client/              # Frontend code
│   ├── public/           # Static files
│   ├── src/              # React components, pages, hooks
│   └── package.json
│
├── server/              # Backend code
│   ├── models/           # Mongoose models
│   ├── routes/           # Express routes
│   ├── controllers/      # Business logic
│   ├── utils/            # Helper functions
│   └── package.json
│
├── .env.example         # Example environment variables
├── README.md
└── package.json         # Root config
```

---

## 🚀 Getting Started
Follow these steps to run the project locally.

1️⃣ Clone the Repository
git clone https://github.com/your-username/airbnb-clone.git
cd wanderlust

2️⃣ Install Dependencies
npm install

3️⃣ Setup Environment Variables
Create a .env file in both client and server folders using .env.example as a reference.

4️⃣ Run the Application
node app.js

---

## 🏗 Future Improvements
🏷 Add categories & price filters

💳 Payment gateway integration

🌍 Multi-language support

📧 Email notifications

---

## 💡 Fun Fact:
This project was built purely for learning purposes — to practice full-stack development concepts, APIs, and deployment workflows.
