# 🌐 SpotWise  
*Hyper-local service connection within 5km radius*  

![SpotWise Banner](https://img.shields.io/badge/SpotWise-Experimental-orange?style=for-the-badge&logo=vercel&logoColor=white)      
![HTML5](https://img.shields.io/badge/HTML5-Frontend-orange?style=for-the-badge&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-Frontend-blue?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-blueviolet?style=for-the-badge&logo=bootstrap&logoColor=white)   
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript&logoColor=black)

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

**Frontend**  
- HTML5 + CSS3 (with media queries)  
- **Bootstrap 5** for responsive UI  
- **Google Maps JS API (v3.52)** for geolocation  


## ⚙️ Installation & Setup (Frontend Only)  

```bash
# Clone the repository
git clone https://github.com/dhanushkumarms/spotwise.git
cd spotwise

# Install dependencies
npm install

# Run frontend dev server
npm run dev   # Runs on http://localhost:3000
