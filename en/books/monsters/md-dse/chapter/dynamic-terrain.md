---
file_basename: dynamic-terrain
file_dpath: chapter
item_id: dynamic-terrain
item_name: Dynamic Terrain
name: Dynamic Terrain
order: 2
scc: mcdm.monsters.v1/chapter/dynamic-terrain
source: mcdm.monsters.v1
type: chapter
---

A terrain object is an element placed in an encounter that alters tactics on the battlefield, allowing the Director to better theme an encounter. Terrain objects range from hazards that provide tempting targets for [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), to fieldworks and siege engines that provide a locational advantage, to supernatural objects that an entire encounter can be built around.

### Terrain Object Stat Blocks

Each terrain object is set up in a stat block, but this stat block format is different than for monsters. The following sections explain what you'll find in a terrain object stat block.

#### EV

Each dynamic terrain object has an [encounter value](scc.v1:mcdm.monsters.v1/rule.monster/encounter-value) cost, just like monsters in an encounter. Some objects, particularly environmental hazards, have a cost representing an area, such as a 10 x 10-square section of terrain. A hazard can always be smaller than that indicated size.

#### Stamina

Terrain objects have either a fixed amount of [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) or an amount of [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) per square, depending on their nature and size. If an object has an amount of [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) per square, it can be partially destroyed square by square.

#### Size

Terrain objects either have a standard size (for example, 1M) or a size noted as squares of terrain or material. If a terrain object's size is noted as squares, a creature can move through that terrain object but might trigger the object's effects. Many terrain objects sized in squares are [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain), as noted in the object's size entry.

#### Direction

Some terrain objects have a defined direction indicating how they are placed, such as archer's stakes having a front side.

#### Deactivate

Most terrain objects can be deactivated under certain circumstances. The Sabotage skill is generally applicable for tests made to deactivate mechanisms and siege engines, while traps might allow different skills to be used depending on their setup—Alchemy to deactivate a pool of flammable oil, Nature to deactivate a spiked pit trap in a forest, Magic or Psionics to deactivate a supernatural object, and so forth. Disabling a supernatural object requires a more intricate process detailed in each object's stat block.

Once a terrain object is deactivated, the Director determines what must be done to reset it and how long it takes to do so.

#### Activate

Terrain objects typically activate when a creature enters their space or when the object is interacted with in a specific way. Unless otherwise noted, there is no limit to how often a terrain object can activate.

Some terrain objects, particularly traps and other objects that are set up by creatures, are set to activate only in response to creatures or objects of a particular size. For example, smaller creatures such as goblins and kobolds typically calibrate their traps for size 1M and larger creatures, making those traps safe for smaller creatures to pass through.

Many area terrain objects activate when a creature enters their area without [shifting](scc.v1:mcdm.heroes.v1/movement/shifting). If such a terrain object is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain), remember that creatures can't usually [shift](scc.v1:mcdm.heroes.v1/movement/shifting) through [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) without having a trait or feature that allows them to do so.

#### Effect

Each terrain object's effect entry defines what happens when the object is triggered.

#### Upgrades

Some terrain objects can be upgraded to create additional effects. If a terrain object has a size in squares, the upgrade cost is paid on a square-by-square basis unless otherwise noted.

### Hidden Terrain Objects

Some terrain objects are inherently hidden or can be hidden with an upgrade. Hidden objects can be found as part of the [Search for Hidden Creatures](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/search-for-hidden-creatures) maneuver (see *Draw Steel: Heroes*). When you make an **Intuition test** to search for hidden creatures and objects, use the following outcomes for dealing with objects:

- **≤11:** You find all hidden terrain objects [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you.
- **12-16:** You find all hidden terrain objects within 5 squares of you.
- **17+:** You find all hidden terrain objects within 10 squares of you.

#### Allied Awareness

Some terrain objects have an Allied Awareness trait noting benefits and options available to creatures who have familiarity and training with the object. If a creature is aware of a terrain object and has sufficient time to study it, they gain the object's Allied Awareness benefits at the Director's determination.
