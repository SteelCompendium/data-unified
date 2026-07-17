---
agility: 4
ev: 9 for four minions
file_basename: faded-echo-spirit
file_dpath: monster/undead/3rd-echelon/statblock
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
item_id: faded-echo-spirit
item_name: Faded Echo Spirit
keywords:
    - Undead
level: 7
might: -3
movement: Fly, hover
name: Faded Echo Spirit
organization: Minion
presence: -3
reason: -5
role: Hexer
scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/faded-echo-spirit
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "10"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 4
ev: 9 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 3 corruption damage
          tier2: 6 corruption damage; P < 3 [weakened](../../../../condition/weakened.md)
          tier3: 7 corruption damage; P < 4 [weakened](../../../../condition/weakened.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Hollow Grasp
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: The spirit can move through creatures and objects at their usual speed, but can't end their turn inside a creature or object. The first time in a round that the spirit moves through a creature, that creature takes 4 corruption damage. The spirit doesn't take damage from being [force moved](../../../../movement/forced-movement.md) into objects.
      feature_type: trait
      icon: ⭐️
      name: Corruptive Phasing
      type: feature
free_strike: 3
immunities:
    - Corruption 7
    - poison 7
intuition: 1
keywords:
    - Undead
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.undead.3rd-echelon.statblock/faded-echo-spirit
    source: mcdm.monsters.v1
might: -3
movement: Fly, hover
name: Faded Echo Spirit
organization: Minion
presence: -3
reason: -5
role: Hexer
size: 1M
speed: 5
stability: 1
stamina: "10"
type: statblock
with_captain: Gain an edge on strikes
```
