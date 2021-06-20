# Flixter
Flixter is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---


## Flixter

### User Stories

- [X]  Users can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [X]  Users can click on a movie to expose details of the movie (ratings using RatingBar, Movie trailer, popularity, language, date-released and synopsis) in a seperate activity.
- [X]  Users can click on a movie to watch the movie's trailer which can be played in full-screen using the YouTubePlayerView.



#### ADDITIONAL FEATURES

- [X] Views are responsive for both landscape/portrait mode.
- [X] In portrait mode, the poster image, title, and movie overview is shown.
- [X] In landscape mode, the rotated alternate layout uses the backdrop image instead and shows the title and movie overview to the right of it.
- [X] Implemented a shared element transition when user clicks into the details of a movie for a smooth transition between the activities.
- [X] Trailers for popular movies are played automatically when the movie is selected.
- [X] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video is played immediately.
- [X] Less popular videos rely on the detailed page to show an image preview that can initiate playing a YouTube video.
- [X] Improved the user interface by experimenting with styling and coloring to give it a more personalized look.



### App Walkthough GIF

<img src="Walkthrough.gif" width=250><br>



## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android





