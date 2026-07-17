---
agility: 2
ev: "6"
file_basename: dwarf-gunner
file_dpath: monster/dwarf/statblock
free_strike: 4
intuition: 1
item_id: dwarf-gunner
item_name: Dwarf Gunner
keywords:
    - Dwarf
    - Humanoid
level: 1
might: 0
name: Dwarf Gunner
organization: Platoon
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-gunner
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "26"
type: statblock
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage; [push](../../../movement/forced-movement.md) 1
          tier2: 9 damage; [push](../../../movement/forced-movement.md) 3
          tier3: 12 damage; [push](../../../movement/forced-movement.md) 5
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Portable Ballista
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** The gunner makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target, and the [prone](../../../condition/prone.md), [restrained](../../../condition/restrained.md), and [slowed](../../../condition/slowed.md) conditions on the target end. The target is then [restrained](../../../condition/restrained.md) (save ends).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Weapon
      name: Ensnaring Chains
      target: One prone, restrained, or slowed creature
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever the gunner deals rolled damage to a target, one creature or object adjacent to the target takes 3 damage.
      feature_type: trait
      icon: ⭐️
      name: Split Shot
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Dwarf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-gunner
    source: mcdm.monsters.v1
might: 0
name: Dwarf Gunner
organization: Platoon
presence: 0
reason: 0
role: Artillery
size: 1M
speed: 5
stability: 1
stamina: "26"
type: statblock
```
