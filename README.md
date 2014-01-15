## D-Network Dayz Epoch Server Pack 1.0.3.1

This is custom DayZ PvE Epoch script pack for Chernarus only. 

### Modifications

- PvE ( No PvP allowed! )
- Animated Heli Crash
- Name Tags
- Custom Menu for specific small scripts
- Selfbloodbag
- Autorefuel
- Salvage modification to remove every part
- NPC (Sarge AI)
- Side Missions (EMS)
- Custom debugmonitor with mission display
- AI Zone Alpha
- Several Map Updates
- Churches replaced to be accessable
- New Traders & Changes
- Traders Safezone
- Wrecks with Loot
- Service Station near Stary City
- Snap Building
- Indestructible Bases
- Extra Vehicles
- No Plot 
- Tow & Lift
- No Tow on locked vehicles

## Map Updates

- New Trader cities
- Bridges to islands Otmel and Skalisty
- Junkyard
- Extra Charnarus Buildings
- Topolka Dam Military Base
- Black Lake Military Base
- Hidden Killers Ranch
- Wreck Sites
- Dead Castle
- Devils Caste
- Prigindy City
- Tikhaya City
- Train Wreck
- Dubrovka Detruit
- Camping Tents 
- Cherno Quarantine
- New Buildings Balota
- New Buildings Cherno
- New Buildings Kamenka

### Installation

- Stop your server
- Download PBO Manager (http://www.armaholic.com/page.php?id=16369)
- Create ```dayz_private_1.epoch.chernarus.pbo```and ```dayz_server.pbo```
- Upload ```dayz_private_1.epoch.chernarus.pbo``` to ```\dayz\mpmissions\```
- Upload ```dayz_server.pbo``` to ```\dayz\@DayZ_Epoch_Server\addons\```
- Clear table ```SERVER_TRADERS```, ```TRADER_DATA```, ```TRADER_TIDS```
- Import attached SQL files
- Start your server

### Configuration

- To get access to the script menu, open ```\dayz_private_1.epoch.chernarus\scripts\custom_menu.sqf``` and add your Arma2 playerid like ```if ((getPlayerUID player) in ["12345"]) then {```

### Credits

#### Modifications

- http://opendayz.net/threads/epoch-animated-heli-crashes.15051/
- http://opendayz.net/threads/release-cpc-name-tags.13292/
- http://opendayz.net/threads/krixes-self-bloodbag-script.12288/
- https://board.nitrado.net/support-de-german-only/support-gameserver/dayz/36409/auto-refuel-for-dummies/
- https://board.nitrado.net/support-de-german-only/support-gameserver/dayz/55833/bexs-epoch-pack-f-r-1-0-3-und-1-0-3-1/
- https://github.com/Swiss-Sarge/SAR_AI-1.5.0
- https://github.com/TheFuchs/EMS-Epoch-Mission-System
- http://epochmod.com/forum/index.php?/topic/4666-zone-alpha/?hl=+zone++alpha
- http://opendayz.net/threads/epoch-safe-zone-commander-god-anti-backpack-stealing-no-shooting-no-vehicle-weapons.14877/
- http://opendayz.net/threads/custom-wrecks-with-loot-why-limit-it-to-heli-crashes-p.10426/
- http://epochmod.com/forum/index.php?/topic/3935-release-vehicle-service-point-refuel-repair-rearm-script/
- http://dayzepoch.com/forum/index.php?/topic/5117-building-snapping/
- http://dayzepoch.com/forum/index.php?/topic/1673-how-to-cpc-indestructible-bases/
- http://www.armaholic.com/page.php?id=9285
- http://epochmod.com/forum/index.php?/topic/2112-tutorial-disabling-r3f-towlift-for-locked-vehicles/

#### Mappings

- http://epochmod.com/forum/index.php?/topic/316-multi-release-cherno-race-tracks-and-custom-campstowns/
- http://epochmod.com/forum/index.php?/topic/316-multi-release-cherno-race-tracks-and-custom-campstowns/
- http://dayzepoch.com/forum/index.php?/topic/325-multi-release-poi-chernarus-by-team-bbc/
- http://epochmod.com/forum/index.php?/topic/1918-nwaf-military-base/
- http://opendayz.net/threads/map-addition-chernogorsk-quarantine-zone.14634/
- https://board.nitrado.net/support-de-german-only/support-gameserver/dayz/49945/lw-dayz-ultima-ultima-epoch-pack/
- http://opendayz.net/threads/various-camping-tent-sites.12623/
- https://github.com/AVendettaForYou/DayZ_Map_Additions/

### Donate

Feel free to support this pack by donating at http://server.nitrado.net/donations/donate/300391