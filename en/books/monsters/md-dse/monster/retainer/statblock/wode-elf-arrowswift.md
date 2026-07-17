---
agility: 2
ev: '-'
file_basename: wode-elf-arrowswift
file_dpath: monster/retainer/statblock
free_strike: 2
intuition: 1
item_id: wode-elf-arrowswift
item_name: Wode Elf Arrowswift
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
might: 0
name: Wode Elf Arrowswift
organization: Retainer
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.retainer.statblock/wode-elf-arrowswift
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "21"
type: statblock
---

```ds-sb
agility: 2
ev: '-'
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + highest characteristic
          tier1: 4 damage
          tier2: 7 damage
          tier3: 10 damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Longshot
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: Abilities targeting the arrowswift that would take a bane from cover or concealment have a double bane instead.
      feature_type: trait
      icon: ⭐️
      name: Masking Glamor
      type: feature
free_strike: 2
intuition: 1
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.retainer.statblock/wode-elf-arrowswift
    source: mcdm.monsters.v1
might: 0
name: Wode Elf Arrowswift
organization: Retainer
presence: 0
reason: 0
role: Artillery
size: 1M
speed: 7
stability: 1
stamina: "21"
type: statblock
```
