# Calagopus_Eggs
Collection of game eggs &amp; files for Calagopus / Pelican / Pterodactyl Panel
Has been written and tested on Calagopus panel, but should be (mostly, if not completely) backwards compatible with Pelican / Pterodactyl.

### Install Instructions:
- Simply import each egg into your panel app - Set the variables / resources and go from there.
- I've attempted to be as verbose as time permits with descriptions (for install scripts, variables & egg descriptions).

## COD2X
[Download CoD2x Calagopus Egg](/cod2x_egg_calagopus.json)
- Runs CoD2 1.3 linux server binaries.
- Adds CoD2x mod: https://cod2x.me/
- Requires all .iwd files from a _legitimate_ install of Call of Duty 2.

- Last updated: 10 Nov 2026

## Battlefield 2142
[Download BF2142 Calagopus Egg](/tbc)
- Found the last linux 2142 dedicated server (v1.10.?).
- Server binary has been patched to connect to OpenSpy (manually via ghidra) as Reclamation only does the win32 binary update.
- Can also be run as a remaster server if desired, by uploading the appropriate maps / files & running the mod as a command switch (to be added in variables)

- Last updated: 11 Nov 2026

## Enemy Terrritory - Quake Wars
- Work-in-progress. As master servers are offline, needs ETQW Server Manager ([https://etqw.org]) to work.
- So far I've got the container running, but the online-part of the server management is looking for a path thats outside the /home/container directory (cannot do in Calagopus / Pelican / Pterodactyl).
- Next step is to either:
  - Create a custom docker image with an inbuilt symbolic / junction link from /app to /home/container _or_
  - Get in touch with the devs and get them to have their script respect $1.
 
- Last updated: 9 Nov 2026
