---
agility: 2
ev: "6"
file_basename: fangling
file_dpath: monster/demon/2nd-echelon/statblock
free_strike: 2
intuition: 0
item_id: fangling
item_name: Fangling
keywords:
    - Abyssal
    - Demon
level: 4
might: 3
name: Fangling
organization: Horde
presence: 0
reason: 0
role: Harrier
scc: mcdm.monsters.v1/monster.demon.2nd-echelon.statblock/fangling
size: 1L
source: mcdm.monsters.v1
speed: 8
stability: 0
stamina: "30"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage
          tier2: 7 damage
          tier3: 9 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Tooth! Tusk! Claw!
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: 8 x 3 line within 1
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage; pull 1; A < 1 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier2: 3 damage; pull 1; A < 2 [bleeding](../../../../condition/bleeding.md) (save ends)
          tier3: 4 damage; pull 1; A < 3 [bleeding](../../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Tumbling Gore
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: Whenever an [adjacent](../../../../rule/combat/adjacent.md) enemy [grabs](../../../../feature/common/maneuvers/grab.md) the fangling or uses a melee ability against the fangling, they take 2 damage.
      feature_type: trait
      icon: ⭐️
      name: Made of Teeth
      type: feature
    - effects:
        - effect: While the fangling is [winded](../../../../rule/health/winded.md), they gain an [edge](../../../../rule/dice/edge.md) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the fangling can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Abyssal
    - Demon
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.demon.2nd-echelon.statblock/fangling
    source: mcdm.monsters.v1
might: 3
name: Fangling
organization: Horde
presence: 0
reason: 0
role: Harrier
size: 1L
speed: 8
stability: 0
stamina: "30"
type: statblock
weaknesses:
    - Holy 5
```
