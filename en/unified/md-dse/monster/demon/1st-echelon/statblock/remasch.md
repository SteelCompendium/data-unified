---
agility: 2
ev: "4"
file_basename: remasch
file_dpath: monster/demon/1st-echelon/statblock
free_strike: 3
intuition: 0
item_id: remasch
item_name: Remasch
keywords:
    - Abyssal
    - Demon
level: 2
might: 0
movement: Teleport
name: Remasch
organization: Horde
presence: 2
reason: 0
role: Ambusher
scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/remasch
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "20"
type: statblock
weaknesses:
    - Holy 3
---

```ds-sb
agility: 2
ev: "4"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; the remasch can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 2 squares
          tier2: 6 damage; the remasch can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 3 squares
          tier3: 8 damage; the remasch can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Melee
        - Strike
        - Weapon
      name: Abyssal Strike
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Self
      effects:
        - effect: '**Effect:** The remasch can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 2 squares and uses Abyssal Strike.'
      feature_type: ability
      icon: "\U0001F464"
      keywords:
        - Magic
      name: Grasping Shadow
      target: Self
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the remasch is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the remasch can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Abyssal
    - Demon
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/remasch
    source: mcdm.monsters.v1
might: 0
movement: Teleport
name: Remasch
organization: Horde
presence: 2
reason: 0
role: Ambusher
size: 1S
speed: 5
stability: 0
stamina: "20"
type: statblock
weaknesses:
    - Holy 3
```
