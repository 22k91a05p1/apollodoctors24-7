**Apollo247 Doctor Listing Clone - Internship Assignment**

This project is a clone of the Apollo247 doctor listing destination page, built using Next.js with off-page SEO, RESTful APIs, and MongoDB as the backend database. The goal is to implement the doctor's listing UI and functional filters using best practices in modern web development.

🔧 Tech Stack
Frontend: Next.js (App Router), React, Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB (local or Atlas)
API Protocol: REST
🌐 Live Page Structure
Implemented Page
/specialties/general-physician-internal-medicine
Components
Responsive Header
Doctor Listing Section
Filters (functional)
Pagination
✅ Features
🌟 SEO Optimized (Off-page)
Dynamic <meta> tags with Next.js metadata API
OpenGraph tags
Twitter cards
Canonical URLs
Structured data
sitemap.xml and robots.txt
🧠 Functional Filters
Gender
Experience (min & max)
Availability (Today, Tomorrow, Weekend)
⚙️ Backend APIs
POST /api/doctors/add

Adds a new doctor to the database
Expects a JSON body with doctor fields
GET /api/doctors

Lists doctors with support for:
Pagination (page, limit)
Filters (gender, availability, minExperience, maxExperience)
Sorting (optional)
⚙️ Environment Variables
Create a .env.local file and add:

MONGODB_URI=mongodb://localhost:27017/apollo-clone
MONGODB_DB=apollo-clone
