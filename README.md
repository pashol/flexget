# flexget config.yml


Processing of sources:
RSS Source 
                    ------> Transmission ----> Filebot ----> Storage
Rarbg
kat
piratebay

#TV Show
RSS input from showrss. No particular changes to the stream apart from naming and a specific download path. Which is no requirement for filebot (Author switched from "TheRenamer")

#Movies
Trakt acts as wishlist and flexget tries to discover that particular movie from various sources. See beginning of article.
Flexget is able to determine the quality of the source and will act accordingly. In this config it only redirects movies to transmission
which are between 720p-1080p of resolution, any higher source quality than web-dl and only movies with ac3, mp3 or aac audio compression.
In addition flexget is able to filter for the size of the file. This config doesn't like rips which are any lower than 700mb and any larger than 5GB.

#Notify my android
In the case it finds something to feed to transmission, it'll send a notification to your mobile

#Naming
Flexget would be able to name your files and place them accordingly. I wasn't very successful with it.
THere seeem to be plugins to download subtitles, but there were no good configuration examples around. Therefore sticking with filebot was the best decision for now.

