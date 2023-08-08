### Patchnotes:
This plugin was patched in one evening, for the purpose of waiting until https://github.com/marlester-dev/ReallyFakePlayers is fixed to patch https://github.com/marlester-dev/ReallyFakePlayers/issues/20

Some things will be broken:
- Warn messages may get spammed in console because bots don't properly follow the protocol for players joining
- Some plugins depending on PlayerJoinEvent or Protocol things (e.g anticheat) could break

However the NMS and Version has been updated to 1.20.1.
This will likely not be updated frequently as I'm busy with other projects, but open an Issue or PR if you want (it can't hurt!)

### Original README preserved below:

# ReallyFakePlayers
This is a Minecraft server plugin under Spigot environment to simulate players. I personally use it to test my own plugins.
The fake players don't trigger the AsyncPlayerPreLoginEvent and PlayerLoginEvent (and maybe others) which allows to have virtual test accounts on servers that don't accept cracked versions.
I created this fork to update the plugin for Minecraft 1.18.2. The original plugin works in 1.17.

## Download
Download plugin for 1.18.2 ONLY: https://github.com/tristiisch/ReallyFakePlayers/releases/download/v1.11.3/TitanBoxRFP.jar
## Credit
Original creator : https://github.com/freethemice \
Original spigotmc link : https://www.spigotmc.org/resources/really-fake-players.95927/ \
Original github link : https://github.com/freethemice/ReallyFakePlayers
