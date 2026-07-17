---
agility: 1
ev: 3 for 4 minions
file_basename: dwarf-driver
file_dpath: monster/dwarf/statblock
free_strike: 1
intuition: 0
item_id: dwarf-driver
item_name: Dwarf Driver
keywords:
    - Dwarf
    - Humanoid
level: 1
might: 2
name: Dwarf Driver
organization: Minion
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-driver
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "6"
type: statblock
with_captain: +2 bonus to Stamina
---

```ds-sb
agility: 1
ev: 3 for 4 minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage; [push](../../../movement/forced-movement.md) 1
          tier2: 2 damage; [push](../../../movement/forced-movement.md) 2
          tier3: 3 damage; [push](../../../movement/forced-movement.md) 4
      feature_type: ability
      icon: ⚔️
      keywords:
        - Charge
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Handaxes
      target: One creature or object per minion
      type: feature
      usage: Main action
free_strike: 1
intuition: 0
keywords:
    - Dwarf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-driver
    source: mcdm.monsters.v1
might: 2
name: Dwarf Driver
organization: Minion
presence: 0
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 1
stamina: "6"
type: statblock
with_captain: +2 bonus to Stamina
```
