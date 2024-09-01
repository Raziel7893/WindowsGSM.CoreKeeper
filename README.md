# WindowsGSM.CoreKeeper
🧩WindowsGSM plugin that provides Core Keeper Dedicated server support!


# The Game
https://store.steampowered.com/app/1621690/Core_Keeper/

# Important
- Your Game Id is stored inside Server Files as GameID.txt (click Browse => Server Files in Wgsm)
- Your World Save is stored in ServerFiles\Saves 
- To configure your server go to %USERPROFILE%\AppData\LocalLow\Pugstorm\Core Keeper\DedicatedServer and edit ServerConfig.json
- If you want to import a world copy it
  - from your client %USERPROFILE%\AppData\LocalLow\Pugstorm\Core Keeper\Steam\$YourSteamID\worlds\0.world.gzip
  - to your server serverfiles\Saves\worlds\0.world.gzip (or default if you don't override default location %USERPROFILE%\AppData\LocalLow\Pugstorm\Core Keeper\DedicatedServer\worlds\0.world.gzip)
- If you don't want to use steam relay service, add parameter "-port 27015" (27015-27050) to host on your own ip. That needs Portforwarding of Port XXXXX TCP/UDP and a semi-static IPv4)


# Installation
1. Download the latest release
2. Move CoreKeeper.cs folder to plugins folder
3. Click [RELOAD PLUGINS] button or restart WindowsGSM
