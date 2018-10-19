Shamash Development & Design Bureau Tech Tree

Reconfigures the tech tree and utilizes the stock upgrade modules to produce a hopefully better career experiance, or at the very least, a different one.


Version History:

0.3: enabled subsonic jet engine ISP upgrades, seperatron upgrade modules implimented, large SRBs moved back in tech tree, pre-1.4 replaced parts assigned, added unlock cost to mystery goo, fixed LR-87 second gimbal not getting upgrade applied [0.2.5], implimented multiple tiers of engine gimbal upgrades, adjusted some descriptions [0.2.6], updated to 1.5's new parts, moved some parts around (Voskhod 1 to Adv Space Flight, Voskhod 2 to Electrical Systems, launch clamp and radial decoupler to Simple Structures, non-retractable solar panels to Large Electrical Systems) [0.3]

0.2: some spelling errors fixed, upgrades for antenna added, Wheesley upgrade fixed, optional config file added with SRB gimbals [0.2]

0.1: configs pushed to GitHub [0.1]

Immediate To-do (things to do before incimenting version number):
-either adjust experiment unlock progression or adjust experiment return value
-configure alternators to output appropriately to the modified thrust of the engine
-adjust part unlock and upgrade costs
-add upgrade parameters for jet engine spool speeds
-add useEngineResponseTime upgrades for the rocket engines in the optional configs
-add minThrust upgrades in the optional configs
-RCS upgrade stats

General To-do (things that should be done, but aren't a priority for the next patch):
-analyze engine stats and rework their balance
-give the spelling and grammar a thorough check
-add passive EC and heat generators to the LV-N optional config, make it act more like a bimodal nuclear thermal rocket
-analyze and plot new aerospike ISP curves for upgrade modules
-impliment upgrade modules for the supersonic jet engines
-consider bringing thrust on the LV-T45 and a few other engines up
-take a look to see if variant modules can be hidden behind upgrade nodes, and if max thrust and ISP can be effected by variant (mass is established as being modified by variants, might be an easy, if potentially clunky way of implimenting selectable upgrade levels)

Distant To-do (extensive, stretch projects that are a long way down the road):
-create custom node icons to reduce the number of repeats in the tree
-take a look at engine plumes, see if it can be scaled appropriate to the reduced thrust
-rework the way the jet engines are unlocked and possibly add branch just for jet engine upgrades
-create agorithmic method of implimenting engine rebalances and upgrades to make supporting parts mods easier
-part mod support (Airplanes Plus, RLA Stock-A-Like, kOS, HullCam, DMagic Orbital Science...)
-find or write a script that allows upgrade level to be selected in the editor
