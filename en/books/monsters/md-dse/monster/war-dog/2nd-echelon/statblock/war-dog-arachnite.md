---
agility: 3
ev: "8"
file_basename: war-dog-arachnite
file_dpath: monster/war-dog/2nd-echelon/statblock
free_strike: 4
immunities:
    - Psychic 6
intuition: 2
item_id: war-dog-arachnite
item_name: War Dog Arachnite
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 6
might: 0
movement: Climb
name: War Dog Arachnite
organization: Horde
presence: 1
reason: 2
role: Artillery
scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-arachnite
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "35"
type: statblock
---

```ds-sb
agility: 3
ev: "8"
features:
    - ability_type: Signature Ability
      distance: Ranged 15
      effects:
        - roll: Power Roll + 3
          tier1: 7 damage
          tier2: 9 damage
          tier3: 11 damage; A < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Longarm Shrikegun
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 2 cube within 10
      effects:
        - effect: '**Effect:** The area is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) until the end of the encounter.'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
      name: Web Vial
      target: Special
      type: feature
      usage: Maneuver
    - effects:
        - effect: At the start of each of their turns, the arachnite automatically knows the location of each hidden creature within 10 squares of them.
      feature_type: trait
      icon: ⭐️
      name: Eight-Eyed Sight
      type: feature
    - effects:
        - effect: When the arachnite is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their loyalty collar explodes, dealing 2d6 damage to each [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 4
immunities:
    - Psychic 6
intuition: 2
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 6
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.2nd-echelon.statblock/war-dog-arachnite
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: War Dog Arachnite
organization: Horde
presence: 1
reason: 2
role: Artillery
size: 1L
speed: 5
stability: 0
stamina: "35"
type: statblock
```
