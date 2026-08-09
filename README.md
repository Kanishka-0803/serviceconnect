# ServiceConnect 🛠️

An AI-enhanced, location-aware service discovery web platform built with Django and PostgreSQL[cite: 1, 2]. ServiceConnect connects local customers with service professionals without platform commission fees[cite: 1].

## Key Features ✨
* **Geo-Spatial Search:** Uses the **Haversine Formula** to compute distances between live browser GPS coordinates and providers ($O(N \log N)$ sorting)[cite: 1, 2].
* **Emergency SOS Radar:** Broadcasts emergency requests to providers within a **30km radius** using real-time GPS tracking and AJAX polling[cite: 1, 2].
* **AI Support Chatbot:** Integrated **Google Gemini 2.5 Flash API** for 24/7 customer support[cite: 1, 2].
* **Role-Based Workflows:** Custom dashboards for Customers and Service Providers with conflict-free booking and reviews[cite: 1, 2].

## Tech Stack 🛠️
* **Backend & DB:** Python 3.10+, Django 5.x, PostgreSQL (Neon Cloud)[cite: 2]
* **Frontend:** HTML5, CSS3, JavaScript (ES6+), Bootstrap 5[cite: 2]
* **APIs & Deployment:** Google Gemini API, Geolocation API, Render, Cloudinary[cite: 2]

## Quick Start 🚀
1. **Clone repo:** `git clone https://github.com/your-username/ServiceConnect.git`
2. **Install deps:** `pip install -r requirements.txt`[cite: 2]
3. **Set `.env`:** Add `SECRET_KEY`, `GEMINI_API_KEY`, and Cloudinary credentials[cite: 2].
4. **Run:** `python manage.py migrate` && `python manage.py runserver`[cite: 2]

## Team 👥
* **Jeyathakseena R** — API & Deployment[cite: 1]
* **Kanishka S** — Geo-Spatial & Logic[cite: 1, 2]
* **Preethi P** — Frontend UI/UX[cite: 1]
* **Thirthikka K** — Database Architecture[cite: 1]
