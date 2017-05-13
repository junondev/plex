# Plex
BASH scripts for interacting with Plex Media Server.

## Requirements
* *curl*
* Install *curl* on Debian based systems (including Ubuntu) with: `sudo apt update && sudo apt install curl`

## Versions
* These scripts are tailored to the Ubuntu x86_64 version of Plex Media Server, but can be easily changed by editing the user supplied variables at the top of the scripts.

## Scripts
### plex-update
Checks the currently running and latest versions of Plex Media Server using curl. If the versions are different, the new version is installed.

### plex-update-short
One line example that downloads and installs the latest version of Plex Media Server (Plex Pass, Ubuntu, x86_64 version).
