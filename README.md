# MovieDucks

A React-based frontend application for browsing movies and managing a personal watchlist. Users can explore movies in a card grid, add them to a watchlist, and filter/search by genre or rating.

---

## Features

- Browse a grid of **movie cards,** with title, genre, rating, and poster
- Toggle **“Add to Watchlist”** for any movie  
- Two main pages:
  - **Home / Movie List** – browse and search/filter movies based on title, rating, and genere
  - **Watchlist** – view only the movies added to your watchlist  
- Responsive design for desktop and mobile  
- State management with React Hooks (`useState`, `useEffect`)  

---

## Pages & Components

### Movie List Page
- Grid of movie cards with thumbnail, title, genre, rating  
- Add/remove movies to watchlist via toggle switch  
- Search input for filtering by title  
- Dropdown filters for genre and rating  

### Watchlist Page
- Grid of movies currently in your watchlist  
- Remove movies from watchlist via toggle  

---

##  Tech Stack

- **Frontend:** React.js, JSX  
- **State Management:** React Hooks
- **Routing:** React Router  
- **Styling:** CSS  
- **Data:** Static `movies.json` file

---

## Quick Setup

1. Clone the repository
2. Install dependencies with npm install
3. Run the server with npm start