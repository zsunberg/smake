# smake
Plays a random good or bad sound file upon make (or any desired command) completion

This scipt executes make with all of the options given to it. If make exits successfully, it randomly selects a sound file from ~/.smake/good and plays it using mplayer. If make fails, it randomly selects a file from ~/.smake/bad and plays it.
