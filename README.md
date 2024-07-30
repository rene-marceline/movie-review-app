# 🎬 Movie Review App

The Movie Review App is a simple and efficient Spring Boot application that allows users to browse movies, view details, and add their own reviews. It features a RESTful API for easy integration and supports a variety of CRUD operations on movie data.

## Features

- **Browse Movies**: See a list of movies with essential details.
- **Movie Details**: Access detailed information about each movie, including reviews and ratings.
- **Add Reviews**: Users can add their own reviews and rate movies.
- **Search Functionality**: Search movies by title or genre.

## Technology Stack

- **Backend**: Spring Boot, Spring Data JPA
- **Database**: MongoDB
- **Build Tool**: Maven

## Getting Started

### Prerequisites

- **Java 17**
- **Maven**
- **MongoDB**

### API Endpoints
GET /api/v1/movies: Retrieve all movies.
GET /api/v1/movies/{imdbId}: Retrieve a movie by IMDb ID.
POST /api/v1/reviews: Post review for a movie.
