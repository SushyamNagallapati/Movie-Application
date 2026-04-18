# Movie App

A clean, responsive movie browsing app built with React. Search for movies, view what's popular, and save your favorites — all powered by the TMDB API.

## Features

- Browse popular movies on load
- Search movies by title
- Add and remove favorites
- Favorites persist across sessions via localStorage

## Tech Stack

- React
- React Router v7
- Vite
- TMDB API

## Getting Started

### Prerequisites

- Node.js 18+
- A free API key from [TMDB](https://www.themoviedb.org/settings/api)

### Installation

```bash
git clone https://github.com/your-username/movie-app.git
cd movie-app
npm install
```

Add your TMDB API key in `src/services/Api.js`:

```js
const API_KEY = "your_api_key_here";
```

### Run locally

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

## Deployment

This app is configured for Vercel. Import the repo on [vercel.com](https://vercel.com) and it will auto-detect the Vite setup. The included `vercel.json` handles client-side routing.

## Project Structure

```
src/
├── components/     # NavBar, MovieCard
├── contexts/       # MovieContext (favorites state)
├── pages/          # Home, Favorites
├── services/       # TMDB API calls
└── css/            # Component styles
```

---

## Built with ❤️ by Sushyam Nagallapati
