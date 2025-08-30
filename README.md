# 🌐 SpotWise  
*Hyper-local service connection within 5km radius*  


![SpotWise Banner](https://img.shields.io/badge/SpotWise-Experimental-orange?style=for-the-badge&logo=vercel&logoColor=white)  
![Node.js](https://img.shields.io/badge/Node.js-v16.x-green?style=for-the-badge&logo=node.js&logoColor=white)  
![Express.js](https://img.shields.io/badge/Express.js-v4.17.x-lightgrey?style=for-the-badge&logo=express&logoColor=black)  
![MongoDB](https://img.shields.io/badge/MongoDB-v5.0-brightgreen?style=for-the-badge&logo=mongodb&logoColor=white)  
![Mongoose](https://img.shields.io/badge/Mongoose-v6.x-red?style=for-the-badge&logo=mongoose&logoColor=white)  
![JWT](https://img.shields.io/badge/JWT-v8.5.x-blueviolet?style=for-the-badge&logo=jsonwebtokens&logoColor=white)    
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-blueviolet?style=for-the-badge&logo=bootstrap&logoColor=white)  
![HTML5](https://img.shields.io/badge/HTML5-Frontend-orange?style=for-the-badge&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-Frontend-blue?style=for-the-badge&logo=css3&logoColor=white)  
![MongoDB Atlas](https://img.shields.io/badge/Database-MongoDB%20Atlas-green?style=for-the-badge&logo=mongodb&logoColor=white)  
  

---

## 🚀 Overview  
**SpotWise** is an innovative, location-based web platform designed to seamlessly connect **service seekers** with **local service providers** (plumbers, electricians, carpenters, etc.) within a **5km radius**.  

By prioritizing **hyper-local interactions**, SpotWise ensures:  
✔️ Faster response times  
✔️ Higher service quality  
✔️ Secure and scalable architecture  

---

## ✨ Key Features  

- 📍 **5km Radius Matching**  
  Google Maps API + MongoDB Geospatial Indexing for accurate, efficient provider matching.  

- 🔐 **Secure Authentication**  
  Role-based access using **JWT tokens** (24hr expiry) with **TLS 1.3** for all API calls.  

- ⚡ **Real-Time Alerts**  
  WebSockets for instant provider notifications (with HTTP polling fallback).  

- 🔑 **PIN-based Verification**  
  Auto-generated **6-digit PIN** (SHA-256 hashed) for service completion & fraud prevention.  

- 📱 **Cross-Platform Responsive UI**  
  Built with **Bootstrap 5**, adapts across smartphones, tablets, and desktops.  

- 📊 **Service History & Analytics**  
  - Seekers: Past requests + provider ratings  
  - Providers: Completed jobs, earnings, and customer feedback  

---

## 🛠️ Technology Stack  

**Backend**  
- Framework: **Node.js (v16.x)** + **Express.js (v4.17.x)**  
- Database: **MongoDB (v5.0)** with geospatial support via **Mongoose ODM (v6.x)**  
- Authentication: **JWT** via `jsonwebtoken (v8.5.x)`  

**Frontend**  
- HTML5 + CSS3 (with media queries)  
- **Bootstrap 5** for responsive UI  
- **Google Maps JS API (v3.52)** for geolocation  

**Deployment**  
- Backend: **Vercel**  
- Database: **MongoDB Atlas**  
- Frontend: **GitHub Pages**  

---

## ⚙️ Installation & Setup  

```bash
# Clone the repository
git clone https://github.com/dhanushkumarms/spotwise.git
cd spotwise

# Backend setup
cd backend
npm install
npm start   # Runs on http://localhost:5000

# Frontend setup
cd frontend
npm install
npm run dev # Runs on http://localhost:30001
```
## 🤝 Contributing  

Contributions are welcome!  

1. Fork the repo  
2. Create a feature branch (`git checkout -b feature-name`)  
3. Commit changes (`git commit -m "Add new feature"`)  
4. Push & create a PR  

---

## 👥 Contributors  

- [Dhanushkumar](https://github.com/dhanushkumarms)  
- [Jeyanth](https://github.com/Jeyanth2005)  
- [Jothiswarar](https://github.com/jothiswarar)  
- [Santhosh G](https://github.com/ITZsanthosh369)  

---
---

⚡ *SpotWise – Bridging the gap between local services & seekers, one connection at a time.*  

