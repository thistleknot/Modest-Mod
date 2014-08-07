Modest Mod v2.0
An indispensable mod for Dwarf Fortress v0.34.11

By Igfig


The Modest Mod is a collection of vital bugfixes and tweaks that everyone should be able to use comfortably and without reservation. This mod doesn't add anything new. It doesn't do anything controversial. It's just like vanilla DF, but a little better. French vanilla.

Please direct all questions, suggestions, and comments to the Modest Mod thread at
http://www.bay12forums.com/smf/index.php?topic=105871.0



INSTALLATION

Back up your existing 'raw' folder.
Unzip this archive into your Dwarf Fortress directory.
Say yes when it asks if you want to replace files.



COMPATIBILITY

Modest Mod should be compatible with many mods and some texture packs--anything that doesn't change one of the files listed in "Modified raw files" (see below).

Even if you /have/ modified these files, it's pretty easy to merge things manually. All of my changes are clearly marked in the raw files with a note and the word "Igfig". Everything but the changes to grazers, mounts, children, and egg-layers should be easy to move over. Alternatively, use WinMerge (http://winmerge.org).

In addition, there exist alternate versions of the Modest Mod intended specifically for use with the Ironhand and Phoebus tilesets. Be sure to install Modest Mod AFTER installing the graphics packs.



MODULES

Included with this mod are a number of optional modules that you can use to further customize your game. These modules involve changes that, while popular, are a little too ambitious for the core mod.  Installing modules is easy: open "modest modules/<module name>", put the folder's contents in your Dwarf Fortress directory, and you're done!

Current modules include:

Rubbless:
  Tired of all that useless stone lying around your fortress and clogging your FPS? Now you can say goodbye to wasted stone with Rubbless, the Rubble Remover! Thanks to our secret formula, Rubbless actually evaporates layer rocks as they're mined, leaving you with a fortress that's clean and smooth.
  Warning: Do not use Rubbless if your fortress contains load-bearing pillars of non-economic rock. Side effects may include evaporating trade goods, furniture, and workshops. If you're using another mineral mod, ask your doctor if Rubbless is right for you.

Cat Damper:
  Removes [ADOPTS_OWNER] and [RETURNS_VERMIN_KILLS_TO_OWNER] from cats, preventing catsplosion and widespread miasma.

Eternal Fashion:
  Clothing (except shoes and cloaks) no longer suffers wear and decay, preventing FPS loss and worries about nudity.
  Warning: Immigrants and NPCs will show up at your fort naked but for socks, a vest, and a loincloth. All other clothing counts as armour now, so you'll have to stick all your dwarves in the military and assign them clothes manually.

Pedestals:
  Adds a pedestal building so you can put otherwise useless artifacts and masterworks on display.
  Note that pedestals are built from the Workshops menu and require the Architecture skill.

Skill Tweaks:
  Increases dwarves' skill gain rates for all combat skills (except wrestling, which already trains really fast), plus crutch-walking and swimming.

Seasonal Crops (courtesy of RavingManiac):
  This mod makes farming more realistic by adjusting the growth durations and growing seasons such that crops are grown on an annual basis. The growing seasons of the crops are roughly similar to those of their real-life counterparts. As crop yield per tile is now lower, a larger farm area will be required to adequately provide for the fortress.
  Farm plots should be set such that the desired crop is planted only in the FIRST season of its cycle (e.g. a farm plot is set only to grow pig tails in Spring, with NOTHING set in any of the other seasons). Planting a crop in the wrong season (e.g. planting pig tails in Summer) will result in wasted seeds and no harvest, as the crop will not have enough time to germinate.
  Note from Igfig: I've removed the season restrictions from plump helmets, since being plantable any time is kinda their shtick.



SPECIAL THANKS

Vintermann, for starting the thread that inspired this mod
Meph, for identifying and addressing a lot of issues
RavingManiac, for the Seasonal Crops mod
Joben, for the Broken Arrow mod
Quietust, for creating a whole bunch of binary patches
Elvang, for compiling them into a single .exe
Everyone who's contributed to the thread
And Toady One, of course.



CHANGELOG

v2.1 (11/10/2012)
Not everybody has "extremely long" hair
Wagons are made of real wood, not 'wagon wood'
Fiddled with temperature values of organic materials; undead should die in lava now
Increased shear values of obsidian to match glass
Fixed a bug in the Pedestals module
Eternal Fashion module leaves vests, loincloths, and socks as regular clothing
Added a binary patched .exe (by Quietust and Elvang), fixing many bugs:
- Long patrol duty thoughts accumulate from all squad orders, including training
- Dwarven caravan brought silver crossbow, ITEMS_WEAPON_RANGED ignored in world gen
- Vermin can only escape from artifact animal traps
- Fish in aquariums interfere with vermin behavior checks
- Military dwarves turn off all of their labors when becoming heroes
- Diplomats don't bring bodyguards
- Deconstructing walls teleport material to location


v2.0 (29/08/2012)
Phoebus and Ironhand compatibility!
Rebalanced ranged weapons (Broken Arrow mod by Joben)
Added missing child tags to many creatures
Wooden blocks are now called "planks"

v1.6 (07/07/2012)
Fixed some bugs with milling reactions
Made scale work like leather instead of shells

v1.5 (05/07/2012)
Fixed a duplicate reaction (MILL_FLOUR)
Tweaks to Eternal Fashion module
Added optional Seasonal Crops module (by RavingManiac)

v1.4 (04/06/2012)
Elves have LOCAL_BANDITRY
Changed cave dragons' growth rate to match regular dragons
Added optional Rubbless, Cat Damper, Eternal Fashion, Pedestals, and Skill Tweaks modules

v1.3 (14/05/2012)
Updated to DF v0.34.08 through 11
Added reactions to specify which type of plant to mill
Hooves, nails, claws, and talons heal slowly now, so broken nails won't be lethal.
Hooves are also settable and splintable
Reduced frequency of animal people
Added "Overseer" noble position for succession games

v1.2 (09/04/2012)
Removed skill rate increases for combat skills
Removed NO_EAT and NO_DRINK from kobolds--apparently they don't need it after all

v1.1 (31/03/2012)
Updated to DF v0.34.07
Restored pause and recenter on migrant arrival

v1.0 (27/03/2012)
Reduced clutch size for egg-laying animals
Changed GRAZER values according to an arcane formula to keep grazers happy on smaller pastures
	the formula is GRAZER = 20000 / (BODY_SIZE/3000)^0.8
Multipled panda and red panda's GRAZER by 10 on top of that, so they can survive on relatively little bamboo
Removed MOUNT_EXOTIC from flying and amphibious animals because it was causing pathfinding errors
Mussels and oysters now give pearls when you clean them
Dragons grow up faster (dwarf size within a year, ten times that within two)
Doubled dwarves' skill gain rates for all combat and leadership skills (except wrestling)
Kobolds don't eat, so they no longer die out in worldgen
Dwarves and goblins build fortresses in worldgen, so you can actually find them
Goblins wear less clothing, causing less clutter after sieges
Gave elves and humans diplomats
Gave humans guild reps, so you can make trade requests
weakened serrated disks a little so they don't cut as deeply
Weakened whips and scourges a lot; they still tear skin to bits, but have real trouble with armour
Creatures made out of inorganic materials (except hard-coded ones) can now be butchered
Gave feathers PEARL and ITEMS_SOFT, so you can use them as if they were pearls
Gave scale and chitin SHELL and ITEMS_SCALED so you can use them as if they were shells
Added a few basic adventurer reactions for making crafts
Made outdoor plants more visually distinguishable (by colour)
Added some generic, empty reactions for if you need a new reaction mid-game
Stopped pause and recenter on migrant arrival, citizen birth, and warm/damp walls
Added pause and recenter on death of citizen

New raw files:
	body_pearl.txt
	reaction_adventurer_basic.txt
	reaction_generic.txt
	reaction_specific.txt
	tissue_template_pearl.txt

Modified raw files:
	c_variation_default.txt
	creature_birds.txt
	creature_birds_new.txt
	creature_bug_slug_new.txt
	creature_desert_new.txt
	creature_domestic.txt
	creature_equipment.txt
	creature_large mountain.txt
	creature_large_riverlake.txt
	creature_large_temperate.txt
	creature_large tropical.txt
	creature_large_tundra.txt
	creature_next_underground.txt
	creature_ocean_new.txt
	creature_riverlakepool_new.txt
	creature_small_ocean.txt
	creature_standard.txt
	creature_subterranean.txt
	creature_temperate_new.txt
	creature_tropical_new.txt
	entity_default.txt
	item_ammo.txt
	item_trapcomp.txt
	item_weapon.txt
	material_template_default.txt
	plant_standard.txt
	tissue_template_default.txt

Other modified files:
	announcements.txt
	Dwarf Fortress.exe