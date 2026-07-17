---
agility: 1
ev: "5"
file_basename: war-dog-pestilite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 2
immunities:
    - Poison 3
intuition: 0
item_id: war-dog-pestilite
item_name: War Dog Pestilite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 3
might: 0
name: War Dog Pestilite
organization: Horde
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-pestilite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "20"
type: statblock
---

```ds-sb
agility: 1
ev: "5"
features:
    - ability_type: Signature Ability
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 2
          tier1: 2 poison damage; I < 0 [frightened](../../../../condition/frightened.md) (save ends)
          tier2: 4 poison damage; I < 1 [frightened](../../../../condition/frightened.md) (save ends)
          tier3: 5 poison damage; I < 2 [frightened](../../../../condition/frightened.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Plaguecaster
      target: Each creature in the area
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Posthumous Promotion
      target: One war dog
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the pestilite is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 2
immunities:
    - Poison 3
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-pestilite
    source: mcdm.monsters.v1
might: 0
name: War Dog Pestilite
organization: Horde
presence: 2
reason: 0
role: Controller
size: 1M
speed: 5
stability: 0
stamina: "20"
type: statblock
```
