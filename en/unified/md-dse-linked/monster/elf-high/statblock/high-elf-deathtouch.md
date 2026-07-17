---
agility: 0
ev: "8"
file_basename: high-elf-deathtouch
file_dpath: monster/elf-high/statblock
free_strike: 5
intuition: 0
item_id: high-elf-deathtouch
item_name: High Elf Deathtouch
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 2
might: 2
name: High Elf Deathtouch
organization: Platoon
presence: 1
reason: 1
role: Artillery
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-deathtouch
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 0
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 10 damage
          tier3: 13 damage; R < 1 [bleeding](../../../condition/bleeding.md) (save ends); I < 1 [frightened](../../../condition/frightened.md) (save ends); P < 1 [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Heartpiercer
      target: One creature
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - effect: '**Effect:** The target has a +5 bonus to speed and automatically obtains a tier 3 outcome on power rolls. They can still roll to determine if they score a critical hit. At the end of their next turn, the target immediately dies.'
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
      name: Kiss of Death
      target: One willing ally
      type: feature
      usage: Maneuver
    - effects:
        - effect: At the start of each of their turns, the deathtouch can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Otherworldly Grace
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-deathtouch
    source: mcdm.monsters.v1
might: 2
name: High Elf Deathtouch
organization: Platoon
presence: 1
reason: 1
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "30"
type: statblock
```
