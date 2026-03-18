# 🏡 WanderNest – Travel & Stay Booking Platform


**WanderNest** is a full-stack web application.                                              

That lets users **explore destinations, book accommodations**, and **share reviews — powered with AI-driven search, cloud media uploads**, and interactive maps. Built using **Node.js, Express.js, MongoDB**, and enhanced with **cloud image storage, social login, map integration**, and **secure authentication systems**.



---
## 🚀 Live Demo

🔗 Live Website: https://wandernest.onrender.com  
🔗 GitHub Repository: https://github.com/Tanu882/WonderNest/tree/main


---

## 📸 Screenshots

<table align="center">

  <tr>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 1</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20181245.png" width="400"><br><br>
      <i>All Listings</i>
    </td>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 2</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20185421.png" width="400"><br><br>
      <i>Searching Filter</i>
    </td>
  </tr>

  <tr>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 3</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20182054.png" width="400"><br><br>
      <i>Signup Page</i>
    </td>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 4</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20190649.png" width="400"><br><br>
      <i>Login Page</i>
    </td>
  </tr>

  <tr>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 5</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20190714.png" width="400"><br><br>
      <i>List Your Property</i>
    </td>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 6</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20182341.png" width="400"><br><br>
      <i>Upload Property Image</i>
    </td>
  </tr>

  <tr>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 7</b><br><br>
      <img src="https://github.com/Tanu882/WonderNest/blob/main/Screenshot%202026-03-18%20181320.png" width="400"><br><br>
      <i>Property Details</i>
    </td>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 8</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20200255.png" width="400"><br><br>
      <i>More About Property</i>
    </td>
  </tr>

  <tr>
    <td align="center" style="border:1px solid #ccc; padding:10px;">
      <b>Screenshot 9</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20182549.png" width="400"><br><br>
      <i>Calander UI</i>
    </td>
    <td align="center" style="border:1px solid #ccc; padding:10px;">
      <b>Screenshot 10</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20200331.png" width="400"><br><br>
      <i>Add Review</i>
    </td>
  </tr>

  <tr>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 11</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20190608.png" width="400"><br><br>
      <i>Wish List</i>
    </td>
    <td align="center" style="border:1px solid #ccc; padding:12px;">
      <b>Screenshot 12</b><br><br>
      <img src="https://raw.githubusercontent.com/Tanu882/WonderNest/main/Screenshot%202026-03-18%20182737.png" width="400"><br><br>
      <i>Map and Footer Section</i>
    </td>
  </tr>

</table>

---

## 🎯 Project Overview

WonderNest is a comprehensive property listing and booking platform designed to deliver a seamless user experience. It supports property discovery, user account management, reviews, and location-based interactions. The application integrates multiple authentication methods, secure session handling, cloud-based image storage, and dynamically rendered interfaces to ensure performance, scalability, and usability.

-----
## 🚀 Key Features

- 🔐 **Auth** – Signup, login, sessions, protected routes  
- 🏠 **Listings** – Create, edit, delete, view properties  
- 🖼️ **Images** – Multer + Cloudinary uploads  
- 🗺️ **Maps** – Mapbox location integration  
- ⭐ **Reviews** – Add/delete reviews & ratings  
- 👤 **Users** – Profile & listing management  
- 🌐 **Social Login** – Google + email/password  
- 🤖 **AI Search** – Gemini API + NLP  
- 🔒 **Security** – Hashing, validation, cookies  
- 📱 **Responsive** – Works on all devices  
---

## 🛠 Tech Stack

| Layer | Technology Used |
|------|----------------|
| **Frontend** | HTML, CSS, Bootstrap, JavaScript, EJS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB with Mongoose |
| **Authentication** | Passport.js, Express Session |
| **Image Management** | Cloudinary, Multer |
| **Maps & Location** | Mapbox API |
| **AI Search** | Google Gemini API, Natural.js |
| **Deployment** | Render |
| **Version Control** | Git & GitHub |

---
## 📁 Detailed Project Structure

```
WanderNest
│
├── models
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── routes
│   ├── listing.js
│   ├── review.js
│   └── user.js
│
├── controllers
│   ├── listings.js
│   ├── reviews.js
│   └── users.js
│
├── views
│   ├── listings
│   ├── reviews
│   ├── layouts
│   └── partials
│
├── public
│   ├── css
│   ├── js
│   └── images
│
├── middleware
├── utils
│
├── app.js
└── package.json
```

---
## 👤 User Workflow

Signup → Login → Browse Listings → View Details → Add Listing → Manage Listings → Leave Reviews → View Map → Logout


- 📝 **Signup/Login** – Create account or log in  
- 🔍 **Browse** – Explore available listings  
- 📄 **Details** – View property info, images & location  
- ➕ **Add Listing** – Create new property with images  
- ✏️ **Manage Listings** – Edit or delete your listings  
- ⭐ **Reviews** – Add ratings & feedback  
- 🗺️ **Map View** – See property location  
- 🚪 **Logout** – Securely exit account  
--- 

## 📦 Installation Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/nahida-athanikar/WanderNest.git
cd WanderNest
```
### 2️⃣Install Dependencies
```bash
npm install
```

### 3️⃣ Add Environment Variables
Create a .env file:
```bash
# Cloudinary Configuration
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

# Mapbox Configuration
MAPBOX_TOKEN=your_mapbox_access_token

# Gemini AI Configuration
GEMINI_API_KEY=your_gemini_api_key

# Session Secret
SESSION_SECRET=your_session_secret
```

```bash
Replace the values with your specific configurations.

```

### 4️⃣ Start the Server
```bash
npm start
```

### 5️⃣ Open App in Browser
Open http://localhost:8080/listings in your web browser.


---

## 👤 Author

<p align="center">
  <a href="https://www.linkedin.com/in/tanu-yadav-693a1a261/">
    <img src="https://img.shields.io/badge/LinkedIn-Tanu%20Yadav-blue?style=for-the-badge&logo=linkedin">
  </a>
  <a href="https://github.com/Tanu882">
    <img src="https://img.shields.io/badge/GitHub-Tanu882-black?style=for-the-badge&logo=github">
  </a>
  <a href="mailto:your-email@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail">
  </a>
</p>
