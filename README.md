# SSP: ScreenShot Pusher

A really basic tool for flinging png's at a webserver.

## Setup

1. Put `ssp` somewhere in PATH OR alias to its git location.
2. alias it like: `alias ssp='/path/to/ssp user fullDomain /webserver/path/ /public/path`
3. Enjoy hurling png files at the world with more speed.

This assumes you have a public facing html server, exchanged ssh keys, 
have `imagemagick`, `xclip`, `ssh`, `rsync` installed on both ends.

We highlt recommend adding a systemd timer to clean up your images 
folder on whatever basis you desire.
