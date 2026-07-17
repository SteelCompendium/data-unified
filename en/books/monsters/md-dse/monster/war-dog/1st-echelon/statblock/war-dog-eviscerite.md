---
agility: 2
ev: "3"
file_basename: war-dog-eviscerite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 1
intuition: 0
item_id: war-dog-eviscerite
item_name: War Dog Eviscerite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
might: 1
name: War Dog Eviscerite
organization: Horde
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-eviscerite
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage
          tier2: 4 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier3: 5 damage; [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Chainsaw Whip
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** If the target has a loyalty collar, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).'
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
        - effect: When the eviscerite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
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
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-eviscerite
    source: mcdm.monsters.v1
might: 1
name: War Dog Eviscerite
organization: Horde
presence: 0
reason: 0
role: Harrier
size: 1M
speed: 7
stability: 0
stamina: "15"
type: statblock
```
