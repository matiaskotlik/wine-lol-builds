# Builds of wine-lol for other distributions to use

### How to use

Download the latest release packages (.deb files) and install with `sudo dpkg -i /path/to/package.deb`

If you already have League installed using this method and are just updating, you can contiue running League normally.

If you need a fresh install, you can do the following (after installing the packages!):

1. Create a folder somewhere for your league install. In this example I'll do /home/matias/league

2. Download the league installer. You can do this with the command `wget https://lol.secure.dyn.riotcdn.net/channels/public/x/installer/current/live.na.exe -O installer.exe` or you can download it yourself from the riot website and then rename it to `installer.exe`

3. Install league on your computer by running `WINEPREFIX=/home/matias/league /opt/wine-lol/bin/wine installer.exe` (the path after `WINEPREFIX` is the path from step 1). Keep all the default settings, League will install itself to the folder from step 1.

4. Once league is installed you can run it with the command `WINEPREFIX=/home/matias/league /opt/wine-lol/bin/wine "/home/matias/league/drive_c/Riot Games/League of Legends/LeagueClient.exe"`. Remember to replace `/home/matias/league` in my example with the directory you chose in step 1.
