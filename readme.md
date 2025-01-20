# TravelSage Application

## 🚀 Overview
TravelSage is a full-stack travel planning application that helps users explore destinations, create itineraries, and manage their trips seamlessly. The backend uses Node.js, Express.js, and MongoDB, while the front end uses React.js.

## ✨ Features
- 🌍 **Explore Destinations** – Browse through various destinations with details.
- 📅 **Create Itineraries** – Plan trips and manage itineraries efficiently.
- 🗺️ **Interactive Maps** – View locations on an embedded map.
- 📌 **Bookmark Places** – Save favorite destinations for future reference.
- 🔍 **Search Functionality** – Quickly find destinations and trips.
- 🛠 **User Authentication** – Secure login/signup with JWT authentication.
- 📊 **Scalable Backend** – Built using RESTful API architecture with MongoDB.

## 🛠 Tech Stack
### **Frontend**
- React.js
- React Router
- Styled Components / Tailwind CSS

### **Backend**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Cloudinary (for image uploads)

### **Other Tools**
- Socket.io (for real-time updates)
- Google Maps API (for location data)
- Redis (for caching)
- Docker (for containerization)

## 📂 Project Structure
```
📦 TravelSage
├── 📂 client            # Frontend (React.js)
├── 📂 server            # Backend (Node.js, Express)
│   ├── 📂 models       # Mongoose Schemas
│   ├── 📂 routes       # Express Routes
│   ├── 📂 controllers  # Business Logic
│   ├── 📂 middleware   # Authentication & Error Handling
│   ├── 📂 config       # Environment Variables & Config Files
│   ├── index.js       # Entry Point
├── 📂 public            # Static Assets
├── 📜 .env.example      # Example Environment Variables
├── 📜 package.json      # Dependencies
└── 📜 README.md         # Project Documentation
```

## ⚡ Installation & Setup
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/nishantatras/TravelSage.git
cd TravelSage
```

### **2️⃣ Install Dependencies**
#### Backend:
```sh
cd server
npm install
```
#### Frontend:
```sh
cd client
npm install
```

### **3️⃣ Set Up Environment Variables**
Create a `.env` file in the `server` directory and add the required configurations.
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_API_KEY=your_cloudinary_api_key
```

### **4️⃣ Start the Application**
#### Start the backend server:
```sh
cd server
npm start
```
#### Start the frontend:
```sh
cd client
npm start
```

The app will be live at **`http://localhost:3000`**
## 🛡 Security & Performance Enhancements
- **Helmet.js** – Protects against common vulnerabilities.
- **Rate Limiting** – Prevents API abuse.
- **Caching with Redis** – Optimizes performance.
- **Docker** – For seamless deployment.

## 📜 API Endpoints
| Method | Endpoint        | Description                  |
|--------|----------------|------------------------------|
| GET    | `/api/v1/tours/` | Get all travel destinations |
| POST   | `/api/v1/tours/` | Create a new itinerary |
| GET    | `/api/v1/users` | Fetch user profile |

## 🤝 Contributing
Contributions are welcome! Feel free to **fork** this repository and submit a PR.

## 📧 Contact
- **Author:** Nishant Atras
- **Email:** your.email@example.com
- **GitHub:** [nishantatras](https://github.com/nishantatras)
