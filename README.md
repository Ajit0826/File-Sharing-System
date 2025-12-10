# 🚀 File Sharing System

A secure and scalable **File Sharing System** built using **Node.js, Express, and MongoDB**, designed to allow users to upload, share, and download files with ease.  
This project demonstrates backend architecture, API development, cloud storage logic (optional), and a clean UI workflow ideal for learning full-stack development.

---

## 📌 Features

### 🔐 **Secure File Uploads**
- Upload any file type (PDF, images, ZIP, videos, etc.)
- Prevents malicious files through backend validation
- Files stored with unique identifiers for safe access

### 🔗 **Shareable Download Links**
- Each uploaded file generates a unique download URL  
- Links can be shared easily with others

### 📥 **Fast Downloads**
- Optimized streaming for downloading large files
- Efficient memory handling

### 📊 **Upload & Download Tracking**
- Logs file uploads and download events  
- Helps understand user activity patterns

### 🗄️ **Database Integration**
- Uses **MongoDB** to store:
  - File metadata
  - Download count
  - Timestamps

### 🌐 **REST API**
- Clean & easy-to-extend REST API structure
- Supports future integration with frontend frameworks

---

## 🛠️ Tech Stack

| Layer           | Technology Used     |
|----------------|----------------------|
| Backend        | Node.js, Express.js |
| Database       | MongoDB / Mongoose |
| File Handling  | Multer (middleware) |
| Environment    | dotenv              |
| Hosting (future)| Render / AWS / Vercel |

---

## 📁 Project Folder Structure
File-Sharing-System/
│
├── controllers/
│   └── fileController.js        # Handles upload + download logic
│
├── models/
│   └── fileModel.js             # Mongoose schema for file metadata
│
├── routes/
│   └── fileRoutes.js            # API endpoints for upload/download
│
├── uploads/                     # Stores uploaded files (auto-generated)
│   └── <uploaded-files>
│
├── .env                         # Environment variables (PORT, MONGO_URI)
├── .gitignore                   # Ignore node_modules, uploads, etc.
├── package.json                 # Project metadata + dependencies
├── package-lock.json
├── server.js                    # Main server entry file
└── README.md                    # Project documentation


