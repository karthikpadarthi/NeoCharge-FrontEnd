---
project: NeoCharge Frontend
type: EV Charging Marketplace
repository: NeoCharge-FrontEnd
author: Karthik Padarthi
tech_stack:
  - React.js
  - JavaScript (ES6+)
  - REST APIs(SpringBoot-Backend)
  - Vite / CRA
  - CSS / Tailwind / Material UI
status: Under Development
---

# ⚡ NeoCharge – Frontend

NeoCharge is a **modern EV charging marketplace** that allows users to **discover, view, and book electric vehicle charging stations** seamlessly.  
This repository contains the **frontend application** responsible for UI, user interaction, and backend API integration.

---

## 🎯 Product Goal

To provide a **clean, responsive, and intuitive user interface** that enables EV users to:
- Find nearby charging stations
- View real-time availability
- Book charging slots efficiently
- Track bookings and charging sessions

---

## 🚀 Features

### 🔍 Station Discovery
- Location-based charging station listing
- Charger details including type, price, and availability

### 📅 Booking Interface
- Time-slot selection
- Seamless booking flow
- Conflict prevention handled via backend APIs

### 👤 User Authentication
- Login & Signup screens
- Secure session handling

### 📊 User Dashboard
- View active bookings
- Booking history
- Charging session status

### 📱 Responsive UI
- Mobile-first design
- Optimized for desktop and tablet views

---

## 🛠 Tech Stack

| Layer        | Technology |
|-------------|------------|
| Frontend     | React.js |
| Language     | JavaScript (ES6+) |
| Styling      | CSS / Tailwind / Material UI |
| State Mgmt   | React Hooks / Context API |
| API Type     | REST |
| Build Tool   | Vite / CRA |

---
```text
## 📁 Project Structure


NeoCharge-FrontEnd/
│
├── src/
│   ├── components/        # Reusable UI components
│   ├── pages/             # Page-level components
│   ├── services/          # API calls and integrations
│   ├── utils/             # Utility/helper functions
│   ├── App.js             # Root component
│   └── main.js            # Application entry point
│
├── public/
├── .gitignore
├── package.json
└── README.md
```
setup:
  prerequisites:
    - Node.js
    - npm
  steps:
    - git clone https://github.com/karthikpadarthi/NeoCharge-FrontEnd.git
    - cd NeoCharge-FrontEnd
    - npm install
    - npm run dev
  local_url: http://localhost:5173

environment_variables:
  VITE_API_BASE_URL: http://localhost:8080

future_enhancements:
  - Map-based charging station visualization
  - Real-time availability using WebSockets
  - Payment gateway integration
  - Role-based dashboards (User, Station Owner, Admin)

contibution-steps:
  - Fork the repository
  - Create a feature branch
  - Commit changes with a meaningful message
  - Push changes and open a pull request

---
