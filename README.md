# soundcloud-dl
A small command-line program to download tracks from soundcloud.com 

==================================================================
##Installation

####From Source
* Clone the repo or download the zip
* Make sure you have pip installed
* `cd` to the folder
* `pip -install -r "requirements.txt"`

##Usage
* usage: soundcloud-dl.py [-h] [--url URL] [--dir DIR] [--all] [--likes]
* The url can be a link to a user, a track or a user's playlists. Downloads a user's uploads unless --all or --likes options      are given 
* Example : `python soundcloud-dl.py --url "https://soundcloud.com/stringofasymptotes" --dir "D:\Music"`

##Options
     -h, --help  show this help message and exit
     --url URL   URL to download tracks from.
     --dir DIR   Directory to save tracks in. Default value is the current
                 working directory.
     --all       Download all tracks.(Uploads and likes)
     --likes     Download only liked tracks.
  
###Dependencies
* soundcloud - To work with the soundcloud API
* Requests - for retrieving HTML
* Mutagen - To tag mp3 files and add album art

###Contributions
If you want to add features, improve them, or report issues, feel free to send a pull request!!

###Contributors
- [Suyash458](https://github.com/Suyash458)
- [sam09] (https://github.com/sam09) ([Sam Radhakrishnan](https://twitter.com/sam_rk9))
