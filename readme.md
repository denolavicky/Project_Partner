# MentorPath MERN STACK APPLICATION

> **Connecting African students and graduates with verified professionals who guide them to their dream career — step by step.**

MentorPath is a full-stack mentor-mentee platform built for students and fresh graduates who feel lost about their career path. It's not just a "find a mentor" tool — it's a **career GPS** that gives users the exact skills, steps, timeline, and human guidance they need to break into the career they want.

---

## 🌍 The Problem

Students and fresh graduates across Africa often fall into one of two situations:
- They have no idea what career path suits them
- They've identified a path but have no roadmap and no one credible to walk them through it

Generic YouTube videos and blog posts don't cut it. They need real humans who have actually done it.

---

## ✨ What MentorPath Does

- Matches mentees with verified, experienced professionals in their chosen field
- Builds a **personalised career roadmap** based on the mentee's goals, situation, and challenges
- Enables **1-on-1 session booking** with mentors
- Provides **real-time messaging** between mentors and mentees
- Lets mentors publish **career roadmaps and resources**
- Runs on a **freemium + revenue share** model

---

## 👥 User Roles

| Role | Description |
|------|-------------|
| **Mentee** | Students and graduates looking for career guidance |
| **Mentor** | Verified professionals who apply to join and guide mentees |
| **Admin** | Platform operators who approve mentors and manage the platform |

---

## 🚀 Tech Stack

**Frontend**
- React 18 (Vite)
- React Router v6
- Redux Toolkit
- TailwindCSS
- Axios
- Socket.io Client

**Backend**
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.io
- JWT Authentication
- Google OAuth 2.0 (Passport.js)

**Services**
- MongoDB Atlas (database hosting)
- Cloudinary (image uploads)
- Stripe (payments + payouts)
- Google OAuth (social login)

---

## 📁 Project Structure

```
mentorpath/
├── client/                         # React frontend (Vite)
│   └── src/
│       ├── api/                    # Axios API calls
│       ├── components/
│       │   └── layout/             # Shared layouts (MenteeLayout, RouteGuards)
│       ├── pages/
│       │   ├── public/             # Landing, Login, Register
│       │   ├── mentee/             # Dashboard, Explore, Book, Messages etc.
│       │   ├── mentor/             # Mentor dashboard, availability, earnings etc.
│       │   ├── admin/              # Admin dashboard, applications, analytics
│       │   └── shared/             # 404, Terms, Verify Email etc.
│       └── store/                  # Redux slices (auth, ui)
│
└── server/                         # Node/Express backend
    ├── config/                     # DB connection, Passport config
    ├── controllers/                # Route logic
    ├── middleware/                 # Auth, role guards
    ├── models/                     # Mongoose schemas
    ├── routes/                     # API endpoints
    └── sockets/                    # Socket.io real-time events
```



## 📱 Pages (40 total)

**Public (5)** — Landing, Explore Mentors, Mentor Profile, Login, Register

**Mentee (14)** — Dashboard, Onboarding, Career Quiz, Explore, Book Session, Session Room, Leave Review, My Sessions, Messages, Saved Mentors, Roadmaps, Subscription, Notifications, Settings

**Mentor (12)** — Apply, Application Status, Dashboard, Availability, Sessions, Session Room, Roadmap Builder, Messages, Earnings, Edit Profile, Pricing, Notifications

**Admin (8)** — Dashboard, Applications, Users, Sessions, Revenue, Moderation, Analytics, Settings

**Shared (5)** — 404, Terms, Privacy, Verify Email, Forgot/Reset Password

---
