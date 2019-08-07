# wine-origin-updater
Origin doesn't like to update in Wine. This Bash script automatically downloads the newest update and will install it to your installation directory using `wget` and `unzip`. Also uses `aria2` if available.

# How to use:
- Make sure Origin is closed and not running in the background
- Set 'WINEPREFIX' variable to origin prefix path
