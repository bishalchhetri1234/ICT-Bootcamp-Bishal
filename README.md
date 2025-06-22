# ICT-Bootcamp
10 Days ICT Bootcamp


A simple web application with a contact form, signup/login system, and profile page using **HTML, JavaScript, and Express.js**.

---

## 🚀 Features

- Contact form with validation
- Signup and login with client-side validation
- User profile page using data from `localStorage`
- Express server to handle form submissions
- Modular JavaScript with ES Modules

---

## 📁 Folder Structure

```

project-root/
├── public/
│   ├── index.html
│   ├── signup.html
│   ├── login.html
│   ├── profile.html
│   ├── contact.html
│   ├── style.css
│   ├── contact.js
│   ├── signup.js
│   ├── login.js
│   ├── profile.js
│   └── helperFunctions.js
├── server.js
├── package.json
└── README.md

````

---

## 🛠️ Installation & Setup

1. **Clone the repository**


2. **Initialize Node project and install dependencies**

```bash
npm init -y
npm install express body-parser
npm install croc
```

3. **Start the server**

node server.js 
```

4. **Open the project**

Visit in your browser:

```
http://localhost:3000/index.html
```

---

## 📌 Notes

* All front-end files are served from the `public/` directory.
* `localStorage` is used to store user data after login.
* `croc` package is installed for future use but not required to run the project.

---
