# Dwarf Fortress modlist


[DFHack](https://store.steampowered.com/app/2346660/DFHack__Dwarf_Fortress_Modding_Engine/) (obviously...)  
[Real Time Combat Log, with combat sound](https://steamcommunity.com/sharedfiles/filedetails/?id=2905960813)  
[Interface Tweaks](https://steamcommunity.com/sharedfiles/filedetails/?id=2899720701)  
[ON/OFF Burrows activation button](https://steamcommunity.com/sharedfiles/filedetails/?id=2902547714)  
[Alternate Ramp Icons](https://steamcommunity.com/sharedfiles/filedetails/?id=2901708068)  
[Rounded hills](https://steamcommunity.com/sharedfiles/filedetails/?id=2900381145)  
~~[Vanilla Two Handed Weapons](https://steamcommunity.com/sharedfiles/filedetails/?id=2899369954)~~  use [Arsenal and Cultural Overhaul](https://steamcommunity.com/workshop/filedetails/?id=3500712566)  
[Squad & Burrow Icons](https://steamcommunity.com/sharedfiles/filedetails/?id=2898973979)  
[Audible Alerts](https://steamcommunity.com/sharedfiles/filedetails/?id=2898589374)  
[Reduced Z-Level Fog](https://steamcommunity.com/sharedfiles/filedetails/?id=2898829756)  
[Deon's missing Plant Graphics replacement](https://steamcommunity.com/sharedfiles/filedetails/?id=2899775969)  
[Obvious Engravings](https://steamcommunity.com/sharedfiles/filedetails/?id=2899669508)  
~~[Naut's Equipment Graphics & New Items](https://steamcommunity.com/sharedfiles/filedetails/?id=2900170621)~~ (outdated)  
~~Better Pause and Play Buttons](https://steamcommunity.com/sharedfiles/filedetails/?id=2898964448)~~ (removed)  
[Underground Farming All Seasons](https://steamcommunity.com/sharedfiles/filedetails/?id=2898799817)  
[See-Through Smoothing Designations](https://steamcommunity.com/sharedfiles/filedetails/?id=2898549749)  
[White Z-Level Fog 30%](https://steamcommunity.com/sharedfiles/filedetails/?id=2899417247)  
~~[Rounded wooden doors](https://steamcommunity.com/sharedfiles/filedetails/?id=2900387038)~~ (outdated)  
~~[Lotsa Names](https://steamcommunity.com/sharedfiles/filedetails/?id=2901921699)~~ unnecessary  
~~[Tweaked Faces](https://steamcommunity.com/sharedfiles/filedetails/?id=2898861338)~~ cursed  
~~[Bulk Sewing](https://steamcommunity.com/sharedfiles/filedetails/?id=2904883350)~~ unnecessary  
[Detailed Landscapes](https://steamcommunity.com/sharedfiles/filedetails/?id=2908779064)  
  
[SK Suspend Button](https://steamcommunity.com/sharedfiles/filedetails/?id=2913796002)  
[Metal plate floor](https://steamcommunity.com/sharedfiles/filedetails/?id=2919042512)  
[Oab's Workshop: Dwarves](https://steamcommunity.com/sharedfiles/filedetails/?id=2915127770)  
[MicroMod: always Cloaks](https://steamcommunity.com/sharedfiles/filedetails/?id=2922842361)  
[Gender Name Colors](https://steamcommunity.com/sharedfiles/filedetails/?id=2923299070)  
[Low Population Tweaks](https://steamcommunity.com/sharedfiles/filedetails/?id=2927259273)  
[Slightly Less Urist](https://steamcommunity.com/sharedfiles/filedetails/?id=2928575155)  
[Improved Cat Graphics](https://steamcommunity.com/sharedfiles/filedetails/?id=2933363562)  
[Ketaros Stones Variations](https://steamcommunity.com/sharedfiles/filedetails/?id=2951182373)  

[Mirror (all mods)](https://drive.google.com/drive/folders/1H5hR4cGPM2ytOsqVIZ7sh0QG__M_KI3W?usp=share_link)

new:  
[Work Detail Icons](https://steamcommunity.com/sharedfiles/filedetails/?id=2899155457)  
[Smelt Ore By Product](https://steamcommunity.com/sharedfiles/filedetails/?id=2907526097)  
[Enhanced Trade](https://steamcommunity.com/sharedfiles/filedetails/?id=2924079137)  
[The Language Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=3041526930)  
[Shaped Shoes/Boots](https://steamcommunity.com/sharedfiles/filedetails/?id=2908215621)  
[Cute(r) creatures!](https://steamcommunity.com/sharedfiles/filedetails/?id=2906798609)  
[Gauntlet Equip Fix](https://steamcommunity.com/sharedfiles/filedetails/?id=2920484492)  
Fancy Frames  
Valuable Underground Trees 
Cave ree Farming  
Civilizations support more biomes  
Armed Dwarves  
Vanilla Weapon Overhaul  
Accurate Domestic Animal Graphics Compilation  
Accurate Ungulate Graphics  
More varied Dog and Cat graphics  
Bravely Default Bestiary  
Better Creature Descriptions  
Military Uniforms  
Creature Graphics Extended  
Bourbon's Dark Depths  
Additional Races: Ratfolk  
Seasonish Crops  
Better Instruments  
See-Through Smoothing Designations w/ Priority  
Specific Decoration
Deeper Dwarven Domestication  
Cuter Cavern Moss  
Decoration - vanity buildings  
Piklopedia  
Recycle clothes and armor (cloth and leather)  
More Mushrooms  
Tobb's Steel for Humans  
Tobb's Armor Statues  
Tweaked Faces  
Colors in the Industry (Stained Glass)  
Metallic  

## How to make all male dwarves have a beard?
Edit `[TISSUE_STYLE:HAIR]` in `C:\Program Files (x86)\Steam\steamapps\common\Dwarf Fortress\data\vanilla\vanilla_entities\objects\entity_default.txt`:
```
[TISSUE_STYLE:HAIR]
	TS_PREFERRED_SHAPING:STANDARD_HAIR_SHAPINGS
	[TS_PREFERRED_SHAPING:NEATLY_COMBED]
	[TS_PREFERRED_SHAPING:BRAIDED]
	[TS_PREFERRED_SHAPING:DOUBLE_BRAIDS]
	[TS_PREFERRED_SHAPING:PONY_TAILS]
```

## How to remove bald hairstyles?
Edit `[TISSUE_STYLE:BEARD]` in `C:\Program Files (x86)\Steam\steamapps\common\Dwarf Fortress\data\vanilla\vanilla_entities\objects\entity_default.txt`:
```
[TISSUE_STYLE:BEARD]
	[TS_MAINTAIN_LENGTH:100:NONE]
	TS_PREFERRED_SHAPING:STANDARD_BEARD_SHAPINGS
	[TS_PREFERRED_SHAPING:NEATLY_COMBED]
	[TS_PREFERRED_SHAPING:BRAIDED]
	[TS_PREFERRED_SHAPING:DOUBLE_BRAIDS]
	[TS_PREFERRED_SHAPING:PONY_TAILS]
```
