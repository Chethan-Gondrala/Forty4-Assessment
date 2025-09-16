# User Dashboard (React)

A small User Dashboard app built with **Create React App**, plain CSS, and **React Context** for global state.  
It fetches users from `jsonplaceholder.typicode.com`, allows searching by name, adding new users (client-side), and viewing full user details with React Router.

---

## ✨ Features
- Fetch & display user list (name, email, phone, company)
- Search/filter users by name
- Create New User form (client-side only, stored in Context)
- User Details page (shows address + geo location)
- Responsive design using plain CSS (Flexbox/Grid)
- Global state management with React Context

---

## 🛠 Tech Stack
- React (Create React App, hooks: useEffect, useState, useContext)
- React Router DOM (routing)
- React Context (state management)
- Fetch API (data fetching)
- Plain CSS (responsive with Flexbox/Grid)

---

## 📂 Folder Structure
frontend/
├─ public/
│ └─ index.html
├─ src/
│ ├─ components/
│ │ ├─ Dashboard.js
│ │ ├─ Dashboard.css
│ │ ├─ UserDetails.js
│ │ └─ UserDetails.css
│ ├─ context/
│ │ └─ UserContext.js
│ ├─ App.js
│ ├─ index.js
│ ├─ index.css
│ └─ App.css
├─ package.json
└─ README.md

2. Install dependencies
npm install

3. Run the app
npm start


Runs at http://localhost:3000/
.

4. Build for production
npm run build

🧩 Development Steps (What I did)

Project Setup

Bootstrapped with Create React App.

Cleaned starter files.

Routing

Added react-router-dom.

Routes:

/ → Dashboard

/user/:id → User Details

Global State (React Context)

UserContext.js:

Fetch users from API.

Store users in state.

Expose users + addUser() globally.

Dashboard

Displays user cards (name, email, phone, company).

Search bar filters by name.

New User Form → Adds to Context.

User Details

Uses useParams() to get id.

Displays full details (address, geo).

Handles invalid user ID gracefully.

Styling

Plain CSS (Flexbox + responsive breakpoints).

Cards grid on desktop, stacked on mobile.


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/fa2198a6-2b30-4cf6-8413-1b7c147adf58" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/410bab5b-08eb-496c-b7f5-a06215d117ce" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b03a1b51-329e-4bc1-b4ba-8fe2062e7614" />



