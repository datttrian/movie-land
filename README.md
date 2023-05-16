# Movie Land

Run the project locally:

``` bash
git clone https://github.com/datttrian/movie-land
cd movie-land
npm install
npm run dev
```

The project is a simplified version of a movie application called "MovieLand." The project aims to build a web application using React, incorporating state management, components, props, and external API integration. The application allows users to search for movies, fetch data from the OMDB API, and display movie information.

The application fetch movie data from the OMDB API by using the fetch function. It demonstrates how to create an asynchronous function called searchMovies that accepts a search title and sends a request to the API using the provided API key. The script then shows how to extract the movie data from the response and log it to the console.

In terms of the JSX structure, the app starts with a div element containing an h1 tag for the application name. Inside the div, there is another div for the search functionality, including an input field and a search icon. The search input has static values for the placeholder and initial value. 

A container div is rendered for individual movie components. Each movie component consists of nested div elements that display movie information such as the year, poster image, type, and title. Placeholder images are used if a movie doesn't have a poster available.

Finally, the movie data is rendered dynamically by mapping through an array of movies and creating multiple movie components.
