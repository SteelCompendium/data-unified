---
agility: 0
ev: "10"
file_basename: dwarf-stone-whisperer
file_dpath: monster/dwarf/statblock
free_strike: 5
intuition: 2
item_id: dwarf-stone-whisperer
item_name: Dwarf Stone Whisperer
keywords:
    - Dwarf
    - Humanoid
level: 3
might: 1
movement: Burrow
name: Dwarf Stone Whisperer
organization: Platoon
presence: 0
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-stone-whisperer
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "52"
type: statblock
---

```ds-sb
agility: 0
ev: "10"
features:
    - ability_type: Signature Ability
      distance: 2 cube within 1
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; [slide](../../../movement/forced-movement.md) 1; M < 0 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 8 damage; [slide](../../../movement/forced-movement.md) 3; M < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 11 damage; [slide](../../../movement/forced-movement.md) 5; M < 2 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Tile Slide
      target: Each creature and object in the area
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage; [push](../../../movement/forced-movement.md) 2; R < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 6 damage; [push](../../../movement/forced-movement.md) 3; R < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 9 damage; [push](../../../movement/forced-movement.md) 3; R < 3 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Stone Wave
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever the stone whisperer willingly moves, they can phase through up to 2 squares of stone as part of that movement. If they end their movement inside stone, they are shunted out into the space from which they entered it.
      feature_type: trait
      icon: ⭐️
      name: Stone Walker
      type: feature
free_strike: 5
intuition: 2
keywords:
    - Dwarf
    - Humanoid
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-stone-whisperer
    source: mcdm.monsters.v1
might: 1
movement: Burrow
name: Dwarf Stone Whisperer
organization: Platoon
presence: 0
reason: 2
role: Controller
size: 1M
speed: 5
stability: 2
stamina: "52"
type: statblock
```
