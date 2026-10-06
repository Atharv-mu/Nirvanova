# 🇮🇳 NIRVANOVA India's Futuristic Tourism Platform

> **Travel smart. Travel safe. Travel India — better.**

NIRVANOVA India is a futuristic, single-page tourism platform prototype designed to make traveling across India more convenient, interactive, and safety-focused.

The platform brings together **travel discovery, hotels, vehicle rentals, verified guides, community sharing, media uploads, credits, emergency assistance, maps, and an AI travel assistant in one interface.

This project was developed as a web-based prototype / hackathon project** and is currently implemented using a single HTML file with embedded CSS and JavaScript.

---

## ✨ Features

### 🗺️ Explore India

Discover different destinations across India through an interactive exploration section.

Currently includes destinations such as:

* Jaipur
* Agra
* Kerala
* Varanasi
* Goa
* Manali

Users can:

* Search destinations
* Save places to their profile
* View locations on Google Maps
* Discover attractions and travel experiences

---

### 🏨 Hotel Booking

NIRVANOVA provides a mock hotel-booking experience.

Users can:

* Browse available hotels
* View ratings
* View prices per night
* Select check-in and check-out dates
* Select number of guests
* Book a hotel
* View booking details
* Cancel bookings

Example stays include:

* Heritage Taj View, Agra
* Royal Pink Palace, Jaipur
* Kerala Backwater Resort

> **Note:** The current version uses mock booking and payment functionality.

---

### 🚗 Vehicle Rentals

Users can explore vehicles available for rental.

Supported examples include:

* 🚘 Swift Dzire
* 🏍️ Royal Enfield 350cc
* 🚐 Innova Crysta

Users can:

* View vehicle types
* Check daily rental prices
* Select pickup and return dates
* Enter pickup locations
* Create bookings
* Cancel bookings

---

### 👤 User Profile

The platform includes a local user profile system.

Users can:

* Set a display name
* Upload a profile picture
* Save their profile
* Load their saved profile
* View their credits
* View their bookings

Currently Profile information is stored locally using browser localStorage.

---

### 💰 Travel Credits

NIRVANOVA includes a simple reward system.

Users can earn:

> 10 credits for every uploaded media file

Credits can also be used toward mock bookings.

Current conversion:

> **1 credit = ₹10**

The system supports:

* Earning credits
* Using credits for bookings
* Deducting credits after payment
* Refunding credits when an eligible booking is cancelled

---

### 🌎 Community

The community section allows travelers to share their experiences.

Users can:

* Create text posts
* Upload images
* Upload videos
* Search posts
* Filter posts
* Like posts
* View author information
* View timestamps

Community data is stored locally using `localStorage`.

---

### 📸 Media Uploads

Users can upload:

* Images
* Videos

Uploaded media can be previewed directly inside the website.

The upload system also rewards users with credits.

---

### 🧑‍🏫 Verified Guides

The platform includes a sample verified-guide section.

Users can view:

* Guide names
* Locations
* Ratings
* Languages
* Booking options

The current guide booking buttons are mock functionality.

---

### 🚨 Emergency Assistance

NIRVANOVA provides quick-access emergency options:

* 🚔 Police
* 🚑 Ambulance
* ☎️ Tourist Helpline

The project also integrates a Google Maps embed for location-based assistance.

Users can search for a destination and open it directly on the map.

---

### 🤖 AI Travel Assistant

The project includes a lightweight mock AI travel assistant.

Users can ask questions such as:

```text
Best time to visit Leh?
```

The current prototype provides predefined contextual responses for destinations including:

* Jaipur
* Rajasthan
* Leh
* Ladakh
* Manali
* Kerala
* Goa

> The assistant is currently a mock AI interface and is structured so that a real AI API can be integrated later.

---

### 🌄 Dynamic Hero Background

The homepage automatically changes its background image every few seconds.

The rotating destinations include:

* India
* Taj Mahal
* Hawa Mahal
* Alleppey Backwaters
* Varanasi Ghats
* Old Goa

---

## 🎨 Design

NIRVANOVA uses a futuristic travel-inspired interface.

### Design characteristics

* 🌌 Dark futuristic theme
* 🔵 Cyan neon accents
* 🟣 Purple gradients
* 🪟 Glassmorphism-inspired cards
* ✨ Glow effects
* 📱 Responsive layout
* 🎞️ Animated sections
* 🗺️ Integrated maps
* 💬 Floating AI assistant

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Browser APIs / Features

* localStorage
* FileReader
* URL.createObjectURL()
* DOM manipulation
* Responsive CSS
* Google Maps Embed

### External Resources

* Font Awesome
* Wikimedia Commons
* Unsplash
* RandomUser
* Google Maps

---

## 📂 Project Structure

The current version is intentionally maintained as a **single-file prototype**.

```text
📦 NIRVANOVA-India
└── 📄 index.html
```

The `index.html` file contains:

```text
├── HTML structure
├── CSS styling
└── JavaScript functionality
```

---

## ▶️ How to Run

No installation or build process is required.

1. Clone the repository

```bash
git clone <your-repository-url>
```

2. Open the project

Navigate to the project directory.

3. Run the website

Open:

```text
index.html
```

in any modern web browser.

That's it! 🚀

---

## 💾 Data Storage

The current prototype uses browser localStorage instead of a backend database.

Stored information includes:

* User profile
* Credits
* Saved places
* Bookings
* Upload information
* Community posts
* Likes

Because the project uses browser storage, the data is local to the user's browser.

---

## ⚠️ Current Limitations

This is currently a frontend prototype, not a production-ready travel booking platform.

Some features are simulated:

* Hotel booking
* Vehicle booking
* Payments
* Guide booking
* AI assistant
* Credits
* User authentication

There is currently no:

* Backend server
* Database
* Real authentication
* Real payment gateway
* Real hotel booking API
* Real vehicle rental API
* Real AI API
* Cloud media storage

---

## 🔮 Future Improvements

The next versions can introduce:

### 🔐 Authentication

* User registration
* Login
* OAuth
* Secure user accounts

### 🗄️ Backend

* Node.js / Express
* REST APIs
* Database integration
* User management
* Booking management

### 💳 Real Payments

Integration with payment gateways such as:

* Razorpay
* Stripe

### 🤖 Real AI Assistant

Replace the mock assistant with an actual AI-powered travel assistant capable of:

* Personalized itineraries
* Destination recommendations
* Travel planning
* Safety recommendations
* Budget planning
* Real-time travel assistance

### 📍 Advanced Maps

Future versions could include:

* Live GPS tracking
* Nearby hospitals
* Nearby police stations
* Hotels near the user
* Restaurants
* Tourist attractions
* Route planning

### ☁️ Cloud Storage

Move uploaded media from browser storage to cloud storage for persistent access.

### 📱 Mobile Application

The platform could eventually be converted into:

* Progressive Web App
* Android application
* iOS application

---

## 🎯 Project Vision

NIRVANOVA aims to create a unified digital travel ecosystem where travelers can:

> Discover → Plan → Book → Explore → Share → Stay Safe

The long-term vision is to combine tourism discovery, safety, community interaction, and travel services into a single platform focused on India.

---

## 🏆 Project Type

**Category:** Tourism / Travel Technology
**Type:** Web Prototype
**Focus:** Smart Tourism & Traveler Safety
**Platform:** Web
**Current Version:** Prototype

---

## 👨‍💻 Developer

### Atharv Holkar

Computer Science Engineering Student & Developer

Interested in:

* Full-Stack Development
* Data Structures & Algorithms
* Web Technologies
* Open Source
* Entrepreneurship
* Problem Solving
* Building real-world products

### 🔗 Connect

* 💼 [LinkedIn](https://www.linkedin.com/in/atharvholkar/)
* 🐙 [GitHub](https://github.com/Atharv-mu)


## 📌 Project Status

**Current Version:** Prototype v1.0

**Status:** 🚧 In Development

The project is currently a frontend prototype and can be expanded into a full-stack tourism platform in future versions.


## ⭐ Support

If you find the project interesting, consider giving the repository a ⭐ on GitHub.

NIRVANOVA India 🇮🇳

> Travel smart. Travel safe. Travel India — better.
