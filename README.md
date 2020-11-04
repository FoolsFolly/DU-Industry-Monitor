# DU-Industry-Monitor
Dual Universe script to monitor industry machines

A simple script to display on a screen the Running/Stopped status and remaining crafting time for the current cycle of multiple industry machines. Optionally can also display an output box and the number of items inside.

Requires 1 Screen/Transparent Screen.
1 Programming Board for the display, and an additional Programming Board for each batch of up to 8 industries with identical recipes.
1 Databank, to be attached to each Programming Board.
1 Detection Zone or Switch, and 1 Relay, to turn everything on at the same time.

Copy the scripts here, then right click the programming boards in game, Advanced, Paste LUA configuration from clipboard. Attach devices to appropriately named slots.

Note 1: Since strings cannot be exported as parameters, certain variables had to be hardcoded. You'll need to go into the script of each Industry Programming Board and adjust a few variables, located at the top of unit.tick(), to match the product you are crafting.

Note 2: If you have learned any talents which affect crafting time after a machine was started, that will throw off the math. You'll need to restart the machine before you get an accurate remaining time.
