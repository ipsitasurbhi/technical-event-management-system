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

## 📸 Screenshots

### 🔐 Login Page
<img width="1919" height="868" alt="Screenshot 2026-04-23 015934" src="https://github.com/user-attachments/assets/0966dbb1-e428-4380-a797-1e1c4439840e" />
-
<img width="1919" height="867" alt="Screenshot 2026-04-23 015948" src="https://github.com/user-attachments/assets/c747aeee-625b-4c4b-a284-c4dd072c65e5" />

### 👤 User Dashboard
<img width="1919" height="867" alt="Screenshot 2026-04-23 015958" src="https://github.com/user-attachments/assets/0fd7859c-3d91-495d-8b21-cc5e33109dc0" />

### Vendor Category Selection 
<img width="1919" height="864" alt="Screenshot 2026-04-23 020008" src="https://github.com/user-attachments/assets/c1ee9cb6-979e-442a-b97a-8dc072ac0a2d" />

### Products 
<img width="1919" height="863" alt="Screenshot 2026-04-23 020017" src="https://github.com/user-attachments/assets/8f5ba822-13a3-4681-b01b-59620f3774ae" />

<img width="1919" height="869" alt="Screenshot 2026-04-23 020041" src="https://github.com/user-attachments/assets/0b47cfe6-6679-4089-a0a9-158461788e68" />

<img width="1913" height="957" alt="Screenshot 2026-04-23 020048" src="https://github.com/user-attachments/assets/afca3cdc-3306-4fa9-8fba-8a28f1a189ce" />

<img width="1919" height="866" alt="Screenshot 2026-04-23 020112" src="https://github.com/user-attachments/assets/986e49e8-c5a2-4e9f-a6c4-f7aeaa7d809d" />

<img width="1919" height="869" alt="Screenshot 2026-04-23 020127" src="https://github.com/user-attachments/assets/111078fe-7cd6-4cea-aa8b-72e9551501b5" />

### Guest List - Update and Delete
<img width="1919" height="864" alt="Screenshot 2026-04-23 020200" src="https://github.com/user-attachments/assets/fabc07e6-4744-4d00-bbb5-91d314abebee" />

### Cart
<img width="1919" height="867" alt="Screenshot 2026-04-23 020210" src="https://github.com/user-attachments/assets/04687651-3d50-4d25-80d6-903bc7af81b3" />

### Checkout
<img width="1919" height="868" alt="Screenshot 2026-04-23 020216" src="https://github.com/user-attachments/assets/34bb222e-2b06-424e-b34e-8bca00518cdb" />

<img width="1919" height="860" alt="Screenshot 2026-04-23 020239" src="https://github.com/user-attachments/assets/d963f49f-8ecb-45fa-b5a5-f55df65e6751" />

### Order Status
<img width="1919" height="875" alt="Screenshot 2026-04-23 020246" src="https://github.com/user-attachments/assets/67f1d404-7ec3-4cb4-943e-f5fbd6206903" />

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
```
technical-event-management/
│
├── client/ # Frontend (HTML, CSS, JS)
├── server/ # Backend (Node.js, Express)
├── .env # Environment variables (not uploaded)
├── package.json
```
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
