# Smart Living Wellness PWA – Architecture

## Overview
A modular progressive web app for wellness tracking and services.

## Frontend
- Built with Next.js (App Router)
- Tailwind CSS for styling
- PWA support via manifest.json + service worker

## Backend
- Node.js/Express API (future expansion)
- Routes for authentication, plans, and payments
- Controllers for business logic
- Models for database entities

## Database
- Configurable with migrations and seeds
- Supports Firebase (MVP) or PostgreSQL (scalable)

## Deployment
- Frontend deployable on Vercel/Netlify
- Backend deployable on Heroku/Render
- Database hosted on Firebase or Supabase

## Testing
- Jest + React Testing Library for frontend
- Supertest for backend API routes
