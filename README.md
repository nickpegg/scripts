# scripts

Random personal scripts that I keep in my ~/bin directory. 

## dock
Do steps required when I dock/undock my laptop at home:

1. Enable external monitor
1. Set default audio output to dock device (external speakers)

## lock
Locks the screen with i3lock, setting the background to a fuzzy version of what you actually have open. Inspired by someone's commands they posted on Reddit in /r/unixporn.

## photodump
Dumps photos from an SD card into ~/Pictures/dump and sorts them into directories by the date they were taken. Really handy when you're travelling and want to move your photos off of your camera to a safe place every night.

It assumes that you have a `/mnt/sd` already configured in `/etc/fstab` that's mountable by your user.

## sync_scripts
Inspired by @akerl's `script_sync`, links scripts from this repo into ~/bin.
