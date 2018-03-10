This is a fork adding mopidy-spotify functionality to cdown/mpdmenu frontend for MPD.

# Arguments

You may pass mpdmenu arguments first, followed by any dmenu arguments. They are separated by `::`. For example:

    mpdmenu -s :: -sb '#000000'

`-l` is library mode (default), which descends artists and albums. 

`-p` is playlist mode, which selects a track from the current playlist.

`-s` is spotify mode, which can both change spotify playlist and song, aswell as search for albums and tracks.


