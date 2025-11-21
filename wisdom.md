## 🐴 Checklist for every new playthrough
1. Prevent wasting plump helmets.
2. Disable child labor (or only hauling bodies)
3. Deconstruct wagon (you can recover 3 wood logs from it)
4. Build beds (the only thing that can be crafted from wood)
5. Disallow automatic web collection.
6. Start squad training.
7. Assign a manager asap to enable work orders (he needs an office with throne and table).
8. Set up labors:
   - assign a lot of miners and few woodcutters, they should be mutually exclusive
   - everyone should be able to craft (and there should be many craft workshops)
   - militia should have no assigned labor
   - expedition leader, broker and manager should have no other job (could be the same person)
   - carpenter: should be one
   - engraver: should be one
   - animal trainer: only the skilled ones
   - healthcare (chief doctor, diagnostician, surgeon, suturer, wound dresser): only the skilled ones
   - jeweller (gems): should be one
   - cook: should be one
   - smiths (armor & weapon): should be one
   - clothier: should be one

## How to optimize new embarks with "Prepare Carefully"
- First, replace all your pig tail threads, ropes, etc with cave spider silk equivalents. They work just as well and cost half as many points.
- Next, replace your 1 stack of meat with a whole bunch of different kinds of meat, 1 of each. That way, each one comes with its own free barrel that you can use after eating the meat. Doesn't really matter what kind, so just go with the 2-point varieties.
- You can get even more barrels by bringing one of each milk too.
- Get rid of the bags in your profile and instead get 1 of each color of sand. Sand only costs 1 point and each color comes with its own bag, similar to the meat barrel trick I posted above.
- Animals: I recommend a breeding pair of cats (to take care of vermin), a breeding pair of dogs (to train as hunting dogs)
- Turkeys because they produce Leather when Butchered - saving you from needing to bring larger animals to Ranch if you’re trying to produce your own Leather rather than import.
- Turkeys + Pigs is a really solid livestock combo. You get eggs, meat, leather, and milk all without needing any grazing space. Especially nice for fortresses which want to isolate underground as much as possible. (pigs don't need to graze)
- After that, you should still have a fair bit of points left. You can bump up your starting seeds and drinks, then pick up some gypsum plaster (for your hospital, to make casts) and lye (for soap, which is more important than you might think).

## 👨🏻‍💻 Useful DFHack commands
- `repeat --name reset-wear-every-week --time 8400 -command [ remove-wear all ]`
- `repeat --name autonick-every-week --time 8400 -command [ autonick all ]`
- `repeat --name fix-buckets-every-week --time 8400 -command [ fix/dry-buckets ]`
- `repeat --name fix-owned-trash --time 8400 -command [ cleanowned ]`
- `repeat --name clean-all-every-week --time 8400 -command [ clean all ]`
- `repeat --name autodump-every-week --time 8400 -command [ autodump destroy ]`
- `repeat --name extinguish-every-week --time 8400 -command [ extinguish -all ]`
- `repeat --name unclog-fps-every-week --time 8400 -command [ exterminate "RODENT MAN" ]`
- `on-new-fortress ban-cooking booze`
- `deteriorate start --types corpses --freq 0.5,days`
- `prioritize ConstructBuilding`
  will kick your dwarves in the pants and get them to finish constructing all the buildings that are currently ready for construction
- `showmood` reveals what the possessed dwarf really needs
- `gui/autodump` allows selecting items to be removed instantly
- `exterminate` can be ocasionally checked if invisible enemies are not swarming and clogging up FPS

Commands can run on game load when inserted in `C:\Program Files (x86)\Steam\steamapps\common\Dwarf Fortress\dfhack-config\init\onLoad.init`

## 🛤️ How to make quantum stockpiles?
1. Build a mine cart.
2. Designate two 1x1 stockpiles, with same item type, set wheelbarrows to 0.
3. Build a track stop between them (IMPORTANT: needs to halt)
4. Create a new track.
5. Assign the built mine cart to the track.
6. Assign the "from" stockpile to the track.
7. Assign item types to the track.

## 💥 How to make an atom smasher?
1. Build channel, min. 2x1
2. Build a bridge below it.
3. Build a lever.
4. Link lever to the bridge.
5. Designate dump zone.
6. Pull the lever to atom smash.

## 💦 How to drain water off the edge of the map?
1. Dig until edge of the map.
2. Smooth the wall of the last tile.
3. Carve fortifications in the smoothed wall (not build!)
4. Let the water flow away from the map.

## ⛓️ How to strip prisoners?
Assuming you already have caged prisoners stacked in a stockpile:
1. Mark all cages with unforbid select. Visually nothing will change, but in fact it will.
2. Mark all cages with dump select.
3. Click on each cage and unselect dumping (individually per each cage)
4. Citizens will strip prisoners without moving cages (might take some time)

## 🗡️ How to make steel?
1. Make iron  
Smelt: hematite, limonite, magnetite
2. Make pig iron  
At smelter: "Make pig iron bars"  
Requires:  
    - iron
    - coke (from i.e. bituminous coal) or charcoal (from wood)
    - Flux stone boulders: calcite, chalk, dolomite, limestone, marble
3. Make steel  
At smelter: "Make steel bars" (requires the same as above, except pig iron except iron)

## 🧈 What else is worth smelting?
- tetrahedrite (20%), galena (50%), horn silver, silver nuggets -> silver (but not when you want to do electrum)
- malachite, tetrahedrite -> copper
- lignite, bituminous coal -> coke
- cassiterite -> tin (light!)
- sphalerite -> zince (light)
- galena (50%) -> lead

## 🧈 Other bars worth making at smelter:
- bronze bars = copper bar + tin bar
- bismuth bronze bars = copper bar + tin bar + bismuth bar
- brass bars = zinc bar + copper bar
- electrum = silver + gold

## ⛏️ Good non-economic stones:
- cinnabar (heavy)
- cobaltite (heavy)
- pitchblende (heavy)
- petrified wood (light)
- jet (light)
- saltpeper (light)

## 🩺 Minimum to have hospital running?
Items: crutches, splints, threads, clothes, soaps, tables, traction benches, beds, buckets, access to well, plaster powder, chests.  
Personnel: the minimum is a chief medical dwarf and one doctor.

## Random
- Wall engravings have a direction, and only add value to rooms that are in the right direction. Therefore it is necessary to separate bedrooms with 2 tiles of wall in order to optimize engraving value.
  - You could also make the walls out of gem windows, giving both rooms way more value than engraving ever would
- You can remove performer or monster slayer role from residents (Labor/Location) and this way allow them to be assigned to any task.
- Pots are better than barrels for storing booze. They are the same size, use more commonly available material (rock), and train your craftsdwarves better. (pots are barrels made of stone)
- You can protect your nobles by assigning metal gear to them in the nobles screen (n)
- Obsidian short swords are sharper than iron and easier to make (need only obsidian and wood logs) but weak against metal
- Bedrooms can share doors with other bedrooms, effectively serving as connecting rooms, it's not an issue for dwarves and can save space
- It's possible to conqueror or raid friendly sites and not trigger a war (or peace gets declared basically instantly), both by you and other forts in your civ.
- Goblins and elves cannot become necromancers. Elves are already immortal, the secrets of the book don't interest them. See, the book teaches you the secrets of life and death, and it's alluring to humans and dwarves because it's the secret of immortality. That you can reanimate corpses is basically just an added bonus. Elves won't read the book, and even if they do, they won't become necromancers.
- You can't raid your civilization from the map view (by clicking on a site), but you can raid your civilization from Artifacts screen if the site has any. This leads to some quirks: in the report's battle log when an enemy dwarf is killed it is highlighted in purple color - same color as when your own dwarf is killed. Attacked site can imprison your squad, but rescuing them seems to be possible from the "Missing citizens" screen.

## Q & A
Q: How to change available hairstyles and beard styles?  
A: `Dwarf Fortress\data\vanilla\vanilla_entities\objects\entity_default.txt`, look for `[TISSUE_STYLE:HAIR]` and `[TISSUE_STYLE:BEARD]`

Q: Is there an activity/thought related to admiring an artifact on display?  
A: Allegedly yes, but unfortunately, it's very rare.

Q: How to start trading with other civilizations?  
A: Demand tribute from them.

Q: Can humans, elves or goblins serve in military?  
A: Once they become citizens, yes (1 year after becoming residents)

Q: Artifacts appear in 2 different names, how to display both names?  
A: ?

Q: Why marksdwarves aren't shooting through fortifications despite having bolts?  
A: They have too low skill level

Q: How to move items with DFHack?  
A: Designate items to be dumped. Press m to activate keyboard cursor (might need to enable in options first). Type `autodump` in DFHack console (Ctrl+Shift+D).

Q: Do bestowed artifacts have any benefits? Like greater value or attributes.  
A: Sadly, no.

Q: Which animals need pastures?  
A: ...

Q: Cats kill vermin. But what does the vermin do?  
A: Food loss, annoyed dwarves (bad thoughts), infestations

Q: How to protect against sneaky snatchers?  
A: Have dogs.

Q: Do killing forgotten beasts bring any benefit? Are their bodies worth anything?  
A: Unfortunately, no.

Q: How to add new mods to existing save?  
A: Copy installed mod's txt files (ideally with changed filenames) to `SteamLibrary\steamapps\common\Dwarf Fortress\data\vanilla\vanilla_interface\graphics\`. Games reads any .txt files in `data\vanilla`, regardless of their names, thanks to this original files don't have to be edited.

Q: I'm not getting any sieges.  
A: Attack someone. Change "minimum raids between sieges" option in custom difficulty settings.

Q: How to deal with nobles' mandates?  
A: Install [Mandate Manager](https://steamcommunity.com/sharedfiles/filedetails/?id=3482656386)

Q: Way to omit already used bars from the stocks view?  
A: DFHack's cleanconst

Q: Who steps up as a new leader after killing goblin demon overlord?  
A: Random goblin of that civ

Q: DFHack's attribute editor displays two values for each attribute, i.e. 825/2036. First one is clear but what is the max attribute? Is it a fixed maximum potential? I noticed it's different for every dwarf. Is it an arbitrary value randomly assigned on birth?  
A: The maximum is determined either by doubling their starting value for that attribute, or the starting attribute + the average species value for that attribute, whichever is higher. There is also an attribute cap of 5000, but dwarves don't usually need to worry about that. So for example, a dwarf born with a strength of 1500 can reach a total of 3000, while a dwarf born with 1000 strength can only reach a value of 2250 (=1000+1250, the dwarven average for strength) naturally

Q: What are some useful non-default game options to change?  
A: ...

Q: How to make a screenshot of an entire z-level?  
A: ...

Q: Is there a way to deny specific petitions indefinitely? Deny works like a snooze button.  
A: Sadly, no. Accept and ignore petition is a longer snooze button, also gives unhappy thoughts, but you get 2 years pause. Denying grants only few months of pause.

Q: How to make maps less deep? I.e. -20 instead of -120.  
A: Try generating a region instead islands, continents have an unintentional bug (?) of being more shallow. Downside is that it will affect not only caverns.

Q: How to be less overwhelmed with the game?  
A: Limit population in game options. Start with a small number (i.e. 20) and gradually increase it once you reach the limit and feel confident. Also, assign hotkeys to increase and decrease the FPS limit, so that you can slow the game down when things get out of hand.

Q: Any way to start the game without having to build a fort from scratch?  
A: Reclaim abandoned forts. DFHack's `embark-anywhere` (Ctrl+A) and `reveal-hidden-sites` can give you even more options.

Q: What is a "current resident"?  
A: Current resident is the marker for those who have claimed the site. If your fort gets wiped and reclaim it whatever killed you off will also be marked as current resident.

Q: Do dwarves use chests in their bedrooms?  
A: ...

Q: How to make a magma forge/smelter/etc?  
A: It needs one hole with access to 4/7 tile of magma directly beneath the forge (no open space).

Q: Can artifacts be created in non-player sites during the course of the playthrough (after world gen)?  
A: ?

Q: How to prefix book names?  
A: ?

Q: Any way to make mission reports in the world screen unroll quicker? I mean the travelling traces and text animation. After sending many squads far away it gets tedious to read.  
A: Increase FPS.
