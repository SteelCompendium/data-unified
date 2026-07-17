---
agility: 1
ev: "48"
file_basename: rival-conduit
file_dpath: monster/rival/4th-echelon/statblock
free_strike: 10
intuition: 5
item_id: rival-conduit
item_name: Rival Conduit
keywords:
    - Humanoid
    - Rival
level: 10
might: 4
name: Rival Conduit
organization: Elite
presence: 3
reason: 1
role: Support
scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-conduit
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "240"
type: statblock
---

```ds-sb
agility: 1
ev: "48"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 15 damage; vertical [slide](../../../../movement/forced-movement.md) 3; M < 3 5 lightning damage
          tier2: 20 damage; vertical [slide](../../../../movement/forced-movement.md) 4; M < 4 7 lightning damage
          tier3: 24 damage; vertical [slide](../../../../movement/forced-movement.md) 5; M < 5 9 lightning damage
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Sunder the Very Skies
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** Each target has a double edge on their next [strike](../../../../rule/combat/strike.md), and that strike deals an extra 10 holy damage. Additionally, they can vertical [slide](../../../../movement/forced-movement.md) each creature targeted by the strike up to 2 squares.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Empyrean Boon
      target: Self and five allies
      type: feature
      usage: Maneuver
    - effects:
        - effect: Damage dealt to any ally [adjacent](../../../../rule/combat/adjacent.md) to the conduit is halved.
      feature_type: trait
      icon: ⭐️
      name: Unwavering Defender
      type: feature
    - effects:
        - effect: At the start of an encounter, the conduit chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the conduit and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 10
intuition: 5
keywords:
    - Humanoid
    - Rival
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.rival.4th-echelon.statblock/rival-conduit
    source: mcdm.monsters.v1
might: 4
name: Rival Conduit
organization: Elite
presence: 3
reason: 1
role: Support
size: 1M
speed: 5
stability: 1
stamina: "240"
type: statblock
```
