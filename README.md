# alx-project-0x14

## API Overview
[MoviesDatabase API](https://rapidapi.com/SAdrian/api/moviesdatabase) is a RESTful web service that offers access to detailed information about movies, TV shows, actors, directors and related content. It provides reviews, ratings, plot summaries, high-quality images/videos and more. It enables search via different categories (title, actor, genre, release year, etc) and supports multiple languages.
This api provides complete and updated data for over 9 million titles (movies, series and episodes) and 11 million actors/crew and cast members.

## API Version
RapidAPI supports version 3 of TMDB. 

## Available Endpoints
Titles, Search, Actors, Obsolete.
Every endpoint returns and object with 'results' key.

| Endpoint | HTTP Method | Description |
| --- | --- | --- |
| /titles | GET | Returns array of titles according to filters / sorting query parameters provided |
| /titles/search/title/{title} | GET | Returns array of titles according to filters / sorting query parameters provided and the title provided in path |
| /actors | GET | Returns array of actors according to filters provided |
| /title/utils/titleType | GET | Returs array of title types |
| /titles/{id}/crew | GET | Returns an array of crew according to id provided |
| Other filters/parameters | GET | - |

## Request and Response Format

 ## Authentication

 ## Error Handling

 ## Usage Limits and Best Practices

 
