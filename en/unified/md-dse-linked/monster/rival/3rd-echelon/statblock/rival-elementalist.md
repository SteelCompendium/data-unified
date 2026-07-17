---
agility: 2
ev: "40"
file_basename: rival-elementalist
file_dpath: monster/rival/3rd-echelon/statblock
free_strike: 8
intuition: 3
item_id: rival-elementalist
item_name: Rival Elementalist
keywords:
    - Humanoid
    - Rival
level: 8
might: 0
name: Rival Elementalist
organization: Elite
presence: 0
reason: 4
role: Controller
scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-elementalist
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "180"
type: statblock
---

```ds-sb
agility: 2
ev: "40"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 4
          tier1: 12 damage; [slide](../../../../movement/forced-movement.md) 2; M < 2 4 acid damage
          tier2: 17 damage; [slide](../../../../movement/forced-movement.md) 3; M < 3 6 acid damage
          tier3: 21 damage; [slide](../../../../movement/forced-movement.md) 4; M < 4 8 acid damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Green
        - Magic
        - Ranged
        - Strike
      name: Verdant Rains
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 4 Malice
      distance: 5 cube within 10
      effects:
        - roll: Power Roll + 4
          tier1: 6 damage
          tier2: 10 damage; [restrained](../../../../condition/restrained.md) (EoT)
          tier3: 14 damage; [restrained](../../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Green
        - Magic
        - Ranged
      name: The Chasm Engulfs
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The elementalist takes damage.
            **Effect:** The elementalist can [teleport](../../../../movement/teleport.md) up to 4 squares. Each creature [adjacent](../../../../rule/combat/adjacent.md) to the space they leave or appear in takes 4 corruption damage.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Void
      name: Maw of the Abyss
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of an encounter, the elementalist chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the elementalist and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 8
intuition: 3
keywords:
    - Humanoid
    - Rival
level: 8
metadata:
    scc: mcdm.monsters.v1/monster.rival.3rd-echelon.statblock/rival-elementalist
    source: mcdm.monsters.v1
might: 0
name: Rival Elementalist
organization: Elite
presence: 0
reason: 4
role: Controller
size: 1M
speed: 5
stability: 1
stamina: "180"
type: statblock
```
