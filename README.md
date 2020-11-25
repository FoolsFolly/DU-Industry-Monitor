# DU-Industry-Monitor
Dual Universe script to monitor industry machines

<img src="https://github.com/FoolsFolly/DU-Industry-Monitor/blob/main/image.png" />

A simple script to display on a screen the Running/Stopped status and remaining crafting time for the current cycle of multiple industry machines. Optionally can also display an output box and the number of items inside.

Requires 1 Screen/Transparent Screen, and 1 Programming Board

Optional: 1 Detection Zone, 1 Relay, to turn everything on at the same time.

Copy the script here, then right click the programming board in game, Advanced, Paste LUA configuration from clipboard. Attach devices to appropriately named slots. Adjust parameters in the Advanced menu.

Note 1: If you add spaces or numbers/symbols to the product name, the game will remove the string from the list of exported variables, and you'll need to hardcode to make any further changes.

Note 2: If you have learned any talents which affect crafting time after a machine was started, that will throw off the math. You'll need to update exported variables and restart the machine before you get accurate numbers returned.
