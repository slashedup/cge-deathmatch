# cge-deathmatch

CGE Deathmatch v1.0.1b update log
 
Supply Drop System
Dynamic Crates: Supply drops now land at 90+ random locations every 7 minutes.
Map Integration: A global map icon will appear whenever a crate is deployed.
Looting Mechanics: Use /loot to claim the drop. Moving or taking damage will now cancel the looting process.
Manual Cancel: Added /cancel command if you need to abort the process quickly.
Drop Rates (Luck Factor): Weapon rewards are now based on rarity:
 Sniper Rifle: 5% Chance
Country Rifle: 15% Chance
 M4 / AK-47: 30% Chance
 SMGs/Shotguns: 50% Chance
Team Synergy: When a crate is opened, all nearby teammates (within 10m) receive weapons, cash, and Zaza rewards!

Zaza (Health) System
Usage: Use /zaza to smoke your grams.
Effect: Smoking a Zaza grants you +40 HP.
Visual FX: Experience the "high" with a 10-second screen shake (drunk effect) that clears up over time.
Combat Lock: You cannot use Zaza if you have taken damage in the last 30 seconds.

Vehicle & Optimization Updates
Smart Respawn: Vehicles will now automatically respawn when their health drops below 301.0 (burning state).
Occupancy Protection: Vehicles with players inside will no longer be force-respawned, preventing annoying bugs.
RAM Efficiency: Vehicle spawn data is now handled via RAM instead of SQL, significantly reducing server lag.
Admin Control: /respawncars command updated to respawn only unoccupied vehicles. 
Weapon Shop & Inventory
Inventory Revamp: Fixed the bug where buying a new gun would reset your entire inventory. You can now carry multiple weapons in different slots (e.g., M4 and MP5 simultaneously).
Newbie Notification: Players will now receive a prompt on spawn if they haven't selected their primary weapon via /weapon.
Economy Balance: Adjusted prices and stock counts to maintain a competitive Gangwar environment.

Bug Fixes
Map Collision: Cleaned up "RemoveBuilding" codes to fix invisible walls and missing map textures.
Infinite Loop Fix: Resolved the "Respawn Loop" bug where vehicles would flicker and respawn every second.
Validation: Fixed several issues where Cash and Zaza counts weren't updating correctly in the database.
Locker System
Slot Management: The locker system has been rewritten. Weapons are now assigned to correct GTA slots, allowing you to carry a Heavy Weapon (M4/AK), a Light Weapon (MP5/Tec9), and a Sidearm simultaneously without them overwriting each other.
Smart Validation: Added a check system that detects if you are "Empty Handed." If you spawn without a loadout, the server will immediately prompt you to use /weapon or visit the locker.
Instant Equip: Fixed the delay when picking up weapons from the locker; weapons are now equipped instantly with the correct ammo counts.
No one can acces your locker, its only for you.



# How to run it?
You need to install plugins first.
pawncmd,
pawnraknet,
samp_bcrypt,
mysql,
sscanf,
streamer,
discord connector
(OPENMP VERSIONS)

This server based in openmp you must install all of compoments

# release: https://github.com/slashedup/cge-deathmatch/releases/tag/cge

