# 🚖 Car Rental Website

Car Rental Website is a full-stack platform for renting cars online.  
Users can explore available vehicles, check availability, and book rentals, while admins can manage fleet, bookings, and users through a secure dashboard.

---

## 🚀 Features
- Browse cars with details and images  
- Flexible booking system with date selection  
- User authentication and profile management  
- Admin dashboard for car, booking, and user management  
- Responsive UI with fast performance  

---

## 🛠️ Tech Stack
- **Frontend:** React, Vite, Tailwind CSS, Axios  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB, Mongoose  
- **Authentication:** JWT, Bcrypt  
- **Media Management:** ImageKit, Multer  

---

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/PranayMittal00/CarRental.git
cd car-rental

# Install client dependencies
cd client && npm install

# Install server dependencies
cd ../server && npm install

# Run servers
cd server && npm run dev
cd client && npm run dev
```

---

## ⚙️ Environment Variables
Create a `.env` file in the `server` directory:

```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_endpoint
PORT=5000
```

Client `.env`:
```
VITE_API_BASE_URL=http://localhost:5000
```

---

