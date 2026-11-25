# 🪑 SteelCraft — Premium Steel Furniture E-Commerce

[![Live Demo](https://img.shields.io/badge/Demo-Live_Website-22c55e?style=for-the-badge&logo=vercel&logoColor=white)](https://steelfurniture.vercel.app)
[![React](https://img.shields.io/badge/React-18-61dafb?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![Express](https://img.shields.io/badge/Express-5-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com)
[![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-47a248?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

A full-stack e-commerce web application for premium stainless steel furniture, featuring interactive product catalogs, real-time search, cart management, and order inquiry flows.

🔗 **Live Deployment:** [steelfurniture.vercel.app](https://steelfurniture.vercel.app)

---

## ✨ Features

- 🎬 **Cinematic Hero Section** — Full-width background showcase with dynamic headline rotations
- 🛍️ **Interactive Product Shop** — 24+ stainless steel products categorized across Swings, Doors, Railings, Furniture, and Decor
- 🔍 **Live Search & Filter** — Instant product searching with image previews and category filters
- 🛒 **Persistent Shopping Cart** — Add, remove, and manage item quantities with automatic `localStorage` synchronization
- 📦 **Product Inspection View** — Multi-angle image gallery, detailed technical specifications, and instant add-to-cart
- 📬 **Inquiry & Order System** — Backend API integration for placing orders and submitting custom design requests
- 📱 **Fully Responsive** — Optimized for mobile, tablet, and desktop viewports

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React 18, Vite 4, CSS Design Tokens |
| **Backend** | Node.js, Express 5, REST API |
| **Database** | MongoDB with Mongoose ODM |
| **Security & Utilities** | CORS, Dotenv |
| **Deployment** | Vercel |

---

## 📁 Project Structure

```
SteelCraft/
├── public/
│   └── images/              # Product imagery & video assets
├── src/
│   ├── App.jsx              # Main React application & views
│   ├── api.js               # Centralized Axios/fetch API helpers
│   ├── main.jsx             # React DOM root entry
│   └── styles.css           # Global design system & animations
├── models/
│   ├── Product.js           # Mongoose Product Schema
│   ├── Order.js             # Mongoose Order Schema
│   └── Message.js           # Contact & custom inquiry Schema
├── routes/
│   ├── products.js          # GET /api/products
│   ├── orders.js            # POST /api/orders
│   └── messages.js          # POST /api/messages
├── server.js                # Express server & API routes
├── vite.config.js           # Vite build configuration
├── .env.example             # Environment template
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/sahaniTripurari/Steel_Funiture_web.git
cd Steel_Funiture_web
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Setup Environment Variables
Copy `.env.example` to create your `.env` file:
```bash
cp .env.example .env
```
Inside `.env`:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
FRONTEND_URL=http://localhost:5173
```

### 4. Run the Development Server
- **Run Backend:**
  ```bash
  node server.js
  ```
- **Run Frontend (in a separate terminal):**
  ```bash
  npm run dev
  ```

> Frontend will run at: `http://localhost:5173`  
> Backend API will run at: `http://localhost:5000`

---

## 📦 API Reference

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/api/products` | Fetch full catalog with categories |
| `POST` | `/api/orders` | Place a customer order |
| `POST` | `/api/messages` | Submit a custom steel fabrication inquiry |

---

## 👨‍💻 Developer & Contact

**Sahani Tripurari** — Full-Stack Developer  
- **GitHub:** [@sahaniTripurari](https://github.com/sahaniTripurari)  
- **Email:** sahanitrirpurari@gmail.com  
- **Live Demo:** [SteelCraft Website](https://steelfurniture.vercel.app)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
