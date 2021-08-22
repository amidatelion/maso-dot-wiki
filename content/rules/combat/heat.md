+++
title = 'Heat'
description = "Return of the tables."
weight = 7
+++
{{< panel title="Under Construction" style="warning" >}} Subject to massive revision. Not really happy with how it slows down combat. {{< /panel >}}

Heat is a characteristic of vehicles that defines how often they are able to fire in a given round. They have a latent heat, heat generation, heat sinking and a heat limit. Latent heat is the baseline level of heat that the mech is currently possessed of. A vehicle may fire all of its weapons as a major action or move its speed without generating Heat. 

Heat generation is the total number of Pushes a vehicle has gone through. Heat sinking is the level of cooling that a mech has, from its weapons and heat sinks. Heat limit is the level of heat that a mech can be possessed of before suffering overheat. Overheat causes effects that can include structural damage, ammo cookoffs and weapon disabilities.  

If a vehicle’s heat level is higher than its maximum heat at the end of the round, it overheats. This may seem complicated, so have an example:
{{< table style="table-striped" >}}
| Latent Heat            | Heat Generation     | Heat Sinking               | Heat at end of round | Heat limit          | Result      |
| ---------------------- | ------------------- | -------------------------- | -------------------- | ------------------- | ----------- |
| Mik’s status is normal | Mik Fires 4 weapons | His heat sinks sink 3 heat |                      | His mech’s heat max | No overheat |
| 0                      | +4                  | \-3                        | 1                    | 2                   |             |
|                        | Plus                | Subtract                   | Equals               | Compared to         | Carry       |
{{< /table >}}

The above is a best-case scenario. However, you’ll find these scenarios to be few and far in between, particularly as players face escalating, ever greater challenges in the process of their mission. 

Below, you’ll find a more common situation. 
{{< table style="table-striped" >}}
| Latent Heat                                                                                     | Heat Generation     | Heat Sinking               | Heat at end of round | Heat limit          | Result         |
| ----------------------------------------------------------------------------------------------- | ------------------- | -------------------------- | -------------------- | ------------------- | -------------- |
| Mik had 1 heat left over from the end of the round, upgraded 2 actions, and was hit by a flamer | Mik Fires 4 weapons | His heat sinks sink 3 heat |                      | His mech’s heat max | Overheat at +1 |
| 2                                                                                               | +4                  | \-3                        | 3                    | 2                   | +1             |
|                                                                                                 | Plus                | Subtract                   | Equals               | Compared to         |                |
{{< /table >}}

Obviously, you don’t need to fire all, or even any weapons. This is your primary means of de-escalating your heat. 

Another thing to note: The overheat value is the difference between a vehicle’s heat limit and the total heat and adds to the roll on the overheat table:

# Heat Consequences
On a roll of 2d6
{{< table style="table-striped" >}}
| Roll | Result                               |
| ---- | ------------------------------------ |
| 2    | Heat Cascade +1                      |
| 3    | Nothing… happens?                    |
| 4    | Heat Bloom -1                        |
| 5    | Heat Cascade +2, Component Damage    |
| 6    | Nothing… happens?                    |
| 7    | Emergency Shutdown!                  |
| 8    | Heat Bloom -2, Structure Damage      |
| 9    | Injury!                              |
| 10   | Emergency Shutdown!                  |
| 11   | Massive Structure Damage             |
| 12   | Ammo Cookoff!                        |
| 13   | Emergency Shutdown! Ammo Cookoff -1! |
| 14   | Injury x2!                           |
| 15+  | Emergency Shutdown! Ammo Cookoff -2! |
{{< /table >}}

**Heat Cascade:** The building heat is too much for your heat stinks to deal with and they begin to fail. Increase latent heat by indicated amount.  
**Nothing… happens?:** You really need me to explain this to you? Consider this a warning.  
**Heat Bloom:** Sweat drips, vision wavers. Due to the rising temperatures in the cockpit, all piloting actions suffer the indicated amount until latent heat reaches zero. This does not stack.  
**Component Damage:** A part of the vehicle suffers damage. GMs choice, and it’s likely to have been one involved in the overheat.  
**Structure Damage:** Wires melt, hydraulics seize and lubricant combusts. Direct damage to the vehicle’s structure occurs to a location of the GM’s choice. Likely to be have been involved in the overheat.  
**Ammo Cookoff!:** Now you’re in it. On a d6 roll of a 5+ your ammunition reserves detonate, dealing max damage to the vehicle's central structure. The target number is reduced by the indicated amount.  
**Injury!:** The heat has become so severe the exposed surfaces of your cockpit are dangerous to touch. You are losing water at a terrifying rate. All crew immediately take an injury.   
**Emergency Shutdown!:** The vehicle’s safeties kick in and turn the vehicle off for a round. A ground vehicle in motion moves in the direction it was moving at half speed. A mech in motion immediately topples and goes immobile. A stationary mech merely goes immobile.  
**Massive Structure Damage:** Like structure damage except worse in every way.   