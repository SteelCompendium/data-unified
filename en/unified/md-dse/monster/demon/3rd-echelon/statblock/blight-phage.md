---
agility: 0
ev: "9"
file_basename: blight-phage
file_dpath: monster/demon/3rd-echelon/statblock
free_strike: 3
intuition: 2
item_id: blight-phage
item_name: Blight Phage
keywords:
    - Abyssal
    - Demon
level: 7
might: 0
name: Blight Phage
organization: Horde
presence: 4
reason: 4
role: Controller
scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/blight-phage
size: "3"
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "40"
type: statblock
weaknesses:
    - Holy 5
---

```ds-sb
agility: 0
ev: "9"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 7 corruption damage
          tier2: 10 corruption damage
          tier3: 11 corruption damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Blight Pus
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 5 cube within 1
      effects:
        - effect: |-
            **Special:** The blight phage must create the cube beneath themself.
            **Effect:** The blight phage spins and sheds corruptive blight to fill the area, which is treated as if affected by Seeping Blight.
            **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The blight phage chooses three 2 cube areas within 10 squares of the phage. Each area is covered with blight and treated as if affected by Seeping Blight.
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Blight Rain
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: While the blight phage is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded), they gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
    - effects:
        - effect: Any creature within 2 squares of the blight phage can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Abyssal
    - Demon
level: 7
metadata:
    scc: mcdm.monsters.v1/monster.demon.3rd-echelon.statblock/blight-phage
    source: mcdm.monsters.v1
might: 0
name: Blight Phage
organization: Horde
presence: 4
reason: 4
role: Controller
size: "3"
speed: 6
stability: 0
stamina: "40"
type: statblock
weaknesses:
    - Holy 5
```
