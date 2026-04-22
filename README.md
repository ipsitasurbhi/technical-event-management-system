# Technical Event Management System
A full-stack Event Management System with role-based access for Admin, Vendor, and User, enabling event service management, product browsing, cart system, and order tracking.

---

## 🚀 Features

### 👤 User
- Register & Login  
- Browse vendors by category (Catering, Florist, Decoration, Lighting)  
- View products  
- Add to cart  
- Checkout  
- View order status  
- Manage guest list  

---

### 🏪 Vendor
- Login  
- Add / manage products  
- View product status  
- Handle user requests  

---

### 🛠️ Admin
- Login  
- Manage users & vendors  
- Add / update memberships  
- Access reports and transactions  

---

## 🧱 Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas  
- **Version Control:** Git & GitHub  

---

## 📁 Project Structure
technical-event-management/
│
├── client/ # Frontend (HTML, CSS, JS)
├── server/ # Backend (Node.js, Express)
├── .env # Environment variables (not uploaded)
├── package.json

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/ipsitasurbhi/technical-event-management-system.git
cd technical-event-management-system
```
### Install dependencies
```bash
cd server
npm install
```

### Setup environment variables
Create a .env file inside server/:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

### Run backend
```bash
node app.js
```

### Run frontend
Open client/index.html using Live Server.

### Highlights
Role-based authentication
Category-based product filtering
Cart & checkout system
Order status tracking
Clean UI flow based on assignment

---

### Author
Ipsita Surbhi
