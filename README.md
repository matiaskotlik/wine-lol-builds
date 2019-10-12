# Builds of wine-lol for other distributions to use

### How to use

Download the latest tar.gz file from releases, and extract all the files into the `/opt/wine-lol` directory (create this if needed).
The run league with `WINEPREFIX=/full/path/to/install/folder /opt/wine-lol/bin/wine path/to/LeagueClient.exe`

### Releases
Releases are are built using `makepkg -si` on my arch machine using the PKGBUILD in the root folder of the repo.
