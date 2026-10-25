# DojoChef updates

Auto-update packs for the DojoChef Android game. Each release carries:
- version.txt - an integer build number
- dojochef.pck - the game content pack

The game checks releases/latest/download/version.txt on launch and pulls a
newer dojochef.pck when one is available. Published by tools/publish_update.ps1.
