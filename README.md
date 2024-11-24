# **TMDB API Endpoints**

This repository contains the documentation and examples for using the **The Movie Database API (TMDB)**.

---

## **Endpoints Overview**

### **Account**
- **Login**: `POST https://www.themoviedb.org/login`
- **Account Details**: `GET https://api.themoviedb.org/3/account`
- **Add Favorite**: `POST https://api.themoviedb.org/3/account/{account_id}/favorite`
- **Add to Watchlist**: `POST https://api.themoviedb.org/3/account/{account_id}/watchlist`
- **Favorite Movies**: `GET https://api.themoviedb.org/3/account/{account_id}/favorite/movies`
- **Favorite TV Shows**: `GET https://api.themoviedb.org/3/account/{account_id}/favorite/tv`
- **Rated Movies**: `GET https://api.themoviedb.org/3/account/{account_id}/rated/movies`
- **Rated TV Shows**: `GET https://api.themoviedb.org/3/account/{account_id}/rated/tv`
- **Watchlist Movies**: `GET https://api.themoviedb.org/3/account/{account_id}/watchlist/movies`
- **Watchlist TV Shows**: `GET https://api.themoviedb.org/3/account/{account_id}/watchlist/tv`

---

### **Genres**
- **Movie Genres**: `GET https://api.themoviedb.org/3/genre/movie/list`
- **TV Genres**: `GET https://api.themoviedb.org/3/genre/tv/list`

---

### **Movies**
- **Now Playing**: `GET https://api.themoviedb.org/3/movie/now_playing`
- **Popular**: `GET https://api.themoviedb.org/3/movie/popular`
- **Top Rated**: `GET https://api.themoviedb.org/3/movie/top_rated`
- **Upcoming**: `GET https://api.themoviedb.org/3/movie/upcoming`

---

### **Search**
- **Search Movies**: `GET https://api.themoviedb.org/3/search/movie`
- **Search TV Shows**: `GET https://api.themoviedb.org/3/search/tv`
- **Search People**: `GET https://api.themoviedb.org/3/search/person`
- **Search Keywords**: `GET https://api.themoviedb.org/3/search/keyword`

---

### **Movie Details**
- **Movie Info**: `GET https://api.themoviedb.org/3/movie/{movie_id}`
- **Lists for a Movie**: `GET https://api.themoviedb.org/3/movie/{movie_id}/lists`
- **Add Rating**: `POST https://api.themoviedb.org/3/movie/{movie_id}/rating`
- **Delete Rating**: `DELETE https://api.themoviedb.org/3/movie/{movie_id}/rating`
- **Add Movie to List**: `POST https://api.themoviedb.org/3/list/{list_id}/add_item`
## **About the Project**

This project documents various endpoints provided by the TMDB API for managing movies, genres, accounts, and more. It is intended to serve as a reference for developers working with TMDB to build applications that require functionalities like adding favorites, managing watchlists, and searching for movies or TV shows.

The repository is structured for ease of use and provides clear endpoint information along with required parameters. Contributions are welcome to enhance or expand this documentation.
