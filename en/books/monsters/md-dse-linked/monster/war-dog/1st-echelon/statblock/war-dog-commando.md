---
agility: 2
ev: 3 for four minions
file_basename: war-dog-commando
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 2
intuition: 0
item_id: war-dog-commando
item_name: War Dog Commando
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
might: 0
name: War Dog Commando
organization: Minion
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-commando
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "4"
type: statblock
with_captain: +1 damage bonus to strikes
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage
          tier3: 5 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Daggers
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the commando is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 1d3 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-commando
    source: mcdm.monsters.v1
might: 0
name: War Dog Commando
organization: Minion
presence: 0
reason: 0
role: Ambusher
size: 1M
speed: 5
stability: 0
stamina: "4"
type: statblock
with_captain: +1 damage bonus to strikes
```
