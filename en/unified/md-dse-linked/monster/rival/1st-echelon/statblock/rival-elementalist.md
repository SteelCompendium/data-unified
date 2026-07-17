---
agility: 0
ev: "16"
file_basename: rival-elementalist
file_dpath: monster/rival/1st-echelon/statblock
free_strike: 5
intuition: 1
item_id: rival-elementalist
item_name: Rival Elementalist
keywords:
    - Humanoid
    - Rival
level: 2
might: 0
name: Rival Elementalist
organization: Elite
presence: 0
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-elementalist
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "60"
type: statblock
---

```ds-sb
agility: 0
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; [slide](../../../../movement/forced-movement.md) 1
          tier2: 10 damage; [slide](../../../../movement/forced-movement.md) 2
          tier3: 13 damage; [slide](../../../../movement/forced-movement.md) 3
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Green
        - Magic
        - Ranged
        - Strike
      name: The Writhing Green
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage
          tier2: 5 damage; [restrained](../../../../condition/restrained.md) (EoT)
          tier3: 8 damage; [restrained](../../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Green
        - Magic
        - Ranged
      name: The Earth Devours
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The elementalist takes damage.
            **Effect:** The elementalist can [teleport](../../../../movement/teleport.md) up to 2 squares. Each creature [adjacent](../../../../rule/combat/adjacent.md) to the space they leave takes 2 corruption damage.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Void
      name: Jaws of the Void
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of an encounter, the elementalist chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the elementalist and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Humanoid
    - Rival
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.rival.1st-echelon.statblock/rival-elementalist
    source: mcdm.monsters.v1
might: 0
name: Rival Elementalist
organization: Elite
presence: 0
reason: 2
role: Controller
size: 1M
speed: 5
stability: 1
stamina: "60"
type: statblock
```
