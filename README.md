# Unofficial Red Alert 2 mod branch for OpenRA
This unofficial branch will contain bugfixes and unit rebalancing to try and better replicate the original experience mostly via the yaml files.


# Installation Instructions
  1. Install the latest dotnet sdk and mono (mono 6.9 required, >6.10 causes crashes for unknown reason.)  depending on your OS and reboot
  2. Clone this repo into a folder
  3. Run make.cmd all for windows, make for mac and linux
  4. Navigate to %appdata%\OpenRA\Content\ra2\ for windows, ~/Library/Application Support/OpenRA/Content/ra2 for Mac, or ~/.config/openra/Content/ra2/ for Linux (Create folders if they do not exist) and paste the .mix files from your original game installation.
  5. Open by running launch-game.cmd or launch-game.sh
