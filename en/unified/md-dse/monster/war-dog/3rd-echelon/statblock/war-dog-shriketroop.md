---
agility: 4
ev: 9 for four minions
file_basename: war-dog-shriketroop
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 4
intuition: 1
item_id: war-dog-shriketroop
item_name: War Dog Shriketroop
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 7
might: 1
name: War Dog Shriketroop
organization: Minion
presence: 1
reason: 3
role: Artillery
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-shriketroop
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "10"
type: statblock
with_captain: Gain an edge on strikes
---

```ds-sb
agility: 4
ev: 9 for four minions
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 4 damage
          tier2: 7 damage
          tier3: 8 damage; I < 3 the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of all shriketroops (EoT)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Canis Shrikegun
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: When the shriketroop is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 4
intuition: 1
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-shriketroop
    source: mcdm.monsters.v1
might: 1
name: War Dog Shriketroop
organization: Minion
presence: 1
reason: 3
role: Artillery
size: 1M
speed: 5
stability: 0
stamina: "10"
type: statblock
with_captain: Gain an edge on strikes
```
