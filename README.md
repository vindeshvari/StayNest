# StayNest 🏡

A full-stack, Airbnb-inspired property rental platform enabling users to browse, list, review, and visually locate accommodations worldwide.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=flat&logo=render)](https://stay-nest-abm4.onrender.com)

---

## 🔗 Live Application

Access the live platform here:  
👉 **[https://stay-nest-abm4.onrender.com](https://stay-nest-abm4.onrender.com)**

---

## 🌟 Features

* **Property Management:** Full CRUD operations for hosting, editing, and managing rental property listings.
* **Interactive Maps:** Real-time geocoding and visual location mapping integrated via Mapbox.
* **Authentication & Authorization:** Secure user registration, login, and session persistence powered by Passport.js.
* **Cloud Storage:** High-performance media upload and image delivery managed through Cloudinary.
* **Reviews & Ratings:** Authenticated community reviews and rating systems per listing.
* **Server-Side Rendering:** Dynamic layout rendering using EJS templating.

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose)
* **Frontend / Templating:** EJS (Embedded JavaScript), HTML5, CSS3, JavaScript
* **Authentication:** Passport.js
* **External APIs & Services:** Cloudinary (Media Management), Mapbox API (Geocoding & Interactive Maps)
* **Deployment:** Render

---

## 📁 Project Structure

```text
StayNest/
├── controllers/       # Route request handling logic
├── models/            # Mongoose schemas (Listing, Review, User)
├── routes/            # Express route endpoints
├── views/             # EJS view templates and partials
├── public/            # Static assets (CSS, client JS, images)
├── utils/             # Express error handlers and middleware
├── app.js             # Main server entry point
├── package.json       # Project dependencies
└── README.md          # Project documentation
