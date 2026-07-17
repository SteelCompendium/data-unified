---
agility: 2
ev: "6"
file_basename: high-elf-zephyr
file_dpath: monster/elf-high/statblock
free_strike: 3
intuition: 0
item_id: high-elf-zephyr
item_name: High Elf Zephyr
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
might: 0
name: High Elf Zephyr
organization: Platoon
presence: 1
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-zephyr
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage
          tier2: 7 damage
          tier3: 9 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Sweeping Blade
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The zephyr [flies](../../../movement/fly.md) up to their speed. If they don''t end this movment on solid ground, they are [prone](../../../condition/prone.md).'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Windwalk
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: The zephyr doesn't provoke opportunity attacks by moving.
      feature_type: trait
      icon: ⭐️
      name: Like the Wind
      type: feature
    - effects:
        - effect: At the start of each of their turns, the zephyr can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Otherworldly Grace
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-zephyr
    source: mcdm.monsters.v1
might: 0
name: High Elf Zephyr
organization: Platoon
presence: 1
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "30"
type: statblock
```
