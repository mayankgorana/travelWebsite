# 🌍 Travel Website

A dynamic and interactive travel booking website built using **Node.js**, **Express.js**, **PostgreSQL**, **EJS**, and **GSAP**. This project features dynamic package rendering, newsletter integration via Mailchimp API, and beautiful animations using GSAP.

<img width="1919" height="968" alt="image" src="https://github.com/user-attachments/assets/836b492d-7b9e-47e2-be9f-1344e07ec647" />
 <!-- Replace with your actual screenshot path -->
<img width="1919" height="966" alt="image" src="https://github.com/user-attachments/assets/c5b67727-fe9c-436a-af04-6330b4304b21" />
<img width="1916" height="969" alt="image" src="https://github.com/user-attachments/assets/6754247e-0503-493e-8089-49af5f680b5a" />
<img width="1919" height="968" alt="image" src="https://github.com/user-attachments/assets/0c74d46b-9e29-49aa-a5da-a5b72d5dbccc" />

---

## 🚀 Features

- 🌐 Responsive travel website with dynamic content
- ✨ Smooth animations using GSAP
- 📦 Travel package data from PostgreSQL
- 📧 Newsletter subscription using Mailchimp API
- ⚠ Toast alerts for actions and feedback
- 📝 Contact form with validation
- 📄 EJS templating for reusable frontend components

---

## 🔧 Tech Stack

| Frontend            | Backend                | Database     | APIs & Tools        |
|---------------------|------------------------|--------------|---------------------|
| HTML, CSS, JavaScript | Node.js, Express.js     | PostgreSQL   | Mailchimp API       |
| EJS Templating      |                        |              | Toast Alerts (JS)   |
| GSAP Animations     |                        |              |                     |

---

### 1. Clone the repo
git clone https://github.com/mayankgorana/travelWebsite.git
cd travelWebsite

### 2. Install dependencies
npm install

### 3. Create a .env file
PORT=3000
DATABASE_URL=your_postgres_connection_string
MAILCHIMP_API_KEY=your_mailchimp_api_key
MAILCHIMP_LIST_ID=your_list_id
MAILCHIMP_SERVER_PREFIX=your_dc_prefix

### 4. Run the project
node app.js

***Navigate to http://localhost:3000 in your browser.***

### ✉️ Mailchimp Integration
The website allows users to subscribe to a newsletter using the Mailchimp API. Upon submission, user data is sent and handled with a secure POST request and proper feedback via toast alerts.

### 💡 Toast Alerts
Feedback for user actions (like form submissions and entering email in the newletter section) are shown using simple JavaScript-based toast notifications.
