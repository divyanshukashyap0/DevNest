# 🎓 Project Marketplace Platform

A full-stack web application that allows students to **browse, purchase, and manage academic projects** based on their field of study.  
The platform integrates **secure payments, authentication, AI assistance, and a modern UI** to deliver a complete student-focused experience.

---

## 🚀 Features

### 🔐 Authentication & Authorization
- Student signup & login
- Secure JWT-based authentication
- Role-based access (Student / Admin)
- Google OAuth (optional)

### 💳 Payment Integration
- Secure payment gateway (Razorpay / Stripe)
- Order history & invoices
- Coupon & discount support

### 🛒 Project Marketplace
- Browse projects by:
  - Field (Web Dev, AI/ML, Data Science, etc.)
  - Difficulty (Beginner / Intermediate / Advanced)
  - Technology stack
- Project previews (screenshots, descriptions)
- Instant access after purchase

### 🤖 AI Project Assistant
- Explains project code
- Helps modify features
- Assists with viva & interview questions
- Available for paid users

### 📊 Student Dashboard
- Purchased projects
- Download source code & documentation
- Learning progress tracking

### 🌗 UI / UX
- Modern, responsive design
- Light & Dark theme toggle
- Smooth animations
- Mobile-friendly layout

### ⭐ Reviews & Ratings
- Verified user reviews
- Rating system for projects

---

## 🧑‍💻 Tech Stack

### Frontend
- React / Next.js
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB / PostgreSQL

### Authentication
- JWT
- OAuth (Google)

### Payments
- Razorpay / Stripe

### AI Integration
- OpenAI / Gemini API

### Deployment
- Frontend: Vercel
- Backend: Render / AWS

---

## 🤝 Contributors

This project is collaboratively developed by:

- **Harshit Tiwari**  
  Full Stack Developer  
  Focus: Backend, Database Design, Authentication, Payments, AI Integration

- **Divyanshu Kashyap**  
  Full Stack Developer  
  Focus: Frontend UI/UX, Responsive Design, Theme Toggle, User Experience

Both contributors actively participate in planning, development, testing, and feature improvements.

---

## 🤝 Contributing
Contributions are welcome!

1. Fork the repository  
2. Create a new branch (`feature/your-feature-name`)  
3. Commit your changes  
4. Open a Pull Request  

---

## 📬 Contact

For queries, feedback, or collaboration:

- **Harshit Tiwari**  
  Email: your-email@example.com  

- **Divyanshu Kashyap**  
  Email: divyanshu-email@example.com  


## 📁 Project Structure


project-marketplace/
│
├── frontend/                      # Client-side application
│   ├── public/                    # Static assets
│   │   └── favicon.ico
│   │
│   ├── src/
│   │   ├── assets/                # Images, icons, animations
│   │   ├── components/            # Reusable UI components
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── ProjectCard.jsx
│   │   │   └── ThemeToggle.jsx
│   │   │
│   │   ├── pages/                 # App pages (Next.js or React Router)
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── Signup.jsx
│   │   │   ├── Marketplace.jsx
│   │   │   ├── ProjectDetails.jsx
│   │   │   ├── Dashboard.jsx
│   │   │   └── Admin.jsx
│   │   │
│   │   ├── context/               # Auth & global state
│   │   │   └── AuthContext.jsx
│   │   │
│   │   ├── services/              # API calls (Axios)
│   │   │   ├── authService.js
│   │   │   ├── projectService.js
│   │   │   └── paymentService.js
│   │   │
│   │   ├── utils/                 # Helper functions
│   │   ├── styles/                # Tailwind & global styles
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   └── package.json
│
├── backend/                       # Server-side application
│   ├── src/
│   │   ├── config/                # DB, payment, OAuth configs
│   │   │   ├── db.js
│   │   │   ├── razorpay.js
│   │   │   └── oauth.js
│   │   │
│   │   ├── models/                # Database schemas
│   │   │   ├── User.js
│   │   │   ├── Project.js
│   │   │   ├── Order.js
│   │   │   └── Review.js
│   │   │
│   │   ├── routes/                # API routes
│   │   │   ├── auth.routes.js
│   │   │   ├── project.routes.js
│   │   │   ├── payment.routes.js
│   │   │   └── ai.routes.js
│   │   │
│   │   ├── controllers/           # Business logic
│   │   ├── middleware/            # JWT, role-based access
│   │   ├── services/              # AI, payment logic
│   │   ├── utils/                 # Helpers & validators
│   │   └── server.js
│   │
│   └── package.json
│
├── docs/                          # Documentation & guides
│   ├── API.md
│   ├── SETUP.md
│   └── DATABASE.md
│
├── .env.example                   # Environment variables template
├── .gitignore
├── README.md
└── LICENSE

