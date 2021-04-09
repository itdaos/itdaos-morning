# itdaos-morning
This repo contains all the utility scripts that I use to wake up myself everyday

`gradincvol` requires two arguments ($min, $max). Uses `amixer set` command to change Master volume from min to max. Has conditions for incorrect args.

`rtcwake` requires no arguments. Calculates the next "8:00 in the morning" timestamp and uses it to set system wakeuptime with `rtcwake` command.

`morningroutine` is a script with two commands. First opens nvlc console player with graphical support in background mode. Second runs `gradincvol` to gradually increase volume. My volume starts at 35 and goes to 85.

Motivation and description of the repo is present in this [telegraph](https://telegra.ph/Pishem-korisn%D1%96-skripti-na-bash-04-09)

Star this if you like the approach. ^_^
