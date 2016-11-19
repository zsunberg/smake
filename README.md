# smake
Plays a random good or bad sound file upon make (or any desired command) completion

This scipt executes make (or any command, with `sdo`) with all of the options given to it. If make exits successfully, it randomly selects a sound file from ~/.smake/good and plays it using mplayer. If make fails, it randomly selects a file from ~/.smake/bad and plays it.

usage:
smake [MAKE_OPTIONS]
sdo [ANY_COMMAND]
a sound file in ~/.smake/good or ~/.smake/bad will be played upon exit
