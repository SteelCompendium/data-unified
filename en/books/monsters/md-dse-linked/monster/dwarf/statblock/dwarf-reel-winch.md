---
agility: 2
ev: "6"
file_basename: dwarf-reel-winch
file_dpath: monster/dwarf/statblock
free_strike: 3
intuition: 1
item_id: dwarf-reel-winch
item_name: Dwarf Reel Winch
keywords:
    - Dwarf
    - Humanoid
level: 1
might: 0
name: Dwarf Reel Winch
organization: Platoon
presence: 0
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-reel-winch
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "36"
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
          tier1: 5 damage; M < 0 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 7 damage; M < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 9 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Snaring Crossbow
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** The target is [pulled](../../../movement/forced-movement.md) up to 8 squares. A [restrained](../../../condition/restrained.md) or [slowed](../../../condition/slowed.md) target can be pulled an additional 2 squares. A target [restrained](../../../condition/restrained.md) by a dwarf can be force moved by this ability. This forced movement doesn''t end the [restrained](../../../condition/restrained.md) condition unless the Director determines otherwise.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Weapon
      name: Reel Them In
      target: Three creatures
      type: feature
      usage: Maneuver
    - effects:
        - effect: If a target made [slowed](../../../condition/slowed.md) by the reel winch is already [grabbed](../../../condition/grabbed.md) or [slowed](../../../condition/slowed.md), the [grabbed](../../../condition/grabbed.md) and [slowed](../../../condition/slowed.md) conditions end and the target is [restrained](../../../condition/restrained.md) (save ends).
      feature_type: trait
      icon: ⭐️
      name: We Have a Quota!
      type: feature
free_strike: 3
intuition: 1
keywords:
    - Dwarf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-reel-winch
    source: mcdm.monsters.v1
might: 0
name: Dwarf Reel Winch
organization: Platoon
presence: 0
reason: 0
role: Support
size: 1M
speed: 5
stability: 2
stamina: "36"
type: statblock
```
