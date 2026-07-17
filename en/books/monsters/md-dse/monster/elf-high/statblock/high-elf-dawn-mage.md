---
agility: 0
ev: 3 for four minions
file_basename: high-elf-dawn-mage
file_dpath: monster/elf-high/statblock
free_strike: 1
intuition: -1
item_id: high-elf-dawn-mage
item_name: High Elf Dawn Mage
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
might: 0
name: High Elf Dawn Mage
organization: Minion
presence: 1
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-dawn-mage
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
---

```ds-sb
agility: 0
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 1 holy damage
          tier2: 2 holy damage
          tier3: 3 holy damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Bright Bolt
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: At the start of each of their turns, the dawn mage can choose one effect on them that can be ended by a saving throw. That effect instead ends at the end of their turn.
      feature_type: trait
      icon: ⭐️
      name: Otherworldly Grace
      type: feature
free_strike: 1
intuition: -1
keywords:
    - Fey
    - High Elf
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.elf-high.statblock/high-elf-dawn-mage
    source: mcdm.monsters.v1
might: 0
name: High Elf Dawn Mage
organization: Minion
presence: 1
reason: 2
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +5 bonus to ranged distance
```
