# New 5 WAI Missions for 1.0.7.1

Original: https://epochmod.com/forum/topic/45420-outdated-release-5-new-missions-for-wai-223-update-will-be-posted-soon/
* Author: Caveman2019 (for 1.0.6 ver)
* Updated: TheFirstNoob (For 1.0.7+)

## Install

1. Download and unpack
2. Drop all file to folder: **dayz_server\WAI\missions\missions**
3. Open **"dayz_server\WAI\config.sqf"** file.
4. Find ```["patrol",1],``` in ```WAI_HeroMissions``` and ```WAI_BanditMissions```
5. Add this code below: 
```	["fallen_satellite",1],
	["oil_depot",1],
	["refugee",1],
	["gold_mine",1],
	["cargo",1],
```
	
## For AdminTools by BigEgg17:
1. Open **"dayz_server\antihack\menus\owner.sqf"** file.
2. Find ```'patrol',```
3. Add this code below:
```	'cargo',
	'fallen_satelite',
	'gold_mine',
	'oil_depot',
	'refugee',
```
**FINISH:** Save all and Repack dayz_server.pbo

## WARNING
All files didnt have basic stringtable.xml text!
You can create custom stringtable.xml inside mission folder and add text for missions.

[pic1]: (https://imgur.com/PEhTJzo "Oil Depot")

[pic2]: (https://imgur.com/ZwTXYTD "Gold Mine")

[pic3]: (https://imgur.com/B97NQX3 "Cargo")

[pic4]: (https://imgur.com/oBSw8AB "Refugee Camp")

[pic5]: (https://imgur.com/lvaMpZ7 "Fallen Satellite")