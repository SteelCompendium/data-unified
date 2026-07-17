---
agility: 2
ev: 3 for four minions
file_basename: high-elf-quiver
file_dpath: monster/elf-high/statblock
free_strike: 2
intuition: 0
item_id: high-elf-quiver
item_name: High Elf Quiver
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
might: 0
name: High Elf Quiver
organization: Minion
presence: 0
reason: 1
role: Artillery
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-quiver
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage
          tier3: 5 damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Heavy Arrow
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: At the start of each of their turns, the quiver can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Otherworldly Grace
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-quiver
    source: mcdm.monsters.v1
might: 0
name: High Elf Quiver
organization: Minion
presence: 0
reason: 1
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
```
