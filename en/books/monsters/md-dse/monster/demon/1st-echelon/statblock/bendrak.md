---
agility: 1
ev: "4"
file_basename: bendrak
file_dpath: monster/demon/1st-echelon/statblock
free_strike: 2
intuition: 0
item_id: bendrak
item_name: Bendrak
keywords:
    - Abyssal
    - Demon
level: 2
might: 0
name: Bendrak
organization: Horde
presence: 2
reason: 0
role: Hexer
scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/bendrak
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "15"
type: statblock
weaknesses:
    - Holy 3
---

```ds-sb
agility: 1
ev: "4"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 4 psychic damage
          tier2: 5 psychic damage; P < 1 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
          tier3: 7 psychic damage; P < 2 [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Warp Perceptions
      target: One creature
      type: feature
      usage: Main action
    - cost: 1 Malice
      distance: Ranged 10
      effects:
        - effect: '**Effect:** The target is invisible until the start of their next turn. They can then move up to 3 squares and attempt to hide.'
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Vanish
      target: Self or one ally
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the bendrak is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the bendrak can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 2
intuition: 0
keywords:
    - Abyssal
    - Demon
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.demon.1st-echelon.statblock/bendrak
    source: mcdm.monsters.v1
might: 0
name: Bendrak
organization: Horde
presence: 2
reason: 0
role: Hexer
size: 1L
speed: 5
stability: 0
stamina: "15"
type: statblock
weaknesses:
    - Holy 3
```
