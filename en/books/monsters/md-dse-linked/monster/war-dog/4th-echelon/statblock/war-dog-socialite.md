---
agility: 2
ev: 12 for four minions
file_basename: war-dog-socialite
file_dpath: monster/war-dog/4th-echelon/statblock
free_strike: 4
immunities:
    - Psychic 10
intuition: 3
item_id: war-dog-socialite
item_name: War Dog Socialite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
might: 2
name: War Dog Socialite
organization: Minion
presence: 5
reason: 4
role: Hexer
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/war-dog-socialite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "14"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 2
ev: 12 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 5
          tier1: The target makes a [free strike](../../../../feature/common/main-actions/free-strike.md) (tier 1 result) against themself
          tier2: The target makes a [free strike](../../../../feature/common/main-actions/free-strike.md) (tier 2 result) against themself
          tier3: The target makes a [free strike](../../../../feature/common/main-actions/free-strike.md) (tier 3 result) against themself
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Call to Self-Sabotage
      target: One creature per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the socialite is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 4
immunities:
    - Psychic 10
intuition: 3
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/war-dog-socialite
    source: mcdm.monsters.v1
might: 2
name: War Dog Socialite
organization: Minion
presence: 5
reason: 4
role: Hexer
size: 1M
speed: 5
stability: 0
stamina: "14"
type: statblock
with_captain: Gain an edge on strikes
```
