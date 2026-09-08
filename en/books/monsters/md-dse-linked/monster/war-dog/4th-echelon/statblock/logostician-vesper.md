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
        - effect: This ability targets only non-[prone](../../../../condition/prone.md) creatures.
          name: Special
          roll: Power Roll + 5
          tier1: 8 damage
          tier2: 12 damage; I < 4 [slowed](../../../../condition/slowed.md) (save ends)
          tier3: 15 damage; I < 5 [slowed](../../../../condition/slowed.md) (save ends)
        - effect: A target creature can choose to drop [prone](../../../../condition/prone.md), in which case the ability takes a bane against them.
          name: Effect
        - cost: 2 Malice
          effect: The area remains active until Vesper is reduced to 0 [Stamina](../../../../rule/health/stamina.md) or until the end of the encounter. Any non-[prone](../../../../condition/prone.md) enemy who enters the area for the first time in a round or starts their turn there takes 15 damage, or 7 damage if they choose to fall [prone](../../../../condition/prone.md).
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
        - effect: The area is [difficult terrain](../../../../movement/difficult-terrain.md). Any creature who enters the area for the first time in a round or starts their turn there takes 10 fir damage. Until the end of the encounter, the size of the area increases by 1 at the start of each round.
          name: Effect
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
        - effect: A portal appears at the center of the area. Any creature at the center of the area when this ability is used or who is pulled into the center for the first time in a round takes 10 sonic damage.
          name: Effect
        - cost: 2 Malice
          effect: The area remains active and deals its damage until Vesper is reduced to 0 [Stamina](../../../../rule/health/stamina.md) or until the end of the encounter. Any creature who enters the area and has A < 4 is [pulled](../../../../movement/forced-movement.md) 3 squares toward the center of the area. Any creature who starts their turn in the area and has M < 4 is [slowed](../../../../condition/slowed.md) until the end of their turn.
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
        - effect: The target is dropped through a portal, which [teleports](../../../../movement/teleport.md) them up to 7 squares above a space within 15 squares.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Ranged
      name: Portal to the Sky
      target: One enemy
      trigger: The target moves within distance of Vesper.
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
