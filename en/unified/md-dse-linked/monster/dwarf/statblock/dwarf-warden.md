---
agility: 0
ev: "8"
file_basename: dwarf-warden
file_dpath: monster/dwarf/statblock
free_strike: 5
intuition: 1
item_id: dwarf-warden
item_name: Dwarf Warden
keywords:
    - Dwarf
    - Humanoid
level: 2
might: 2
name: Dwarf Warden
organization: Platoon
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-warden
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "59"
type: statblock
---

```ds-sb
agility: 0
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [push](../../../movement/forced-movement.md) 1
          tier2: 10 damage; [push](../../../movement/forced-movement.md) 3
          tier3: 13 damage; [push](../../../movement/forced-movement.md) 5; M < 2 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Concussive Maul
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 3 cube within 1
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; [push](../../../movement/forced-movement.md) 2; A < 0 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 8 damage; [push](../../../movement/forced-movement.md) 2; A < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 11 damage; [push](../../../movement/forced-movement.md) 2; A < 2 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Concussive Shockwave
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever the warden moves, they can carry an [adjacent](../../../rule/combat/adjacent.md) [restrained](../../../condition/restrained.md) enemy as if the enemy were [grabbed](../../../condition/grabbed.md) by them.
      feature_type: trait
      icon: ⭐️
      name: Escort the Prisoners
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Dwarf
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-warden
    source: mcdm.monsters.v1
might: 2
name: Dwarf Warden
organization: Platoon
presence: 0
reason: 0
role: Brute
size: 1M
speed: 5
stability: 3
stamina: "59"
type: statblock
```
