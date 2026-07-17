---
agility: 1
ev: "3"
file_basename: torlas
file_dpath: monster/demon/1st-echelon/statblock
free_strike: 1
intuition: 0
item_id: torlas
item_name: Torlas
keywords:
    - Abyssal
    - Demon
level: 1
might: 0
name: Torlas
organization: Horde
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/torlas
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "10"
type: statblock
weaknesses:
    - Holy 3
---

```ds-sb
agility: 1
ev: "3"
features:
    - ability_type: Signature Ability
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 2
          tier1: Slide 3
          tier2: Slide 4
          tier3: Slide 5
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Floor to Flesh
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: '**Effect:** The torlas pulls each target up to 3 squares.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Grasping Tendons
      target: Three creatures
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the torlas is [winded](../../../../rule/health/winded.md), they gain an [edge](../../../../rule/dice/edge.md) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the torlas can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Abyssal
    - Demon
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/torlas
    source: mcdm.monsters.v1
might: 0
name: Torlas
organization: Horde
presence: 2
reason: 0
role: Controller
size: 1S
speed: 5
stability: 0
stamina: "10"
type: statblock
weaknesses:
    - Holy 3
```
