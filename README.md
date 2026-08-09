# Project Title : ServiceConnect 🛠️
An AI-enhanced, location-aware service discovery web platform built with Django and PostgreSQL[cite: 1, 2]. ServiceConnect connects local customers with service professionals without platform commission fees[cite: 1].

## Problem Solved 
* **Zero Intermediary Fees:** Eliminates high platform commissions, lowering costs for customers and increasing worker pay.
* **Rapid Emergency Dispatch:** Replaces slow booking systems with a live SOS radar for urgent needs.
* **Precise Proximity Matching:** Replaces broad zip-code searches with exact GPS-based distance sorting.
* **Instant AI Assistance:** Replaces rigid bots with 24/7 LLM-driven query resolution.

## Key Features 
* **Geo-Spatial Search:** Uses the **Haversine Formula** to compute distances between live browser GPS coordinates and providers ($O(N \log N)$ sorting).
* **Emergency SOS Radar:** Broadcasts emergency requests to active professionals within a **30km radius** using real-time GPS tracking and AJAX polling.
* **AI Support Chatbot:** Integrated **Google Gemini 2.5 Flash API** for intelligent 24/7 customer support.
* **Role-Based Workflows:** Custom dashboards for Customers and Service Providers with conflict-free booking and reviews.

## Tech Stack 
* **Backend & DB:** Python 3.10+, Django 5.x, PostgreSQL (Neon Cloud)
* **Frontend:** HTML5, CSS3, JavaScript (ES6+), Bootstrap 5
* **APIs & Deployment:** Google Gemini API, Geolocation API, Render, Cloudinary

## Team 
* **Jeyathakseena R** — API & Deployment
* **Kanishka S** — Geo-Spatial & Logic
* **Preethi P** — Frontend UI/UX
* **Thirthikka K** — Database Architecture
