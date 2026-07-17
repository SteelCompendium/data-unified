---
agility: 2
ev: "3"
file_basename: umbral-stalker
file_dpath: monster/undead/1st-echelon/statblock
free_strike: 2
immunities:
    - Corruption 1
    - poison 1
intuition: 0
item_id: umbral-stalker
item_name: Umbral Stalker
keywords:
    - Undead
level: 1
might: 0
movement: Climb
name: Umbral Stalker
organization: Horde
presence: 1
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/umbral-stalker
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 4 cold damage
          tier2: 6 cold damage; the stalker can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square
          tier3: 7 cold damage; the stalker [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
      name: Chilling Grasp
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 cube within 1
      effects:
        - roll: Power Roll + 2
          tier1: 2 cold damage
          tier2: 3 cold damage
          tier3: 4 cold damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Freezing Dark
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: The umbral stalker [teleports](scc.v1:mcdm.heroes.v1/movement/teleport) to an unoccupied space in an area of concealment within 10 squares.
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Shadow Jump
      target: Self
      type: feature
      usage: Free maneuver
    - effects:
        - effect: The umbral stalker can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. The first time in a round that the umbral stalker moves through a creature, that creature takes 2 corruption damage. The umbral stalker doesn't take damage from being [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) into objects.
      feature_type: trait
      icon: ⭐️
      name: Corruptive Phasing
      type: feature
free_strike: 2
immunities:
    - Corruption 1
    - poison 1
intuition: 0
keywords:
    - Undead
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/umbral-stalker
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Umbral Stalker
organization: Horde
presence: 1
reason: 0
role: Ambusher
size: 1M
speed: 7
stability: 1
stamina: "15"
type: statblock
```
