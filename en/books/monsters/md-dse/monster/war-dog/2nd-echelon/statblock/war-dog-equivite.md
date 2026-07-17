---
agility: 3
ev: "6"
file_basename: war-dog-equivite
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 3
intuition: -2
item_id: war-dog-equivite
item_name: War Dog Equivite
keywords:
    - Soulless
    - War Dog
level: 4
might: 3
name: War Dog Equivite
organization: Horde
presence: 0
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-equivite
size: "2"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "53"
type: statblock
---

```ds-sb
agility: 3
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 6 damage
          tier2: 8 damage
          tier3: 10 damage; I < 3 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Fuse-Iron Lance
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Special; see below
      effects:
        - roll: Power Roll + 3
          tier1: 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
          tier2: 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
          tier3: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Weapon
      name: Blazing Charge
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the equivite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 3
intuition: -2
keywords:
    - Soulless
    - War Dog
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-equivite
    source: mcdm.monsters.v1
might: 3
name: War Dog Equivite
organization: Horde
presence: 0
reason: -1
role: Brute
size: "2"
speed: 8
stability: 2
stamina: "53"
type: statblock
```
