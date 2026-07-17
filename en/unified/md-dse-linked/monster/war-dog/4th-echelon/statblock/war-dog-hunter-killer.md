---
agility: 5
ev: 12 for four minions
file_basename: war-dog-hunter-killer
file_dpath: monster/war-dog/4th-echelon/statblock
free_strike: 5
intuition: 5
item_id: war-dog-hunter-killer
item_name: War Dog Hunter-Killer
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
might: 1
name: War Dog Hunter-Killer
organization: Minion
presence: 2
reason: 3
role: Artillery
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/war-dog-hunter-killer
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "14"
type: statblock
with_captain: +4 damage bonus to strikes
---

```ds-sb
agility: 5
ev: 12 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 5 damage; [push](../../../../movement/forced-movement.md) 2
          tier2: 8 damage; [push](../../../../movement/forced-movement.md) 3
          tier3: 10 damage; [push](../../../../movement/forced-movement.md) 4
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Fuse-Iron Rocket
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the hunter-killer is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 5
intuition: 5
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/war-dog-hunter-killer
    source: mcdm.monsters.v1
might: 1
name: War Dog Hunter-Killer
organization: Minion
presence: 2
reason: 3
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "14"
type: statblock
with_captain: +4 damage bonus to strikes
```
