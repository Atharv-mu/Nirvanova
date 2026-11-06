# NIRVANOVA | India's Futuristic Tourism Platform

> **Travel smart. Travel safe. Travel India, better.**

<p align="center">
  <a href="https://nirvanova1.netlify.app/"><img src="https://img.shields.io/badge/Live_Demo-Visit_Site-00e5ff?style=for-the-badge&logo=netlify&logoColor=white" alt="Live demo"></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

**Live demo:** [nirvanova1.netlify.app](https://nirvanova1.netlify.app/)

NIRVANOVA India is a single-page tourism platform prototype that aims to make travel across India more convenient, interactive and safety-focused. It brings destination discovery, hotels, vehicle rentals, verified guides, community sharing, travel credits, emergency assistance, maps and an AI travel assistant into one interface.

It began as a hackathon project and is currently built as a single HTML file with embedded CSS and JavaScript.

---

## Contents

- [Features](#features)
- [Design](#design)
- [Technologies](#technologies)
- [Project structure](#project-structure)
- [Running it locally](#running-it-locally)
- [Data storage](#data-storage)
- [Current limitations](#current-limitations)
- [Future improvements](#future-improvements)
- [Project vision](#project-vision)
- [About the developer](#about-the-developer)

---

## Features

### Explore India

An interactive section for discovering destinations across the country. It currently covers Jaipur, Agra, Kerala, Varanasi, Goa and Manali.

Users can search destinations, save places to their profile, view locations on Google Maps and browse attractions and travel experiences.

### Hotel booking

A mock hotel-booking flow. Users can browse hotels, see ratings and prices per night, choose check-in and check-out dates and the number of guests, then book, review and cancel their bookings.

Sample stays include Heritage Taj View (Agra), Royal Pink Palace (Jaipur) and Kerala Backwater Resort.

> Booking and payment are simulated in the current version.

### Vehicle rentals

Users can browse rental vehicles, check daily prices, pick pickup and return dates, enter a pickup location, and create or cancel bookings. The sample fleet includes a Swift Dzire, a Royal Enfield 350cc and an Innova Crysta.

### User profile

A local profile system where users can set a display name, upload a profile picture, and save and reload their profile. The profile page also shows their credits and bookings. All of this is stored in the browser using `localStorage`.

### Travel credits

A simple reward system. Users earn **10 credits for every uploaded media file**, and **1 credit is worth ₹10** toward mock bookings.

The system supports earning credits, spending them on bookings, deducting them after payment and refunding them when an eligible booking is cancelled.

### Community

A space for travellers to share experiences. Users can write text posts, upload images and videos, search and filter posts, like posts, and see each post's author and timestamp. Community data is stored locally in `localStorage`.

### Media uploads

Users can upload images and videos and preview them directly on the site. Each upload earns credits.

### Verified guides

A sample guide directory showing each guide's name, location, rating, languages and booking option. Guide booking is mock functionality for now.

### Emergency assistance

Quick-access buttons for **Police**, **Ambulance** and the **Tourist Helpline**, along with an embedded Google Map. Users can search for a destination and open it directly on the map.

### AI travel assistant

A lightweight, mock assistant that answers questions such as "Best time to visit Leh?". It gives predefined, contextual responses for Jaipur, Rajasthan, Leh, Ladakh, Manali, Kerala and Goa.

It's structured so that a real AI API can be plugged in later.

### Dynamic hero background

The homepage changes its background image every few seconds, cycling through India, the Taj Mahal, Hawa Mahal, Alleppey Backwaters, the Varanasi Ghats and Old Goa.

---

## Design

NIRVANOVA uses a futuristic, travel-inspired interface with:

- A dark theme with cyan neon accents and purple gradients
- Glassmorphism-style cards and glow effects
- Animated sections and a floating AI assistant
- Integrated maps
- A responsive layout for different screen sizes

---

## Technologies

**Frontend:** HTML5, CSS3 and JavaScript

**Browser features:** `localStorage`, `FileReader`, `URL.createObjectURL()`, DOM manipulation, responsive CSS and Google Maps Embed

**External resources:** Font Awesome, Wikimedia Commons, Unsplash, RandomUser and Google Maps

---

## Project structure

The project is intentionally kept as a single-file prototype.

```
NIRVANOVA-India/
└── index.html      # HTML structure, CSS styling and JavaScript logic
```

---

## Running it locally

No installation or build step is needed.

1. Clone the repository:
   ```bash
   git clone <your-repository-url>
   ```
2. Open the project folder.
3. Open `index.html` in any modern web browser.

---

## Data storage

The prototype uses browser `localStorage` instead of a database. It stores the user profile, credits, saved places, bookings, upload information, community posts and likes.

Because of this, data stays in the browser it was created in and isn't shared between users or devices.

---

## Current limitations

NIRVANOVA is a frontend prototype, not a production-ready booking platform.

**Simulated features:** hotel booking, vehicle booking, payments, guide booking, the AI assistant, credits and user authentication.

**Not yet available:** a backend server, a database, real authentication, a payment gateway, hotel and vehicle rental APIs, a real AI API and cloud media storage.

---

## Future improvements

- **Authentication:** user registration, login, OAuth and secure accounts
- **Backend:** Node.js and Express with REST APIs, a database, and user and booking management
- **Real payments:** gateways such as Razorpay or Stripe
- **Real AI assistant:** personalised itineraries, destination recommendations, travel and budget planning, safety tips and real-time assistance
- **Advanced maps:** live GPS tracking, nearby hospitals, police stations, hotels, restaurants and attractions, and route planning
- **Cloud storage:** move uploaded media out of the browser so it persists
- **Mobile:** a Progressive Web App, then Android and iOS apps

---

## Project vision

NIRVANOVA aims to be a single digital travel ecosystem where travellers can:

> Discover → Plan → Book → Explore → Share → Stay Safe

The long-term goal is to bring tourism discovery, safety, community and travel services together in one platform built for India.

| | |
|---|---|
| **Category** | Tourism / travel technology |
| **Focus** | Smart tourism and traveller safety |
| **Type** | Web prototype |
| **Version** | Prototype v3.0 |
| **Status** | In development |

---

## About the developer

**Atharv Holkar** is a Computer Science Engineering student and developer interested in full-stack development, data structures and algorithms, web technologies, open source, entrepreneurship and building real-world products.

- LinkedIn: [linkedin.com/in/atharvholkar](https://www.linkedin.com/in/atharvholkar/)
- GitHub: [github.com/Atharv-mu](https://github.com/Atharv-mu)

---

If you find this project interesting, consider giving the repository a star on GitHub.

*Travel smart. Travel safe. Travel India, better.*
