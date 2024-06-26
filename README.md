### The "Movie-Booking-Application" is a backend project developed using Spring Boot aimed at managing movie data efficiently. The primary goal is to enable users to view, add, update, and delete movie records while ensuring data integrity and providing robust error handling for common issues like duplicate or non-existent IDs.

# Features
### View Movies: Fetch a list of all available movies.
### Add Movie: Add new movies with unique IDs.
### Retrieve Movie: Get details of a movie by its ID.
### Update Movie: Update movie details using its ID.
### Delete Movie: Remove a movie from the system by its ID.
### Error Handling: Handle errors for duplicate IDs and non-existent movies.
# Technologies Used
### Spring Boot 3.0.0: Core framework for building the application.
### Hibernate: ORM framework for database operations.
### Postman: Tool for testing API endpoints.
# Validation Rules
### Movie name: 3-20 characters.
### ID: Minimum value of 1.
### Director name: Cannot be null.
### Rating: 1-10.
# REST APIs
### GET /ticket/movies: List all movies.
### POST /ticket/movie: Add a new movie.
### GET /ticket/movie/{id}: Retrieve a movie by ID.
### PUT /ticket/update/{id}: Update a movie by ID.
### DELETE /ticket/movie/{id}: Delete a movie by ID.
### Exception Handling
### IdAlreadyExist: Thrown if the movie ID already exists.
### IdNotFound: Thrown if the movie ID is not found.
# Testing
### Ensure all CRUD operations work correctly.
### Validate error handling for duplicate and non-existent IDs using Postman.
