This is a fork adding mopidy-spotify functionality to cdown/mpdmenu frontend for MPD.

# Arguments

Pass mpdmenu arguments first, followed by any dmenu arguments. They are separated by `::`. For example:

    mpdmenu -p :: -sb '#000000'

`-l` is library mode (default), which descends artists and albums. 
`-p` is playlist mode, which selects a track from the current playlist.
`-s` is spotify mode, which can both change spotify playlist and song
