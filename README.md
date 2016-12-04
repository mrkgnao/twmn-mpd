# An MPD notifier for twmn

`twmn-mpd` is a little notifier for twmn that listens to mpd for

* changes in the currently playing song
* changes in play state (playing -> paused, and so on)

and creates notifications using the excellent [twmn](https://github.com/sboli/twmn/) notification system. 

Install with `pip`:

    $ pip install twmn-mpd

This installs a script called `mpd_twmn_notifier` into your `$PATH` (it does so
into `/usr/bin` for me), which you can either call manually from a terminal or
put in your `.xinitrc` or some other startup script.
