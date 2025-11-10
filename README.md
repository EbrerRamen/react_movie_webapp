# 🎬 Movie Finder Web App  

**Movie Finder** is a sleek and modern **React web application** powered by **Appwrite** and the **TMDB (The Movie Database) API**.
It’s designed for movie enthusiasts to explore, search, and discover the **latest** and **trending movies** — all in real time.

---

## 🚀 Features

### 🆕 Latest Movies
- Displays the **latest released movies** fetched directly from the TMDB API.
- Automatically updates to show new releases as they appear.

### 🔍 Search Movies
- Search for any movie by title.
- Instantly view search results with smooth UI updates.

### 🔥 Trending Movies
- See what’s **trending inside the app** — movies that are most searched by users.
- Powered by **Appwrite** backend to track and rank popular searches.

### 🎥 Movie Details
Movie Card shows: 
- 🖼️ **Movie Poster**
- 🎬 **Title**
- 📅 **Release Year**
- ⭐ **Rating**
- 🌐 **Language**

All information is dynamically fetched from the **TMDB API**.

---

## 🧰 Tech Stack

| Technology | Description |
|-------------|-------------|
| **React** | Frontend JavaScript library for building dynamic UIs. |
| **Appwrite** | Backend as a Service (BaaS) for managing trending search data. |
| **TMDB API** | Source for all movie data, posters, and metadata. |

---

## 🧑‍💻 Setup & Installation

### Prerequisites
- Node.js and npm/yarn installed
- TMDB API key
- Appwrite project setup with database and collection

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/EbrerRamen/react_movie_webapp.git
   cd react_movie_webapp
   ```
2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Add environtment variables**
   Create a .env file in the project root:
   ```bash
   VITE_TMDB_API_KEY=your_tmdb_api_key
   VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
   VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
   VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
   ```
4. **Run the app**
   ```bash
   npm run dev
   ```
      
---

## 📺 Demo Source
This project was inspired by and built following this YouTube tutorial:  
🎥 [React JS 19 Full Course 2025 | Build an App and Master React in 2 Hours](https://www.youtube.com/watch?v=dCLhUialKPQ&t=308s)

---

## 🏗️ Future Improvements  
- Movie details page.    
- Add "Add to Saved" feature.  
- Implement authentication with Appwrite.  
- Support for TV shows and multi-language content.  
- Profile management.

---

## 💡 Credits
- **TMDB API** for movie data  
- **Appwrite** for backend and database management  
- **YouTube Tutorial by JavaScript Mastery**  



