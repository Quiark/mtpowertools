# Powertools

Adds tools to make map editing easier.  
Created by rubenwardy. CC0.

## Column Digger

Punch a node. The node you punch and stackcount - 1 nodes below
(or above if up digger) it will be dug, where stackcount is the stack number
of the digger tool. There are also conditional versions that only dig if
conditions are met.

* **Down Column Digger** - no conditions, works on any punchable node
* **Conditional (Start) Down Column Digger** - only works if the punched node
	matches the itemstack to the right of the tool (use to stop accidental digging)
* **Conditional (Same) Down Column Digger** - only digs nodes that are the same
	as the itemstack to the right of the tool

## Column Replacer

Punch a node. The node you punch and stackcount - 1 nodes below
(or above if up digger) it will be replaced with nodes of the type of the
itemstack to the right of the tool.

* **Down Column Replacer** - no condition, works on any punchable node
* **Up Column Replacer** - works up, rather than down

## TODO

* Return dug items when using Down Column Digger
* Up column placer / replacer
* Down column placer / replacer
* Floor placer - punch a wall, and a floor will be placed at that height until
  it reaches another wall. Floor material will be that of the itemstack to the right
* Honour node protection
* Survival version
	* when placing, take from stack to the right.
	* When digging, limit stack count
	* Craft recipes
