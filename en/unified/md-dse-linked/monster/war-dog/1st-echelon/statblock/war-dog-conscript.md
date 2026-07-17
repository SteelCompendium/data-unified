---
agility: 0
ev: 3 for four minions
file_basename: war-dog-conscript
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 1
intuition: 0
item_id: war-dog-conscript
item_name: War Dog Conscript
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
might: 2
name: War Dog Conscript
organization: Minion
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-conscript
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: +1 damage bonus to strikes
---

```ds-sb
agility: 0
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 1 damage
          tier2: 2 damage
          tier3: 3 damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Charge
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Blade
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the conscript is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 1d3 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-conscript
    source: mcdm.monsters.v1
might: 2
name: War Dog Conscript
organization: Minion
presence: 0
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "4"
type: statblock
with_captain: +1 damage bonus to strikes
```
