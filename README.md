# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="http://g.recordit.co/e84nyaQ3aj.gif" width=250><br>

### Notes
I had a major issue getting the collection view cells to display correctly. Initially, the posters were crammed into small 100x100px squares, and I spent 2 days trying to figure out why. I finally resolved the issue by selecting the Collection View Flow Layout item and changing the Estimate Size dropdown from "Automatic" to "None."

## Flix Part 1

### User Stories
#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthough GIF

<img src="http://g.recordit.co/FI129FftyL.gif" width=250><br>

### Notes
I had issues getting AlamofireImage to import correctly. It was solved by running the workspace project first, and then attempting to import AlamofireImage again.
