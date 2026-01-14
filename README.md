# ✈️ Quix Travel — Mock API Travel Booking Frontend

A production-ready **travel booking frontend** built with **React**, **Vite**, **Tailwind CSS v4**, and **Framer Motion**.  
The app simulates a real travel platform (flights, hotels, holidays) using **mock data** while delivering real-world UX patterns like search, region-based pricing, authentication UI, and third-party integrations.

Live Demo: https://travel-booking-ten-orpin.vercel.app/
Repository: https://github.com/SubDan12/travel-booking

---

## Project Overview

Quix Travel is a **frontend-only application** designed to demonstrate how a real travel booking product behaves — without a backend.

This project focuses on:

- Product-like UX
- Clean component architecture
- Realistic frontend logic
- Performance and responsiveness
- Production deployment workflow

It is **backend-agnostic** and ready to be connected to real APIs in the future.

---

## Key Features

- **Destination Search**
- Search and filter flights, hotels, and holiday packages
- Empty state handling for no results

- **Region-Based Pricing**
- Automatic region detection
- Currency switching (USD / EUR / INR)
- VPN-safe logic

- **Mock API Architecture**
- Structured mock data for all travel entities
- Clean data helpers and filters
- No hard-coded UI logic

- **Authentication UI (Mock)**
- Sign In / Sign Up modal
- Realistic auth flows (frontend only)

- **Newsletter Subscription**
- Real email capture via **Formspree**
- Loading, success, and error states

- **Premium UI & Animations**
- Tailwind CSS v4
- Framer Motion for smooth transitions
- Fully responsive (mobile-first)

- **Production Deployment**
- Deployed on Vercel
- Git-based auto deployment

---

## 🛠 Tech Stack

- **Framework:** React + Vite
- **Styling:** Tailwind CSS v4
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **Forms:** Formspree
- **Deployment:** Vercel

---

## Architecture Notes

- This app uses **mock APIs** (local data + helpers) to simulate real backend behavior.
- Business logic is separated from UI components.
- The frontend is designed to be **plug-and-play** with a real backend later.
- No payments, bookings, or databases are included by design.

---

## Installation & Setup

# Install dependencies

npm install

# Run locally

npm run dev
