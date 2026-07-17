---
agility: 2
ev: "10"
file_basename: wode-elf-gweiadur
file_dpath: monster/elf-wode/statblock
free_strike: 5
intuition: 1
item_id: wode-elf-gweiadur
item_name: Wode Elf Gweiadur
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 3
might: 0
movement: Climb
name: Wode Elf Gweiadur
organization: Platoon
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-gweiadur
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "40"
type: statblock
---

```ds-sb
agility: 2
ev: "10"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 11 damage
          tier3: 14 damage; A < 2 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Snare Bow
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage; R < 0 the target is marked (save ends)
          tier2: 6 damage; R < 1 [slowed](../../../condition/slowed.md) and the target is marked (save ends)
          tier3: 9 damage; R < 2 [slowed](../../../condition/slowed.md) and the target is marked (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: You Activated My Trap!
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: Abilities targeting the gweiadur that would take a bane from cover or concealment have a double bane instead.
      feature_type: trait
      icon: ⭐️
      name: Masking Glamor
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-gweiadur
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Wode Elf Gweiadur
organization: Platoon
presence: 0
reason: 0
role: Artillery
size: 1M
speed: 7
stability: 0
stamina: "40"
type: statblock
```
