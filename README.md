# 🏥 Apollo247 Doctor Listing Clone - Internship Assignment

This project is a clone of the **Apollo247 doctor listing destination page**, created as part of an internship assignment. It showcases a full-stack web development approach using **Next.js** for the frontend with **SEO optimization**, a **Node.js/Express** backend, and **MongoDB** for data persistence.

---

## 🔧 Tech Stack

- **Frontend**: Next.js (App Router), React, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Atlas or Local)  
- **API Protocol**: RESTful APIs

---

## 🌐 Live Page Structure

**Implemented Page**:  
`/specialties/general-physician-internal-medicine`

### 🧩 Components

- ✅ Responsive Header  
- ✅ Doctor Listing Section  
- ✅ Functional Filters (Gender, Experience, Availability)  
- ✅ Pagination

---

## ✅ Features

### 🌟 SEO Optimized (Off-Page)

- Meta tags using Next.js Metadata API
- OpenGraph tags
- Twitter cards
- Canonical URLs
- Structured data
- Sitemap.xml and robots.txt

---

## 🧠 Functional Filters

- **Gender**
- **Experience** (minExperience & maxExperience)
- **Availability** (Today, Tomorrow, Weekend)

---

## ⚙️ Backend APIs

### 📥 Add Doctor

- **URL**: `POST /api/doctors/add`
- **Description**: Adds a new doctor to the database
- **Body (JSON)**:
```json
{
  "name": "Dr. Jane Doe",
  "specialization": "General Physician",
  "experience": "10 YEARS",
  "qualification": "MBBS, MD",
  "price": "₹500",
  "location": "Apollo Virtual Clinic - Hyderabad",
  "language": ["English", "Hindi"],
  "consultMode": ["Online Consult"]
}


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
