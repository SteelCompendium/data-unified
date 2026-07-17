---
agility: 2
ev: "8"
file_basename: wode-elf-chirurgeon
file_dpath: monster/elf-wode/statblock
free_strike: 4
intuition: 0
item_id: wode-elf-chirurgeon
item_name: Wode Elf Chirurgeon
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 2
might: 1
movement: Climb
name: Wode Elf Chirurgeon
organization: Platoon
presence: 1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-chirurgeon
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "40"
type: statblock
---

```ds-sb
agility: 2
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 9 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
          tier3: 12 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
      feature_type: ability
      icon: ⚔️
      keywords:
        - Charge
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Wild Ax
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 5
      effects:
        - effect: '**Effect:** Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 10 squares to a space that has cover or concealment.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: The Wode Protects Us
      target: Self and three allies
      type: feature
      usage: Maneuver
    - effects:
        - effect: Abilities targeting the chirurgeon that would take a bane from cover or concealment have a double bane instead.
      feature_type: trait
      icon: ⭐️
      name: Masking Glamor
      type: feature
free_strike: 4
intuition: 0
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-chirurgeon
    source: mcdm.monsters.v1
might: 1
movement: Climb
name: Wode Elf Chirurgeon
organization: Platoon
presence: 1
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "40"
type: statblock
```
