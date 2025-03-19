![Blogging Frontend](https://img.shields.io/badge/Blogging%20Frontend-ReactVite,%20TailwindCSS,%20JavaScript-blue?style=for-the-badge&logo=react)

# 🚀 Blogging Website Frontend

```ascii
  ____  _              _      _     _                     _     _            
 |  _ \| | ___   ___  | |    (_)___| |_   ___  __ _  __ _| |__ | | ___  ___  
 | |_) | |/ _ \ / _ \ | |    | / __| __| / __|/ _` |/ _` | '_ \| |/ _ \/ __| 
 |  __/| | (_) | (_) || |____| \__ \ |_  \__ \ (_| | (_| | |_) | |  __/\__ \ 
 |_|   |_|\___/ \___(_)______|_|___/\__| |___/\__,_|\__,_|_.__/|_|\___||___/
```

## 🌟 Features

- ⚡ **Fast & Lightweight** using Vite
- 🎨 **Modern UI** with Tailwind CSS
- 🔥 **Seamless Authentication** with Firebase
- 📄 **Rich Text Editor** for blogging
- 🌍 **Responsive Design** for all devices
- 📡 **API Integration** with blogging backend
- 🎭 **Dark Mode Support**
- 🛡️ **Protected Routes** with JWT Authentication

## 🏗️ Tech Stack

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=white)  
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=white)  
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=white)  

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/itz-Hiru/Blogging-Website-Frontend.git
cd blogging-frontend

# Install dependencies
npm install
```

## 🚀 Usage

```bash
# Start development server
npm run dev
```

## 📡 API Endpoints Used

| Method | Endpoint             | Description               |
|--------|---------------------|---------------------------|
| GET    | /api/posts          | Fetch all blog posts     |
| POST   | /api/posts          | Create a new post        |
| GET    | /api/posts/:id      | Get a single post by ID  |
| PUT    | /api/posts/:id      | Update a post           |
| DELETE | /api/posts/:id      | Delete a post           |
| POST   | /api/auth/login     | Authenticate user       |
| POST   | /api/auth/register  | Register new user       |

## 🔑 Environment Variables

Create a `.env` file in the root directory and add:

```ini
FIREBASE_API_KEY=your firebase api key
FIREBASE_AUTH_DOMAIN=your firebase auth domain
FIREBASE_PROJECT_ID=your firebase project id
FIREBASE_STORAGE_BUCKET=your firebase storage bucket
FIREBASE_MESSAGING_SENDER_ID=your firebase messaging sender id
FIREBASE_APP_ID=your firebase app id
```

## 🏗️ Folder Structure

```
/blogging-frontend
│── src/
│   ├── assets/
│   ├── common/
│   ├── components/
│   ├── pages/
│── public/
│── .env
│── package.json
│── vite.config.js
│── tailwind.config.js
│── README.md
│── LICENSE
```

## 🛡️ Security Practices

- ✅ **JWT Token Handling** for authentication
- ✅ **Input Validation** to prevent XSS attacks
- ✅ **Secure Storage** for user credentials
- ✅ **Strict CORS Policies**

## 📜 License

This project is licensed under the MIT License.

---
🚀 Happy Coding! 🎉
