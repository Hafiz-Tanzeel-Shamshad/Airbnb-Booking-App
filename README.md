<h1 align="center"> 🌍Airbnb Booking Web Applictaion (MERN + EJS)🌍 </h1>


 ## 🏡 Overview
This project is a **full-stack rental booking web application** inspired by **Airbnb**, built using the **MERN** stack (**MongoDB, Express.js, React.js, Node.js**) with **EJS** as the templating engine for server-side rendering. It provides a seamless experience for **browsing, listing, and managing rental properties** with robust **authentication, CRUD operations, a responsive design, interactive Mapbox maps, and user comments with ratings**. It is fully **deployment ready on Railway** — both frontend and backend deployed together.

---

## ✨ Key Features  

 ✅ **User Authentication:** Secure login & registration with Passport.js  
 ✅ **CRUD Operations:** Add, update, and delete rental listings  
 ✅ **EJS Templating:** SEO-friendly dynamic page rendering  
 ✅ **MongoDB Database**: Data storage and retrieval using MongoDB with Mongoose.  
 ✅ **Express.js Backend**: RESTful API endpoints for efficient data handling. <br/>
 ✅ **Bootstrap UI:** Clean, responsive, and mobile-friendly design.  
 ✅ **Session Management:** Secure user sessions with cookies.  
 ✅ **Error Handling:** Centralized error handling for better debugging.  
 ✅ **Interactive Maps:** Mapbox (third-party map service) integration to show listing locations.  
 ✅ **Comments & Ratings:** Users can comment on listings and give ratings.  
 ✅ **Deployment Ready:** Easily deployable on **Railway** — frontend and backend together.

---

## 🏗️ Tech Stack

### Frontend
- ![EJS](https://img.shields.io/badge/EJS-Embedded%20JavaScript-blue)
- ![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0-purple)
- ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
- ![Mapbox](https://img.shields.io/badge/Mapbox-Interactive%20Maps-black)

### Backend
- ![Node.js](https://img.shields.io/badge/Node.js-Server-6DA55F)
- ![Express.js](https://img.shields.io/badge/Express.js-Framework-blue)
- ![MongoDB](https://img.shields.io/badge/MongoDB-Mongoose-brightgreen)
- ![bcrypt](https://img.shields.io/badge/Bcrypt-Password%20Hashing-orange)
- ![Passport.js](https://img.shields.io/badge/Passport.js-Authentication%20Middleware-blue)
- ![dotenv](https://img.shields.io/badge/dotenv-Environment%20Variables-yellowgreen)

---

## 🛠️ Installation and Setup

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Hafiz-Tanzeel-Shamshad/Airbnb-Mern-Project.git
   cd mern-ejs-project
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   node app.js
   ```

4. **Open the application in your browser:**
   ```
   Visit: http://localhost:3000/listings
   ```

---

## 🚀 Deployment

This project is **deployment ready for Railway**. Both the **frontend** and **backend** are deployed together as a single Node.js application.

### 1. Push your code to GitHub:
   ```bash
   git push origin main
   ```

### 2. Create a new project on Railway:
- Go to [Railway.app](https://railway.app) and click **New Project** → **Deploy from GitHub repo**.
- Select your repository; Railway will auto-detect the Node.js build.

### 3. Configure environment variables:
- Add your `MONGODB_URL`, `SESSION_SECRET`, `MAP_TOKEN`, and `CLOUDINARY` keys in the Railway dashboard.

### 4. Deploy:
- Railway automatically builds and deploys both frontend and backend.
- Set the start command to `node app.js` in the service settings if it is not auto-detected.
- Your app will be live at the Railway-provided URL.

---

## 👨‍💻 Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork it and submit a pull request.

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a Pull Request.

---

## 📞 Contact

For any inquiries, feel free to reach out via:
- **Hafiz Tanzeel** - [LinkedIn](https://www.linkedin.com/in/hafiz-tanzeel-shamshad-8680a8309/)
- **Email**: [hafiztanzeel.pk@gmail.com](mailto:hafiztanzeel.pk@gmail.com)

---

## 📜 License

This project is licensed under the **MIT License**.
