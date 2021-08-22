+++
title = 'Damage'
description = "so. many. tables."
weight = 6
+++

Damage can broadly be split into Infantry and Vehicle Damage models.

# Infantry Damage
Damage against a person or beast or really anything organic is done against their HP and usually mitigated by armour. Infantry armour blocks damage. So when a shot connects, it does its damage first to the armour and then to the wearer’s hit points. Hit points are defined your Body stat - namely 10 x your Body (minimum of 10). Once a player’s hit points are depleted, they take an injury and their hit points reset. The nature of the injury may penalize the reset hit points. Once a player has suffered their maximum amount of injuries, they are considered out of the fight, not necessarily dead. By default, characters have 2 injuries. However, further damage will rapidly hasten the onset of death.  

# Vehicle Damage
Damage against a vehicle is done against their armour and then their structure. Additionally, in this model, damage is measured per hit location, as defined on a character sheet. All of a location’s armour must be depleted before any damage can be done to structure. Different weapons will perform better against structure or armour and different locations will have different armour values depending on their purpose. One a location has lost all its structure points, it becomes destroyed. This may disable the vehicle. Certain weapons may even temporarily disable the location by dealing any amount damage to the structure. When certain locations are damaged, they may make the vehicle as a whole count as destroyed. See the table below.
{{< table style="table-striped" >}}
| Vehicle                     | Parts              |
| --------------------------- | ------------------ |
| Tanks, ground vehicles, etc | Chassis            |
| Mechs                       | Center Torso, Head |
| Aircraft, aerospacecraft    | Yes                |
| Spacecraft                  | Yes\*              |
{{< /table >}}

# Targeting
Shots may be targeted against vehicles, depending on a character’s reaction stat. Players may always allow the GM choice of hit location. Shots at “center mass” reduce the scatter. Headshots resolve at -2.
{{< table style="table-striped" >}}
| Player’s Reaction Stat |                                                                          |
| ---------------------- | ------------------------------------------------------------------------ |
| 1-3                    | GM’s choice of hit location                                              |
| 4-6                    | GM rolls on scatter table (player may, this is to speed things up)       |
| 7-9                    | Roll on Improved scatter table  (player may, this is to speed things up) |
| 10+                    | Player’s choice of hit location                                          |
{{< /table >}}

{{< table style="table-striped" >}}
| Scatter Table |                      | Improved Scatter Table |                      |
| ------------- | -------------------- | ---------------------- | -------------------- |
| D6 roll       |                      | D6 roll                |                      |
| 1             | GM’s choice          | 1                      | GM’s choice          |
| 2             | GM’s choice          | 2                      | Neighboring location |
| 3             | Neighboring location | 3                      | Neighboring location |
| 4             | Neighboring location | 4                      | Hit target           |
| 5             | Hit target           | 5                      | Hit target           |
| 6             | Hit target           | 6                      | Hit target +crit     |
{{< /table >}}

# Critical Hits
Natural 20s on hits against vehicles cause critical hits. If there is a piece of equipment in the location hit, roll to determine if anything happens to it.
{{< table style="table-striped" >}}
| D6 roll |                                      |
| ------- | ------------------------------------ |
| 1       | Equipment disabled 1 round           |
| 2       | Equipment disabled d3 rounds         |
| 3       | Equipment disabled d3 rounds         |
| 4       | Equipment disabled until repair      |
| 5       | Equipment disabled until repair      |
| 6       | Equipment destroyed (ammo explosion) |
{{< /table >}}

# Immobilization and Reduced Mobility
Mechs and ground vehicles can be damaged in such a way that that their mobility is permanent reduced, up to being completely immobilized. Damage to a vehicle’s motive device(s) (whether that be tracks, wheels or hover curtain) will reduce its mobility by a certain amount depending on the vehicle. 

A mech will generally not suffer reduced mobility on damage to its legs, except for highly specialized weapons. Losing a leg however will reduce it to combat speed only, and even then it will move at half its maximum combat speed. Losing both causes the mech to topple and become immobile, though its upper body functions will continue to work. 

*A note about spacecraft: unlike other flying craft, it is possible for a player to continue fighting when a part is destroyed - you’re not going to crash into a ground of some kind. However, given the nature of space combat and the extreme risks involved, it's usually best to register as a non-combatant. 

