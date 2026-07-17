---
agility: 2
ev: "16"
file_basename: bugbear-roughneck
file_dpath: monster/bugbear/statblock
free_strike: 5
intuition: 0
item_id: bugbear-roughneck
item_name: Bugbear Roughneck
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
might: 2
name: Bugbear Roughneck
organization: Elite
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-roughneck
size: 1L
source: mcdm.monsters.v1
speed: 6
stability: 0
stamina: "109"
type: statblock
---

```ds-sb
agility: 2
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 11 damage; one target is [grabbed](../../../condition/grabbed.md); one target is [pushed](../../../movement/forced-movement.md) up to 2 squares
          tier3: 14 damage; one target is [grabbed](../../../condition/grabbed.md); one target is vertical [pushed](../../../movement/forced-movement.md) up to 3 squares
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Haymaker
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 8 damage; M < 1 [prone](../../../condition/prone.md)
          tier2: 13 damage; M < 2 [prone](../../../condition/prone.md)
          tier3: 16 damage; M < 3 [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Leaping Fury
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 1
      effects:
        - effect: |-
            **Special:** The target must be [grabbed](../../../condition/grabbed.md) by the roughneck.
            **Effect:** The roughneck moves up to their speed across the ground, dragging the target with them. The target takes 2 damage for each square they were dragged through. When this movement ends, the target is no longer [grabbed](../../../condition/grabbed.md) and falls [prone](../../../condition/prone.md). Each square the target was dragged through is difficult terrain for enemies.
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
      name: Drag Through Hell
      target: One creature or object
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Special:** The target must be [grabbed](../../../condition/grabbed.md) by the roughneck.
            **Effect:** The target is vertical [pushed](../../../movement/forced-movement.md) up to 5 squares. An ally doesn't take damage from being [force moved](../../../movement/forced-movement.md) this way.
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
      name: Throw
      target: One creature or object
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** A size 1 creature or object is [force moved](../../../movement/forced-movement.md) within distance, or a size 1 ally willingly moves within distance.
            **Effect:** The target is [grabbed](../../../condition/grabbed.md) by the roughneck.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Catcher
      target: The triggering creature or object
      type: feature
      usage: Free triggered action
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The roughneck is vertical force moved by another creature.
            **Effect:** The roughneck uses Haymaker against a creature or object at any point during the forced movement, or after falling as a result of it.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Flying Sawblade
      target: Self
      type: feature
      usage: Triggered action
free_strike: 5
intuition: 0
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-roughneck
    source: mcdm.monsters.v1
might: 2
name: Bugbear Roughneck
organization: Elite
presence: 0
reason: 0
role: Brute
size: 1L
speed: 6
stability: 0
stamina: "109"
type: statblock
```
