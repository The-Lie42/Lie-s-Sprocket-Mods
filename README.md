# Lie-s-Sprocket-Mods
Repo for Lie's mods for the tank designer game Sprocket.<br>
AI use: The following mods are made with heavy AI assistance, which includes research into the game's code, feasibility studies, coding and patching. All mods however are manually tested to work for all listed compatible game versions, and all "save-safe" features are also manually tested.

---
## Lie's Transmission Rework
A comprehensive transmission overhaul that simulates differential steering with power redistribution, torque fixes for Twin-Transmission, and improved meshing system that simulates modern transmission systems that partially retains torque during shifting.<dr>
For Sprocket 0.2.55.5 and 0.2.56.1<dr>

### True Differential Steering
The way vanilla Sprocket do neutral steering baffles me. Twin transmission uses two independent gearboxes which can be shifted separately to achieve neutral steering, which to my knowledge the last notable implementation was on the A7V.<br>
This true differential steering uses a single gearbox, and steers the tank via power reassignment, emulating German big cats and cold war NATO tanks. This new design allows neutral steering and regenerative steering, which means the tank loses little speed and sometimes can even accelerate during turning.<br>
Simply select Clutch-Braking transmission, and a second selection tab appears that allows you to select Differential steering.<br>
Save safe, the game will simply treat the modded vehicle as vanilla Clutch-Braking transmission if loaded without the mod.<br>

### Twin Transmission Torque Fixes
Have you ever felt that twin transmission in Sprocket is just that tad weaker than clutch-braking in acceleration?<br>
This is because Sprocket divides the total torque output by the engine into two halves for each gearbox, hence to each track. But for clutch-brakes, the game give 100% of torque into the single gearbox, and that somehow means each track receive 100% torque instead of 50%.<br>
This mod fixes that by doubling torque power for each gearbox in twin transmission. Simply select twin transmission, and a second selection tab appears that allows you to select the improved variant.<br>
Save safe, the game will simply treat the modded vehicle as vanilla twin transmission if loaded without the mod.<br>
This mod really is made partially redundent by the previous mod, but hey, if anybody want to make a modern A7V...I guess?<br>

### Modern Synchromesh
Modern tank gearboxes can achieve a shift in about 0.4-0.6s under normal situations. Sprocket ones achieve a shift in about 1 second. This mod adds another mesh type to bring Sprocket ones up to modern standards. This mesh type also comes with the benefit that the gearbox partially retains torque output during shifting, similar to modern NATO and Chinese MBTs.<dr>
Simply select Synchromesh (Modern) in mesh type in your transmission.<dr>
Save safe, the game will simply treat the modded vehicle as vanilla Synchromesh if loaded without the mod.<br>
