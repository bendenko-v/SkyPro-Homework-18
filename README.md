# SkyPro / Homework 18

REST API with MVC pattern for movies.

Database with tables: movie, director, genre.

## Usage

Run "app.py" to start the Flask app.

## App features

* '/movies' view returns a JSON with all movies.
* '/movies/(id)' view returns a JSON with movie by id.
* '/movies?director_id=(id)' view returns a JSON with a list of movies by director id.
* '/movies?genre_id=(id)' view returns a JSON with a list of movies by genre id.
* '/movies?year=(year)' view returns a JSON with a list of movies by year.
---
* '/directors' view returns a JSON with all directors.
* '/directors/(id)' view returns a JSON with director by id.
---
* '/genres' view returns a JSON with all genres.
* '/genres/(id)' view returns a JSON with genre by id.

### Methods POST, PUT and DELETE working with movies instances:
* Use '/movies' view with POST method to add new movie to database;
* Use '/movies/(id)' view with PUT and DELETE methods to change movie data or delete by id.