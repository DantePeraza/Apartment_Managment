# Apartment Management Application

A full-stack apartment management system built to support direct interactions between tenants and property administrators. The application handles apartment listings, applications, leases, payments, and maintenance requests without relying on third-party listing platforms.

This project was developed as a **group project for a university senior proejct**, with an emphasis on real-world system design, RESTful APIs, and full-stack development.

---

## Features

### Tenant Features
- View available apartments
- Submit rental applications
- View lease details
- Make payments (Stripe integration in progress)
- Submit and track maintenance requests

### Admin Features
- Create and manage apartment listings
- Review applications
- Manage leases and tenants
- Track payments
- Handle maintenance requests
- Role-based access control

---

## Tech Stack

### Frontend
- React
- Next.js
- Tailwind CSS
- JavaScript

### Backend
- Node.js
- Express
- SQLite (local development)
- RESTful APIs
- JWT authentication (cookies)

### Integrations
- Google Platform APIs (location and maps)
- Stripe (payment processing, in progress)
- Formspree (form handling)

---

## Project Structure (High Level)

### Frontend
- Pages built with Next.js App Router
- Reusable components for forms and dashboards
- Tailwind CSS for responsive design

### Backend
- Express server with modular routes
- Middleware for authentication and authorization
- SQLite database with normalized schemas
- Separate routes for admin and user functionality

---

## Getting Started

### Prerequisites
- Node.js
- npm
- Git

### Installation
1. Clone the repository
2. Install dependencies in both frontend and backend directories  
3. Set up environment variables (`.env`)
4. Start the backend server  
5. Start the frontend  

The application runs locally and is prepared for deployment on Render.

---

## Key Concepts Demonstrated

- Full-stack application architecture
- REST API design
- Authentication and role-based authorization
- Database schema design and normalization
- Team collaboration using Git and GitHub
- Iterative development and debugging

---

## Future Improvements

- Complete Stripe payment flow
- PostgreSQL migration for production
- Improved admin analytics dashboard
- Enhanced form validation

---

## Authors

Group project developed for Senior Project  
**Dante Peraza** and team  

---
