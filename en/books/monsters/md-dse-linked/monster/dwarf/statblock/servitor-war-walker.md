---
agility: 0
ev: "12"
file_basename: servitor-war-walker
file_dpath: monster/dwarf/statblock
free_strike: 4
intuition: 0
item_id: servitor-war-walker
item_name: Servitor War Walker
keywords:
    - Dwarf
    - Humanoid
level: 1
might: 2
movement: Climb
name: Servitor War Walker
organization: Elite
presence: -2
reason: -2
role: Mount
scc: mcdm.monsters.v1/monster.dwarf.statblock/servitor-war-walker
size: "3"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "60"
type: statblock
---

```ds-sb
agility: 0
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage
          tier2: 9 damage
          tier3: 12 damage; M < 2 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Grasping Claws
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 burst
      effects:
        - roll: Power Roll + 2
          tier1: 3 lightning damage; A < 0 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 6 lightning damage; A < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 7 lightning damage; A < 2 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Stunning Blast
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: While riding the war walker, three size 1 allies can occupy the same space. Creatures riding the war walker have cover.
      feature_type: trait
      icon: ⭐️
      name: Cupola
      type: feature
    - effects:
        - effect: Any [restrained](../../../condition/restrained.md) or [slowed](../../../condition/slowed.md) creature who comes [adjacent](../../../rule/combat/adjacent.md) to the war walker is automatically [restrained](../../../condition/restrained.md) (save ends) and takes a bane on power rolls. A creature [restrained](../../../condition/restrained.md) this way moves with the war walker.
      feature_type: trait
      icon: ⭐️
      name: Mobile Prison Harness
      type: feature
free_strike: 4
intuition: 0
keywords:
    - Dwarf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/servitor-war-walker
    source: mcdm.monsters.v1
might: 2
movement: Climb
name: Servitor War Walker
organization: Elite
presence: -2
reason: -2
role: Mount
size: "3"
speed: 8
stability: 2
stamina: "60"
type: statblock
```
