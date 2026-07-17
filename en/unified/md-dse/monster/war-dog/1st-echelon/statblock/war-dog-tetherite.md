---
agility: 0
ev: 3 for four minions
file_basename: war-dog-tetherite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 2
intuition: 0
item_id: war-dog-tetherite
item_name: War Dog Tetherite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
might: 2
name: War Dog Tetherite
organization: Minion
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-tetherite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "5"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 0
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage
          tier2: 4 damage
          tier3: 5 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Banded Dagger
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: A captain attached to a tetherite squad has their stability increased by the number of tetherites within 2 squares of them.
      feature_type: trait
      icon: ⭐️
      name: Tethered
      type: feature
    - effects:
        - effect: When the tetherite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d3 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
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
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-tetherite
    source: mcdm.monsters.v1
might: 2
name: War Dog Tetherite
organization: Minion
presence: 0
reason: 0
role: Brute
size: 1M
speed: 5
stability: 1
stamina: "5"
type: statblock
with_captain: Gain an edge on strikes
```
