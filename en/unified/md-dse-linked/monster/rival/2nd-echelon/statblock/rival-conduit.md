---
agility: 0
ev: "28"
file_basename: rival-conduit
file_dpath: monster/rival/2nd-echelon/statblock
free_strike: 6
intuition: 3
item_id: rival-conduit
item_name: Rival Conduit
keywords:
    - Humanoid
    - Rival
level: 5
might: 2
name: Rival Conduit
organization: Elite
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-conduit
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "140"
type: statblock
---

```ds-sb
agility: 0
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 9 holy damage; vertical [slide](../../../../movement/forced-movement.md) 1
          tier2: 14 holy damage; vertical [slide](../../../../movement/forced-movement.md) 2
          tier3: 17 holy damage; vertical [slide](../../../../movement/forced-movement.md) 3
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Raging Tempest
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Each target has a double edge on their next [strike](../../../../rule/combat/strike.md).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Imbue with Power
      target: Self and five allies
      type: feature
      usage: Maneuver
    - effects:
        - effect: '[Strikes](../../../../rule/combat/strike.md) made against allies [adjacent](../../../../rule/combat/adjacent.md) to the conduit take a bane.'
      feature_type: trait
      icon: ⭐️
      name: Stalwart Guardian
      type: feature
    - effects:
        - effect: At the start of an encounter, the conduit chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the conduit and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 6
intuition: 3
keywords:
    - Humanoid
    - Rival
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-conduit
    source: mcdm.monsters.v1
might: 2
name: Rival Conduit
organization: Elite
presence: 1
reason: 0
role: Support
size: 1M
speed: 5
stability: 1
stamina: "140"
type: statblock
```
