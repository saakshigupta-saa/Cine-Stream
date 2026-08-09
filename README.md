# 🎬 Cine-Stream — Media Explorer

Cine-Stream is a Netflix-inspired movie discovery SPA built with **React, Vite, OMDb API, and Gemini AI**. It allows users to discover movies, search titles, view details, save favorites, and get AI-powered recommendations based on their mood.

## 📸 Screenshots

### 🏠 Home Page
<img width="1913" height="983" alt="Screenshot 2026-08-08 193202" src="https://github.com/user-attachments/assets/ad371a2a-45c8-4b7a-a740-f77d916b6ac9" />


### 🔎 Movie Search

<img width="1917" height="998" alt="Screenshot 2026-08-08 195228" src="https://github.com/user-attachments/assets/ebfcffbc-95e0-455d-bc18-72a458ad0da2" />


### 🎬 Movie Details

<img width="1917" height="988" alt="Screenshot 2026-08-08 195247" src="https://github.com/user-attachments/assets/41d82cd7-8636-4d2c-be00-6201fecf0b97" />


### ❤️ Favorites

<img width="1917" height="987" alt="Screenshot 2026-08-08 195205" src="https://github.com/user-attachments/assets/42b2c3be-01b8-41b2-b863-25543f775782" />


---

## ✨ Features

* 🎥 Netflix-style movie discovery UI
* 🔎 Movie search with **500ms debouncing**
* ♾️ Infinite scrolling using `IntersectionObserver`
* ❤️ Favorites with `localStorage`
* 🎬 Detailed movie information
* ▶️ Trailer search integration
* 🤖 AI-powered **Mood Matcher** using Gemini
* 🖼️ Lazy-loaded movie posters
* 📱 Responsive design
* ⚡ Loading and error states

## 🤖 AI Mood Matcher

Describe your mood and Cine-Stream finds a suitable movie.

```text
Your Mood
    ↓
Gemini AI
    ↓
Movie Title
    ↓
OMDb API
    ↓
Movie Recommendation
```

Example:

> "I'm feeling sad but want an action movie."

The AI recommends a movie, which is then automatically searched through OMDb.

## 🛠️ Tech Stack

* React
* Vite
* JavaScript
* CSS
* React Router
* OMDb API
* Google Gemini API
* Git & GitHub

## ⚡ Performance

* **500ms debounce** prevents unnecessary search requests
* **Infinite scroll** loads movies progressively
* **Lazy loading** reduces unnecessary image downloads
* **localStorage** provides persistent favorites

## 🚀 Run Locally

```bash
git clone https://github.com/saakshigupta-saa/Cine-Stream.git
cd Cine-Stream
npm install
npm run dev
```

Create a `.env` file:

```env
VITE_OMDB_API_KEY=your_omdb_api_key
VITE_GEMINI_API_KEY=your_gemini_api_key
```

> 🔐 Never commit your `.env` file or API keys to GitHub.

## 📂 Project Structure

```text
src/
├── api/
├── components/
├── context/
├── hooks/
├── pages/
├── styles/
├── App.jsx
└── main.jsx
```

## 👩‍💻 Author

**Sakshi Gupta**
BSc Computer Science & Data Analytics — IIT Patna

---

⭐ If you like the project, consider giving it a star!
