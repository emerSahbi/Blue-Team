# Cybersecurity game "Blue Team"

Linear game for [KYPO CRP](https://docs.crp.kypo.muni.cz/).

Follow the [general instructions](https://gitlab.ics.muni.cz/muni-kypo-trainings/games/all-games-index) to set up the game.

This game uses `kali` and `debian-10` images from [MUNI-KYPO-IMAGES](https://gitlab.ics.muni.cz/muni-kypo-images), which need to be available in OpenStack for use with KYPO CRP. To get and upload the images, see [this guide](https://gitlab.ics.muni.cz/muni-kypo-images/muni-kypo-images-wiki/-/wikis/How-to-get-image-for-OpenStack).

## Game Levels Summary

* Scan the server with nmap to identify vulnerabilities
* Find backup credentials and log into the server via SSH
* Mitigate vulnerabilities by disabling anonymous FTP and root SSH login
* Search for and remove malicious scripts on the system
* Change a user's password to secure his account
* Securing a server

## Topology summary
|Host|Image|Flavor|
|-|-|-|
|attacker|kali|csirtmu.tiny1x2|
|server|debian-10|csirtmu.tiny1x2|
|client|kali|csirtmu.tiny1x2|
|router|debian-10|csirtmu.tiny1x2|

