---
agility: 0
ev: "4"
file_basename: war-dog-amalgamite
file_dpath: monster/war-dog/1st-echelon/statblock
free_strike: 3
intuition: 0
item_id: war-dog-amalgamite
item_name: War Dog Amalgamite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 2
might: 2
name: War Dog Amalgamite
organization: Horde
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-amalgamite
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "25"
type: statblock
---

```ds-sb
agility: 0
ev: "4"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage
          tier2: 5 damage; A < 1 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
          tier3: 6 damage; A < 2 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Several Arms
      target: Two creatures or objects
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
        - effect: When the amalgamite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 1d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.1st-echelon.statblock/war-dog-amalgamite
    source: mcdm.monsters.v1
might: 2
name: War Dog Amalgamite
organization: Horde
presence: 0
reason: 0
role: Brute
size: "2"
speed: 5
stability: 2
stamina: "25"
type: statblock
```
