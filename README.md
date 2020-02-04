Flix Part 1
User Stories
TODO:// In the User Stories section below, add an x in the -[ ] like this - [x] for any user story you complete. 

REQUIRED (10pts)
 [X](10pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
BONUS
 (2pts) Views should be responsive for both landscape/portrait mode.

 (1pt) In portrait mode, the poster image, title, and movie overview is shown.
 (1pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
 (2pts) Display a nice default placeholder graphic for each image during loading

 (2pts) Improved the user interface by experimenting with styling and coloring.

 (2pts) For popular movies (i.e. a movie voted for more than 5 stars), the full backdrop image is displayed. Otherwise, a poster image, the movie title, and overview is listed. Use Heterogenous RecyclerViews and use different ViewHolder layout files for popular movies and less popular ones.

App Walkthough GIF
TODO:// Add the URL to your animated app walkthough gif in the image tag below, YOUR_GIF_URL_HERE. Make sure the gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after after adding gif)

<"https://i.imgur.com/d4F794S.gifv" width=250>

Notes
Describe any challenges encountered while building the app.

Open-source libraries used
Android Async HTTP - Simple asynchronous HTTP requests with JSON parsing
Glide - Image loading and caching library for Androids

# Flixster2## Flix Part 2

### User Stories

#### REQUIRED (10pts)

- [x] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [ ] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [ ] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [ ] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [ ] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [ ] Apply the popular ButterKnife annotation library to reduce view boilerplate. (1 point)
- [ ] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF

`TODO://` Add the URL to your animated app walkthough `gif` in the image tag below, `YOUR_GIF_URL_HERE`. Make sure the gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after after adding gif)

<https://i.imgur.com/dgnFOQR.gifv" width=250><br>

### Notes

Describe any challenges encountered while building the app.
I have had tremendous ammounts of times that I can use my emmulator and run it and everything completely works, but sometimes it will crash right after when i try again.  Then it will also say unknown device and when that comes up it wont let me use my app at all.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
