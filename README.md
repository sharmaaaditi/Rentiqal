# 🏠 Rentiqal — AI-Powered Rental Fraud Detection Platform

## 📌 Overview

Rentiqal is an AI-powered rental fraud detection platform designed to help tenants identify suspicious property listings before making payments or signing agreements.

The platform analyzes rental listings using various fraud indicators such as unrealistic pricing, suspicious descriptions, duplicate images, fake addresses, and scam-related language patterns.

Rentiqal aims to create a safer rental ecosystem by helping users verify listings and avoid common rental scams.

---

## 🎯 Purpose

The purpose of Rentiqal is to provide a digital solution that helps renters make informed decisions when searching for properties online.

This project demonstrates:

* Full-stack web application development
* Machine Learning-based fraud detection
* Natural Language Processing (NLP)
* Image analysis and duplicate detection
* Location verification
* Dashboard and analytics implementation
* Search and filtering functionality
* Responsive UI design

---

## 🚀 Core Features

### 🏘️ Rental Listing Verification

Users can submit rental listings for fraud analysis.

Each listing includes:

* Property title
* Rental price
* Property description
* Property images
* Address/location
* Contact information
* Listing date

---

### 🤖 Fraud Risk Analysis

Rentiqal analyzes multiple fraud indicators and generates a fraud score.

The system evaluates:

* Unrealistically low rental prices
* Scam-related keywords
* Duplicate property images
* Suspicious contact details
* Invalid or suspicious locations

---

### 🖼️ Duplicate Image Detection

The platform checks whether uploaded property images have been reused across multiple listings.

This helps identify:

* Stolen listing photos
* Duplicate advertisements
* Fake property listings

---

### 📍 Location Verification

Rentiqal validates property addresses and checks whether:

* The location exists
* The property type matches the area
* The listed rent is reasonable for the location

---

### 📝 Scam Language Detection

Using NLP techniques, the platform detects common scam phrases such as:

* "Pay advance now"
* "Owner is abroad"
* "Urgent deal"
* "No property visit required"

These patterns contribute to the fraud score.

---

### 📊 Fraud Dashboard

The dashboard provides an overview of submitted listings.

Dashboard features include:

* View all listings
* View fraud risk scores
* Track listing status
* Search listings
* Filter suspicious listings
* View analysis reports

---

### 🔍 Search and Filter

Users can easily manage listings through:

* Search by location
* Search by property title
* Filter by fraud risk level
* Filter by verification status

---

### 🚩 Risk Classification

Each listing is categorized into one of the following levels:

* Low Risk
* Medium Risk
* High Risk

This helps users quickly understand potential threats.

---

## 🧠 How Rentiqal Works

1. User uploads a rental listing.
2. Rentiqal extracts listing information.
3. NLP analyzes the property description.
4. Image analysis checks for duplicate images.
5. Location verification validates the address.
6. Fraud indicators are combined.
7. A fraud score is generated.
8. The user receives a detailed fraud report.

---

## 📊 Example Fraud Report

```text
Fraud Risk Score: 89%

Risk Level: High

Detected Issues:
✓ Rent significantly below market value
✓ Duplicate images found
✓ Suspicious payment request detected
✓ Address validation failed

Recommendation:
Proceed with caution and verify ownership before making any payment.
```

---

## 🌍 Real-World Impact

Rentiqal helps address:

* Online rental scams
* Fake property advertisements
* Advance payment fraud
* Housing marketplace trust issues
* Tenant financial losses

The platform promotes safer property transactions through AI-powered verification.

---

## 🛠️ Technologies Used

### Frontend

* React.js
* Tailwind CSS
* JavaScript ES6+
* React Router DOM

### Backend

* FastAPI
* Python

### Machine Learning

* Scikit-learn
* XGBoost
* Pandas
* NumPy

### Natural Language Processing

* Hugging Face Transformers
* Sentence-BERT

### Computer Vision

* OpenCV
* Image Hashing (pHash)

### APIs

* Google Maps API
* OpenStreetMap

### Database

* PostgreSQL

### Deployment

* Docker
* Vercel
* Render
* AWS

---

## ⚙️ Project Structure

```text
src/
 ├── components/
 │    ├── Navbar.jsx
 │    ├── Hero.jsx
 │    ├── FraudForm.jsx
 │    ├── RiskCard.jsx
 │    ├── ListingCard.jsx
 │    ├── Dashboard.jsx
 │    └── Footer.jsx
 │
 ├── pages/
 │    ├── Home.jsx
 │    ├── Analyze.jsx
 │    └── Reports.jsx
 │
 ├── services/
 │    ├── fraudDetection.js
 │    ├── imageVerification.js
 │    └── locationValidation.js
 │
 ├── App.jsx
 ├── main.jsx
 └── index.css
```

---

## 📦 Installation & Setup

Clone the repository

```bash
git clone https://github.com/sharmaaaditi/Rentiqal.git
```

Navigate to the project directory

```bash
cd rentiqal
```

Install dependencies

```bash
npm install
```

Run the development server

```bash
npm run dev
```

Open in browser

```text
http://localhost:5173
```

---

## 💾 Data Storage

Rentiqal stores listing information and fraud reports in PostgreSQL.

Example listing object:

```javascript
{
  id: 101,
  title: "2BHK Apartment",
  location: "New Delhi",
  rent: 5000,
  description: "Urgent deal, owner abroad, pay token amount now.",
  images: ["property1.jpg"],
  fraudScore: 89,
  riskLevel: "High",
  status: "Flagged",
  createdAt: "2026-06-20"
}
```

---

## 🚀 Future Improvements

Possible future upgrades:

* AI-generated image detection
* Browser extension for rental websites
* Landlord verification system
* Community scam reporting
* Property ownership verification
* Real-time marketplace integration
* Mobile application
* Multilingual support
* Fraud heatmaps for cities
* Verified landlord badges

---

## 🌐 Deployment

Rentiqal can be deployed on:

* Vercel
* Netlify
* Render
* Railway
* AWS

---

## 🏁 Conclusion

Rentiqal is a practical AI-powered platform that addresses the growing problem of rental fraud in online housing marketplaces.

By combining Machine Learning, NLP, Computer Vision, and Location Intelligence, the platform helps users verify rental listings, identify scams, and make safer housing decisions.

The project demonstrates important concepts such as fraud detection, data analysis, image processing, location validation, search and filtering, dashboard development, and modern full-stack application architecture.

Rentiqal showcases how technology can increase trust, transparency, and safety in the rental housing ecosystem.
