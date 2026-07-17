---
agility: 2
ev: "3"
file_basename: war-dog-teletalite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 2
intuition: 0
item_id: war-dog-teletalite
item_name: War Dog Teletalite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 1
might: 0
movement: Teleport
name: War Dog Teletalite
organization: Horde
presence: 0
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-teletalite
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 6 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 7 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
      feature_type: ability
      icon: ⚔️
      keywords:
        - Melee
        - Ranged
        - Strike
        - Weapon
      name: Corrupted Ash Daggers
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
    - cost: 1 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The teletalite can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares and gains an edge on strikes until the end of their turn.'
      feature_type: ability
      icon: "\U0001F464"
      keywords:
        - Magic
      name: Corrupted Ash Teleport
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the teletalite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
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
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-teletalite
    source: mcdm.monsters.v1
might: 0
movement: Teleport
name: War Dog Teletalite
organization: Horde
presence: 0
reason: 0
role: Ambusher
size: 1M
speed: 5
stability: 0
stamina: "15"
type: statblock
```
