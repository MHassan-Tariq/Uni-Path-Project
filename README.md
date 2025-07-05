# 🎓 UniPath – Virtual University Recommendation System

**UniPath** is a smart, responsive web platform that helps students find the most suitable universities based on their academic scores. Users can enter their **Matric**, **FSC**, and **Entry Test** marks, and the system will recommend universities where they are most likely to get admission.

---

## 🔍 Project Overview

- 📘 **Purpose:** Help students make informed university choices based on their academic profile
- 💡 **Frontend:** React, Tailwind CSS, React Hook Form
- 🔐 **Backend (optional):** Firebase / Express.js
- 💾 **Database (optional):** Firestore / PostgreSQL
- ⚙️ **Role Support:** Student, Admin (for future scope)

---

## 🚀 Features

- 🧠 Merit-based university recommendations
- 📊 Smart merit calculation (Matric, FSC, Entry Test)
- 📝 Simple form with validation using React Hook Form
- 🎯 Role-based redirection (User → Home, Admin → Dashboard)
- 🌐 Fully responsive design using Tailwind CSS
- 💾 Optional: Backend for storing recommendations and user logins
- 🛡️ Error handling and feedback

---

## 🖼️ Screenshots

<!-- You can replace these links with real images -->
![Home Page]
(<img width="959" alt="1" src="https://github.com/user-attachments/assets/38982f1f-db8b-4ac3-9c20-e5f2bc617e2f" />)
![Recommendation Page]
(<img width="956" alt="2" src="https://github.com/user-attachments/assets/ffc30a3a-fa51-4fc8-881d-5e19b8602afd" />)

---

## 🧮 Merit Formula (Example)

```text
Merit = (Matric Marks * 10%) + (FSC Marks * 40%) + (Entry Test Marks * 50%)


📁 Project Structure

/src
 ┣ /components       # UI components (Navbar, Form, Card, etc.)
 ┣ /pages            # FormPage, ResultPage, AdminPage
 ┣ /utils            # Calculation logic, constants
 ┣ App.jsx           # Main routes
 ┗ index.js          # Entry point



🛠️ Getting Started
Prerequisites
Node.js

npm or yarn

Install & Run
git clone https://github.com/your-username/unipath.git
cd unipath
npm install
npm run dev


✍️ Example Input
Field	Value
Matric Marks	950 / 1100
FSC Marks	870 / 1100
Entry Test Marks	125 / 200

Output: Recommended universities based on calculated merit.



🔐 Future Features
🎓 University admin panel for setting cutoff criteria

📄 User registration/login (Firebase Auth)

📊 Analytics dashboard

📍 Location-based recommendations


🙋‍♂️ Author
Hassan Tariq
GitHub
LinkedIn


📄 License
MIT License
