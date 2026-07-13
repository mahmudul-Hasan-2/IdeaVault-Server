# 🚀 IdeaVault Server

Welcome to the backend server of IdeaVault — a powerful and secure Crowdfunding Platform designed to turn innovative ideas into reality. This server handles authentication, campaign management, and database operations securely.

## 🛠️ Tech Stack & Dependencies

This server is built using the modern Node.js ecosystem with the following core technologies:

* **Runtime Environment:** Node.js
* **Framework:** Express.js (v5.x)
* **Database:** MongoDB (Official Driver v7.x)
* **Environment Management:** Dotenv
* **Cross-Origin Resource Sharing:** CORS

## 🚀 Features

* **RESTful API Architecture:** Clean and scalable route management.
* **Database Integration:** Seamless connection with MongoDB.
* **Environment Security:** Critical credentials and ports are managed securely via `.env`.
* **CORS Enabled:** Ready to communicate safely with your frontend application.
* **Development Workflow:** Configured with `nodemon` for hot-reloading during development.

---

## ⚙️ Getting Started

Follow these steps to set up and run the server locally on your machine:

### 1. Clone the Repository

```bash
git clone https://github.com/mahmudul-Hasan-2/IdeaVault-Server.git
cd IdeaVault-Server
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Environment Setup

Create a `.env` file in the root directory and define your port and database URI:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

### 4. Run the Server

```bash
nodemon index.js
```


## 🛣️ API Endpoints (Base URL: `http://localhost:5000`)

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/` | Server health check (Returns "Hello World!") |

*(More endpoints for crowdfunding campaigns and users will be added soon!)*

## 👨‍💻 Author

**Mahmudul Hasan Nirab**
* GitHub: [@mahmudul-Hasan-2](https://github.com/mahmudul-Hasan-2)

## 📄 License

This project is licensed under the **ISC License**.
