---
agility: 3
ev: 12 for four minions
file_basename: wraith-skulker
file_dpath: monster/undead/4th-echelon/statblock
free_strike: 4
immunities:
    - Corruption 10
    - poison 10
intuition: 1
item_id: wraith-skulker
item_name: Wraith Skulker
keywords:
    - Undead
level: 10
might: -2
movement: Fly, hover
name: Wraith Skulker
organization: Minion
presence: 5
reason: 1
role: Harrier
scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/wraith-skulker
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 1
stamina: "15"
type: statblock
with_captain: +3 bonus to speed
---

```ds-sb
agility: 3
ev: 12 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 5
          tier1: 4 cold damage; the wraith can [shift](../../../../movement/shifting.md) 1 square
          tier2: 7 cold damage; the wraith [shifts](../../../../movement/shifting.md) up to 2 square
          tier3: 9 cold damage; P < 5 [slowed](../../../../condition/slowed.md) (save ends); the wraith [shifts](../../../../movement/shifting.md) up to 3 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Draining Rake
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The wraith can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. The first time in a round that the wraith moves through a creature, that creature takes 5 corruption damage. The wraith doesn't take damage from being [force moved](../../../../movement/forced-movement.md) into objects.
      feature_type: trait
      icon: ⭐️
      name: Corruptive Phasing
      type: feature
free_strike: 4
immunities:
    - Corruption 10
    - poison 10
intuition: 1
keywords:
    - Undead
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.undead.4th-echelon.statblock/wraith-skulker
    source: mcdm.monsters.v1
might: -2
movement: Fly, hover
name: Wraith Skulker
organization: Minion
presence: 5
reason: 1
role: Harrier
size: 1M
speed: 7
stability: 1
stamina: "15"
type: statblock
with_captain: +3 bonus to speed
```
