# 🎬 Movie App

A simple front-end movie web application built with **React** and **Vite**.  
It uses the **TMDB (The Movie Database) API** to search for movies and allows users to add their favorite titles to a dedicated **Favorites** page.

## Features
- Search for movies by title
- View search results with movie posters and details
- Add or remove movies from your favorites
- Favorites are saved locally (via `localStorage`)

## How to Run
1. Clone the repository and install dependencies:
   ```bash
   npm install
   ```
2. Create a `.env` file with your TMDB API key:
   ```
   VITE_TMDB_API_KEY=your_api_key_here
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open the app in your browser at the URL provided by Vite (usually `http://localhost:5173`).

## Tech Stack
- React + Vite
- TMDB API
- LocalStorage for favorites
