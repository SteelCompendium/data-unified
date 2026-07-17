---
agility: 2
ev: "36"
file_basename: war-dog-breaker
file_dpath: monster/war-dog/3rd-echelon/statblock
free_strike: 7
intuition: 1
item_id: war-dog-breaker
item_name: War Dog Breaker
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 7
might: 4
name: War Dog Breaker
organization: Elite
presence: 3
reason: 1
role: Brute
scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-breaker
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "200"
type: statblock
---

```ds-sb
agility: 2
ev: "36"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 4
          tier1: 12 damage; [push](../../../../movement/forced-movement.md) 4; [prone](../../../../condition/prone.md)
          tier2: 17 damage; [slide](../../../../movement/forced-movement.md) 4; [prone](../../../../condition/prone.md) or M < 3 [dazed](../../../../condition/dazed.md) (save ends)
          tier3: 21 damage; [slide](../../../../movement/forced-movement.md) 4; [prone](../../../../condition/prone.md); M < 4 [dazed](../../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Pile Bunker Gauntlet
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** Until the start of their next turn, the breaker has a double edge on abilities and is automatically affected by all [potency](../../../../rule/character/potency.md) effect.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Surging Power
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: When the breaker would be reduced to 0 [Stamina](../../../../rule/health/stamina.md), they delay that effect as they end any conditions affecting them and immediately take a turn, regardless of whether they have already taken a turn this round. The breaker's abilities deal an extra 5 damage during this turn, at the end of which they are reduced to 0 [Stamina](../../../../rule/health/stamina.md).
      feature_type: trait
      icon: ⭐️
      name: Breaking Point
      type: feature
    - effects:
        - effect: When the breaker is reduced to 0 [Stamina](../../../../rule/health/stamina.md), their loyalty collar explodes, dealing 3d6 damage to each [adjacent](../../../../rule/combat/adjacent.md) enemy and object.
      feature_type: trait
      icon: ⭐️
      name: Loyalty Collar
      type: feature
free_strike: 7
intuition: 1
keywords:
    - Humanoid
    - Soulless
    - War Dog
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.war-dog.3rd-echelon.statblock/war-dog-breaker
    source: mcdm.monsters.v1
might: 4
name: War Dog Breaker
organization: Elite
presence: 3
reason: 1
role: Brute
size: "2"
speed: 5
stability: 4
stamina: "200"
type: statblock
```
