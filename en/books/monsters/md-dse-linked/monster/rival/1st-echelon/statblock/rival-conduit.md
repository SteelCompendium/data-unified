---
agility: 0
ev: "16"
file_basename: rival-conduit
file_dpath: monster/rival/1st-echelon/statblock
free_strike: 5
intuition: 2
item_id: rival-conduit
item_name: Rival Conduit
keywords:
    - Humanoid
    - Rival
level: 2
might: 1
name: Rival Conduit
organization: Elite
presence: 0
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-conduit
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "80"
type: statblock
---

```ds-sb
agility: 0
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 7 holy damage
          tier2: 10 holy damage
          tier3: 13 holy damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Thunder of Heavens
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Each target gains an edge on their next [strike](../../../../rule/combat/strike.md).'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Imbue with Might
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
free_strike: 5
intuition: 2
keywords:
    - Humanoid
    - Rival
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-conduit
    source: mcdm.monsters.v1
might: 1
name: Rival Conduit
organization: Elite
presence: 0
reason: 0
role: Support
size: 1M
speed: 5
stability: 1
stamina: "80"
type: statblock
```
