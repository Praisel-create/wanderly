# 🌍 Wanderly – Your Personal Travel Companion

**Wanderly** is a sleek and interactive travel web application that helps users discover destinations, find flight offers, and plan personalized itineraries in one place.  
Built with React and Tailwind CSS, Wanderly provides a seamless experience from login to trip planning, leveraging real-time data from the Amadeus API.

---

## 🚀 Features

### 👤 User Authentication
- Simple **Login Page** with profile picture, username, email, and password.  
- User details are stored locally using **localStorage** for quick access and persistence.

### 🔍 Search Functionality
- Search for destinations by **city**, **time frame**, and **budget range**.  
- Intuitive UI with dropdown navigation (Home, Itinerary).  

### 🏖️ Destinations Page
- Displays a curated list of **popular destinations and activities**.  
- Each destination includes images, descriptions, and prices.  
- Add destinations to your personal itinerary with a single click.

### ✈️ Flight Offers
- Real-time **flight offers** fetched via the **Amadeus API**.  
- Filter and explore flight options based on location, date, and price.

### 🧳 Itinerary Management
- View, add, and remove destinations from your **Itinerary Page**.  
- All data is persisted in **localStorage** for continuity between sessions.

---

## 🛠️ Tech Stack

- **Frontend:** React, Tailwind CSS  
- **API:** Amadeus for travel data (destinations, hotels, flights)  
- **Storage:** Browser LocalStorage  
- **Version Control:** Git & GitHub  
- **Development Environment:** VS Code  

---

## ⚙️ Installation & Setup

Follow these steps to get Wanderly running locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/<your-username>/wanderly.git
   cd wanderly
