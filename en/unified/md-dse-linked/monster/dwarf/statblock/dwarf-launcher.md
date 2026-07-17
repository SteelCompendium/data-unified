---
agility: 0
ev: "8"
file_basename: dwarf-launcher
file_dpath: monster/dwarf/statblock
free_strike: 4
intuition: 2
item_id: dwarf-launcher
item_name: Dwarf Launcher
keywords:
    - Dwarf
    - Humanoid
level: 1
might: 1
name: Dwarf Launcher
organization: Platoon
presence: 0
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-launcher
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 3
stamina: "39"
type: statblock
---

```ds-sb
agility: 0
ev: "8"
features:
    - ability_type: Signature Ability
      distance: 3 cube within 5
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage; [push](../../../movement/forced-movement.md) 1
          tier2: 6 damage; [push](../../../movement/forced-movement.md) 3; M < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 8 damage; [push](../../../movement/forced-movement.md) 3; M < 2 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Concussive Grenade
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 cube within 5
      effects:
        - roll: Power Roll + 2
          tier1: 3 poison damage; I < 0 [dazed](../../../condition/dazed.md) (save ends)
          tier2: 6 poison damage; I < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier3: 8 poison damage; I < 2 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Ranged
        - Weapon
      name: Sleep Grenade
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: The launcher ignores concealment and cover, and doesn't need line of effect to use their abilities as long as a size 1 opening exists between the dwarf and the target.
      feature_type: trait
      icon: ⭐️
      name: Indirect Fire
      type: feature
free_strike: 4
intuition: 2
keywords:
    - Dwarf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-launcher
    source: mcdm.monsters.v1
might: 1
name: Dwarf Launcher
organization: Platoon
presence: 0
reason: 0
role: Hexer
size: 1M
speed: 5
stability: 3
stamina: "39"
type: statblock
```
