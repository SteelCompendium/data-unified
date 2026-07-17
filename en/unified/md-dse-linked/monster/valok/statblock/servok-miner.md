---
agility: -2
ev: "44"
file_basename: servok-miner
file_dpath: monster/valok/statblock
free_strike: 9
intuition: -1
item_id: servok-miner
item_name: Servok Miner
keywords:
    - Construct
    - Servok
    - Soulless
    - Valok
level: 9
might: 4
movement: Burrow, climb
name: Servok Miner
organization: Elite
presence: -5
reason: -4
role: Controller
scc: mcdm.monsters.v1/monster.valok.statblock/servok-miner
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 6
stamina: "200"
type: statblock
---

```ds-sb
agility: -2
ev: "44"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 4
          tier1: 13 damage; M < 2 [restrained](../../../condition/restrained.md) (save ends) and [prone](../../../condition/prone.md)
          tier2: 18 damage; M < 3 [restrained](../../../condition/restrained.md) (save ends) and [prone](../../../condition/prone.md)
          tier3: 22 damage; [prone](../../../condition/prone.md); M < 4 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Drill Press
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 4 cube within 1
      effects:
        - roll: ""
          tier1: 14 damage; [slide](../../../movement/forced-movement.md) 4; the miner's allies have concealment from the target (save ends)
          tier2: 11 damage; [slide](../../../movement/forced-movement.md) 2
          tier3: 7 damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Unload Rocks
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 20 x 1 line within 1
      effects:
        - roll: ""
          tier1: 14 damage; the target falls into the fissure, and is [prone](../../../condition/prone.md) and can't stand (EoT)
          tier2: 11 damage; the target is [prone](../../../condition/prone.md) and hanging onto the edge of the fissure
          tier3: 7 damage; the target can [shift](../../../movement/shifting.md) into the nearest unoccupied space outside the fissure
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
      name: Break Ground
      target: Each enemy and object in the area
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: Self
      effects:
        - effect: |-
            **Trigger:** The miner is targeted by a strike.
            **Effect:** Until the end of the round, dust and dirt billow in a 2 burst around the miner's initial space. While the miner is in the area, they ignore the nondamaging effects of any strike made against them, including the triggering strike.
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
      name: Miner Inconvenience
      target: Self
      type: feature
      usage: Triggered Action
    - effects:
        - effect: The miner can burrow through stone and metal. When the miner burrows, they create a stable size 2 tunnel in their wake.
      feature_type: trait
      icon: ⭐️
      name: Valiar Tunneler
      type: feature
    - effects:
        - effect: The miner ignores [difficult terrain](../../../movement/difficult-terrain.md), and their abilities deal an extra 15 damage to objects.
      feature_type: trait
      icon: ⭐️
      name: Servok Siege Machine
      type: feature
    - effects:
        - effect: The miner's shape can't be changed by any external effect.
      feature_type: trait
      icon: ⭐️
      name: Crafted to Perfection
      type: feature
    - effects:
        - effect: While the miner isn't [bleeding](../../../condition/bleeding.md), [weakened](../../../condition/weakened.md), or [winded](../../../rule/health/winded.md), any power roll made against them is automatically a tier 1 outcome. A critical hit still grants its additional main action.
      feature_type: trait
      icon: ⭐️
      name: Valiar Might
      type: feature
free_strike: 9
intuition: -1
keywords:
    - Construct
    - Servok
    - Soulless
    - Valok
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.valok.statblock/servok-miner
    source: mcdm.monsters.v1
might: 4
movement: Burrow, climb
name: Servok Miner
organization: Elite
presence: -5
reason: -4
role: Controller
size: "2"
speed: 5
stability: 6
stamina: "200"
type: statblock
```
