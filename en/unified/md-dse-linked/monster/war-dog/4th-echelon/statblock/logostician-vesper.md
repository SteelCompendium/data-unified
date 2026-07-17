---
agility: 1
ev: "48"
file_basename: logostician-vesper
file_dpath: monster/war-dog/4th-echelon/statblock
free_strike: 10
intuition: 4
item_id: logostician-vesper
item_name: Logostician Vesper
keywords:
    - Soulless
    - War Dog
level: 10
might: 2
name: Logostician Vesper
organization: Elite
presence: 1
reason: 5
role: Controller
scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/logostician-vesper
size: "2"
source: mcdm.monsters.v1
speed: 10
stability: 3
stamina: "253"
type: statblock
---

```ds-sb
agility: 1
ev: "48"
features:
    - ability_type: Signature Ability
      distance: 5 x 3 line within 15
      effects:
        - roll: Power Roll + 5
          tier1: 8 damage
          tier2: 12 damage; I < 4 [slowed](../../../../condition/slowed.md) (save ends)
          tier3: 15 damage; I < 5 [slowed](../../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Portal to the Firing Line
      target: Each creature and object in the area
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 cube within 15
      effects:
        - roll: Power Roll + 5
          tier1: 8 fire damage
          tier2: 12 fire damage
          tier3: 15 fire damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Portal to the Mantle
      target: Each creature and object in the area
      type: feature
      usage: Main action
    - distance: 5 cube within 15
      effects:
        - roll: Power Roll + 5
          tier1: A < 4 [pull](../../../../movement/forced-movement.md) 3 toward the center of the area
          tier2: A < 5 [pull](../../../../movement/forced-movement.md) 3 toward the center of the area
          tier3: '[Pull](../../../../movement/forced-movement.md) 3 toward the center of the area'
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Portal to the Void
      target: Each creature and object in the area
      type: feature
      usage: Maneuver
    - distance: Ranged 3
      effects:
        - effect: |-
            **Trigger:** The target moves within distance of Vesper.
            **Effect:** The target is dropped through a portal, which [teleports](../../../../movement/teleport.md) them up to 7 squares above a space within 15 squares.
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Portal to the Sky
      target: One enemy
      type: feature
      usage: Triggered action
    - effects:
        - effect: Each ally who starts their turn within 10 squares of Vesper can [teleport](../../../../movement/teleport.md) whenever they willingly move until the end of their turn. Whenever an affected ally [teleports](../../../../movement/teleport.md), they deal an extra 5 damage on their next strike.
      feature_type: trait
      icon: ⭐️
      name: Living Logistics Network
      type: feature
    - effects:
        - effect: When Vesper is reduced to 0 [Stamina](../../../../rule/health/stamina.md), they move up to their speed and then explode, dealing 4d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object. Any enemy who takes more than 14 damage this way vertically [slides](../../../../movement/forced-movement.md) 5 squares.
      feature_type: trait
      icon: ⭐️
      name: Crash and Burn
      type: feature
free_strike: 10
intuition: 4
keywords:
    - Soulless
    - War Dog
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.4th-echelon.statblock/logostician-vesper
    source: mcdm.monsters.v1
might: 2
name: Logostician Vesper
organization: Elite
presence: 1
reason: 5
role: Controller
size: "2"
speed: 10
stability: 3
stamina: "253"
type: statblock
```
