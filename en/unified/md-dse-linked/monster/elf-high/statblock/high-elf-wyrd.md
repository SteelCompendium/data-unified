---
agility: 1
ev: "10"
file_basename: high-elf-wyrd
file_dpath: monster/elf-high/statblock
free_strike: 5
immunities:
    - Psychic 5
intuition: -1
item_id: high-elf-wyrd
item_name: High Elf Wyrd
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 3
might: 0
name: High Elf Wyrd
organization: Platoon
presence: 2
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-wyrd
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "40"
type: statblock
---

```ds-sb
agility: 1
ev: "10"
features:
    - ability_type: Signature Ability
      distance: 1 cube within 5
      effects:
        - roll: Power Roll + 2
          tier1: Vertical push 3
          tier2: Vertical push 5
          tier3: Vertical push 6
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Twystrd
      target: Each enemy in the area
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 5
      effects:
        - effect: '**Effect:** The wyrd summons two elemental motes or two soot crows into unoccupied spaces within distance.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      name: Summon Elemental
      target: Special
      type: feature
      usage: Maneuver
    - cost: 2 Malice
      distance: 8 wall within 8
      effects:
        - effect: '**Effect:** The wyrd shapes the land in the area as if it were loose clay, either raising the ground or pushing it down to create a trench. Any creature in the area moves with the terrain to its new higher elevation, or falls if the ground is lowered beneath them.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Wyrd Warp
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: At the start of each of their turns, the wyrd can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Otherworldly Grace
      type: feature
free_strike: 5
immunities:
    - Psychic 5
intuition: -1
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-wyrd
    source: mcdm.monsters.v1
might: 0
name: High Elf Wyrd
organization: Platoon
presence: 2
reason: 2
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "40"
type: statblock
```
