## 🐴 Checklist for every new playthrough
1. Prevent wasting plump helmets.
2. Disable child labor (or only hauling bodies).
3. Deconstruct wagon.
4. Build beds (the only thing that can be crafted from wood)
5. Disallow automatic web collection.
6. Set up labors:
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
- `ban-cooking booze`
- `autodump destroy`
- `prioritize ConstructBuilding`  
  will kick your dwarves in the pants and get them to finish constructing all the buildings that are currently ready for construction
- `showmood` reveals what the possessed dwarf really needs
- `gui/autodump` allows selecting items to be removed instantly
- `exterminate` can be ocasionally checked if invisible enemies are not swarming and clogging up FPS

Commands can run on game load when inserted in `C:\Program Files (x86)\Steam\steamapps\common\Dwarf Fortress\dfhack-config\init\init.d`

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

## Random
- Wall engravings have a direction, and only add value to rooms that are in the right direction. Therefore it is necessary to separate bedrooms with 2 tiles of wall in order to optimize engraving value.
  - You could also make the walls out of gem windows, giving both rooms way more value than engraving ever would
- You can remove performer or monster slayer role from residents (Labor/Location) and this way allow them to be assigned to any task.
- Pots are better than barrels for storing booze. They are the same size, use more commonly available material (rock), and train your craftsdwarves better. (pots are barrels made of stone)
