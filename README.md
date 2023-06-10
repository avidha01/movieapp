# movieapp


This is a simple Movie App that allows users to browse and search for movies. It uses the [The Movie Database (TMDB) API](https://www.themoviedb.org/documentation/api) to fetch movie data.

## Features

- Display popular movies on the homepage
- Search for movies by title
- View movie details including title, poster, rating, and overview
- Responsive design for mobile and desktop

## Demo

[Link to Live Demo](https://your-demo-link.com)

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To run the Movie App locally, you can follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/movie-app.git`
2. Navigate to the project directory: `cd movie-app`
3. Open the `index.html` file in your web browser

## API Configuration

To make requests to the TMDB API, you need to obtain an API key. Follow these steps to set up your API key:

1. Sign up for an account at [TMDB](https://www.themoviedb.org/signup)
2. Go to your account settings and navigate to the "API" section
3. Generate a new API key
4. Replace the `API_KEY` constant in the `script.js` file with your API key

```javascript
const APIURL = "https://api.themoviedb.org/3/discover/movie?sort_by=popularity.desc&api_key=YOUR_API_KEY&page=1";
const SEARCHAPI = "https://api.themoviedb.org/3/search/movie?&api_key=YOUR_API_KEY&query=";

Screenshots:
