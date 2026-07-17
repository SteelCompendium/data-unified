---
agility: 0
ev: "12"
file_basename: izyak
file_dpath: monster/demon/4th-echelon/statblock
free_strike: 4
intuition: 2
item_id: izyak
item_name: Izyak
keywords:
    - Abyssal
    - Demon
level: 10
might: 0
movement: Teleport
name: Izyak
organization: Horde
presence: 4
reason: 5
role: Controller
scc: mcdm.monsters.v1/monster.demon.4th-echelon.statblock/izyak
size: "2"
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "55"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 0
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 5
          tier1: 9 psychic damage; R < 3 [restrained](../../../../condition/restrained.md) (save ends)
          tier2: 12 psychic damage; R < 4 [restrained](../../../../condition/restrained.md) (save ends)
          tier3: 14 psychic damage; R < 5 [restrained](../../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
      name: Nostalgic Wanderlust
      target: One creature
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 4 cube within 10
      effects:
        - roll: Power Roll + 5
          tier1: 4 psychic damage; I < 3 [dazed](../../../../condition/dazed.md) (save ends)
          tier2: 7 psychic damage; I < 4 [dazed](../../../../condition/dazed.md) (save ends)
          tier3: 9 psychic damage; I < 5 [dazed](../../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Psionic
        - Ranged
      name: Ruinous Temptation
      target: Each enemy in the area
      type: feature
      usage: Main action
    - effects:
        - effect: While the izyak is [winded](../../../../rule/health/winded.md), they gain an [edge](../../../../rule/dice/edge.md) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the izyak can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 4
intuition: 2
keywords:
    - Abyssal
    - Demon
level: 10
metadata:
    scc: mcdm.monsters.v1/monster.demon.4th-echelon.statblock/izyak
    source: mcdm.monsters.v1
might: 0
movement: Teleport
name: Izyak
organization: Horde
presence: 4
reason: 5
role: Controller
size: "2"
speed: 6
stability: 0
stamina: "55"
type: statblock
weaknesses:
    - Holy 5
```
