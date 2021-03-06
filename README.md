LIRI - Command Line Assistant

L.I.R.I. stands for Language Interpretation and Recognition Interface. It is a command line node app that takes in parameters and gives back data from various APIs.

As the name suggests, LIRI is analagous to the iPhone's SIRI assistant, but rather than using speech, LIRI is controlled through written text.

The LIRI app uses Node.js in the command line of your computer and has dependencies for the request, spotify, and bandsintown Node packages. It also used the built-in fs package to read and write to text files.

The app features 4 different features using the node liri.js [command-here] syntax. Below are the command types...

 concert-this [band-name-here] returns concert info like the event venue, location and date.
spotify-this-song [song-title-here] returns the artist, album, and preview URL for a specific song using the Spotify API.
movie-this [movie-title-here] returns the year, rating, plot summary, reviews of a specific movie using the IMDb API.
do-what-it-says returns the result of a "random" result by reading the random.txt file and performing the command written in that file. This command can be changed to any one of the 3 types listed above.

https://github.com/onanna/liri-node-app/issues/2#issue-382021404
