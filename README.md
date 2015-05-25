A collection of terminal tools to download music from youtube.
To setup just do `./setup.sh`. `batch-dl` relies on youtube-dl,
which you have to install somehow (if you have `pip` just `pip install youtube-dl`)
### What do they do
* `batch-dl` takes a list of song names and downloads them using youtube-dl.
* `list-spotify` takes a url from Spotify's web UI and lists all all the songtracks in it.
Piping these two programs together allows you to "download" songs from spotify. This is exactly what `spotify-dl` does.

### How to use them
* The usage of `batch-dl` is pretty straight forward. See `batch-dl -h` for help.
* `list-spotify` and `spotify-dl` rely on Spotify's API, so you would need to get an access token to use them. If everything is in place, juse `list-spotify -u [url of album or playlist] will list all the sound tracks in standard output.
### How to get access token from Spotify
1. `list-spotify -r` redirects you to the url to register an app
2. `list-spotify -g` redirects you to the url to manually request an `access_token`.
3. `list-spotify -a [access_token] allows you to store access_token you obtained from last step 
