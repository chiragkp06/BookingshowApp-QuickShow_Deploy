<img width="1709" height="892" alt="image" src="https://github.com/user-attachments/assets/d1bc2a52-cd70-460c-acda-72e36ab0fc7c" />





🎬 QuickShow – Movie Ticket Booking App
QuickShow is a full-stack MERN-based movie ticket booking application that enables users to browse movies, book seats, make secure payments via Stripe, and manage bookings in real-time. The app features user authentication (via Clerk), role-based access for admins, and an integrated dashboard for managing movies, bookings, and showtimes.

💻 Tech Stack
Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB (Mongoose)

Authentication: Clerk Auth

Payment Gateway: Stripe

Background Jobs: Inngest

Deployment: Vercel (frontend) & Render (backend)

Features
-Browse and book movie tickets by showtime and seat
-Secure login & signup via Clerk
-Stripe integration for payments
-Admin dashboard to manage movies, users, bookings
-Booking history and invoice support
-Email notification triggers (Inngest)

**.**How to Run Locally 
# Clone the repo

# Install dependencies
cd client && npm install
cd ../server && npm install

# Add .env variables (Stripe key, Mongo URI, Clerk keys)

# Run the app
npm run dev
