A collection of terminal tools to download music from youtube
To setup just do `./setup.sh`. `batch-dl` relies on youtube-dl,
which you have to install somehow (if you have `pip` just `pip install youtube-dl`)
### What do they do
* `batch-dl` takes a list of song names and downloads them using youtube-dl.
* `list-spotify` takes a url from Spotify's web UI and lists all all the songtracks in it.
Piping these two programs together allows you to "download" songs from spotify. This is exactly what `spotify-dl` does.
