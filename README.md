# About :sparkles: :camel: :sparkles:
This is a fork adding mopidy-spotify functionality to cdown/mpdmenu frontend for MPD.

### Example of menu
![Examle image 1](http://god.e-grotto.faith/mpd1.png)

### Example of search results
![Examle image 2](http://god.e-grotto.faith/mpd2.png)



## Requirements
You need to be running mpd server with https://github.com/mopidy/mopidy-spotify enabled.

## Arguments

You may pass mpdmenu arguments first, followed by any dmenu arguments. They are separated by `::`. For example:

    mpdmenu -s :: -sb '#000000'

`-l` is library mode (default), which descends artists and albums. 

`-p` is playlist mode, which selects a track from the current playlist.

`-s` is spotify mode, which can both change spotify playlist and song, aswell as search for albums and tracks.


