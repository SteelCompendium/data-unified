---
agility: 2
ev: "28"
file_basename: rival-elementalist
file_dpath: monster/rival/2nd-echelon/statblock
free_strike: 6
intuition: 2
item_id: rival-elementalist
item_name: Rival Elementalist
keywords:
    - Humanoid
    - Rival
level: 5
might: 0
name: Rival Elementalist
organization: Elite
presence: 0
reason: 3
role: Controller
scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-elementalist
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "120"
type: statblock
---

```ds-sb
agility: 2
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Ranged 10
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage; [slide](../../../../movement/forced-movement.md) 1; M < 1 3 acid damage
          tier2: 14 damage; [slide](../../../../movement/forced-movement.md) 2; M < 2 5 acid damage
          tier3: 17 damage; [slide](../../../../movement/forced-movement.md) 3; M < 3 7 acid damage
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Green
        - Magic
        - Ranged
        - Strike
      name: The Thriving Wilds
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 4 Malice
      distance: 4 cube within 10
      effects:
        - roll: Power Roll + 3
          tier1: 5 damage
          tier2: 9 damage; [restrained](../../../../condition/restrained.md) (EoT)
          tier3: 11 damage; [restrained](../../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Green
        - Magic
        - Ranged
      name: The Depths Hunger
      target: Each enemy in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The elementalist takes damage.
            **Effect:** The elementalist can [teleport](../../../../movement/teleport.md) up to 3 squares. Each creature [adjacent](../../../../rule/combat/adjacent.md) to the space they leave takes 3 corruption damage.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Void
      name: Fissures of Darkness
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the start of an encounter, the elementalist chooses one creature within their [line of effect](../../../../rule/combat/line-of-effect.md). Both the elementalist and the creature can add a d3 roll to power rolls they make against each other.
      feature_type: trait
      icon: ⭐️
      name: Rivalry
      type: feature
free_strike: 6
intuition: 2
keywords:
    - Humanoid
    - Rival
level: 5
metadata:
    scc: mcdm.monsters.v1/monster.rival.2nd-echelon.statblock/rival-elementalist
    source: mcdm.monsters.v1
might: 0
name: Rival Elementalist
organization: Elite
presence: 0
reason: 3
role: Controller
size: 1M
speed: 5
stability: 1
stamina: "120"
type: statblock
```
