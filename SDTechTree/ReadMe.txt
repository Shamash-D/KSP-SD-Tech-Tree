Shamash Development & Design Bureau Tech Tree

Reconfigures the tech tree and utilizes the stock upgrade modules to produce a hopefully better career experiance, or at the very least, a different one.


Version History:

0.3: enabled subsonic jet engine ISP upgrades, seperatron upgrade modules implimented, large SRBs moved back in tech tree, pre-1.4 replaced parts assigned, added unlock cost to mystery goo, fixed LR-87 second gimbal not getting upgrade applied [WORKING UPDATE]

0.2: some spelling errors fixed, upgrades for antenna added, Wheesley upgrade fixed, optional config file added with SRB gimbals

0.1: configs pushed to GitHub


To-do:
-analyze engine stats and rework their balance
-give the spelling and grammar a thorough check
-add passive EC and heat generators to the LV-N optional config, make it act more like a bimodal nuclear thermal rocket
-analyze and plot new aerospike ISP curves for upgrade modules
-impliment upgrade modules for the supersonic jet engines
+move BACC two tiers back, move shuttle SRB one tier back
+upgrade modules for the seperatrons
-configure alternators to output appropriately to the modified thrust of the engine
+fix the fact that only the first gimbal module on the LR-87 is getting the gimbal upgrade applied
+assign pre-1.4 hidden rocket parts to corresponding node as their replacements [+mk1-2 pod, +Rockomax tanks, +decouplers, +stack seps, +toroid]
-consider moving launch clamp and first radial decoupler back in the tree
-adjust part unlock and upgrade costs
-split engine gimbal upgrade out among multiple nodes, narrow range small engines, medium range small and narrow medium, wide range small medium range medium, full range
-move the MK-55 back, its too much thrust too early with too much gimbal compared to everything else available at its tier
-consider bringing thrust on the LV-T45 and a few other engines up
-add upgrade parameters for jet engine spool speeds
-add useEngineResponseTime upgrades for the rocket engines in the optional configs
-add minThrust upgrades in the optional configs
-RCS upgrade stats
-take a look to see if variant modules can be hidden behind upgrade nodes, and if max thrust and ISP can be effected by variant (mass is established as being modified by variants)

Distant To-do:
-create custom node icons to reduce the number of repeats in the tree
-take a look at engine plumes, see if it can be scaled appropriate to the reduced thrust
-rework the way the jet engines are unlocked and possibly add branch just for jet engine upgrades
-create agorithmic method of implimenting engine rebalances and upgrades to make supporting parts mods easier
-part mod support (Airplanes Plus, RLA Stock-A-Like, kOS, HullCam, DMagic Orbital Science...)
-find or write a script that allows upgrade level to be selected in the editor
