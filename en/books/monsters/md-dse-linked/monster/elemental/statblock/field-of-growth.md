---
agility: 0
ev: "28"
file_basename: field-of-growth
file_dpath: monster/elemental/statblock
free_strike: 6
immunities:
    - Poison 5
intuition: 2
item_id: field-of-growth
item_name: Field of Growth
keywords:
    - Elemental
level: 3
might: 2
movement: Climb
name: Field of Growth
organization: Elite
presence: 2
reason: 0
role: Controller
scc: mcdm.monsters.v1/monster.elemental.statblock/field-of-growth
size: "3"
source: mcdm.monsters.v1
speed: 8
stability: 2
stamina: "120"
type: statblock
---

```ds-sb
agility: 0
ev: "28"
features:
    - ability_type: Signature Ability
      distance: Ranged 8
      effects:
        - roll: Power Roll + 2
          tier1: 8 damage
          tier2: 13 damage; R < 1 [prone](../../../condition/prone.md) and can't stand (save ends)
          tier3: 16 damage; R < 2 [prone](../../../condition/prone.md) and can't stand (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Hampering Roots
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: Ranged 5
      effects:
        - effect: |-
            **Effect:** The target gains 15 temporary Stamina that lasts until the start of the field's next turn.
            **3 [Malice](../../../rule/monster/malice.md):** Until the end of the encounter, the ground within 1 square of the target is overgrown with underbrush and vines. Whenever any enemy makes a strike against the target while within line of effect of that area, the enemy is [pulled](../../../movement/forced-movement.md) 5 squares toward the area after the strike is resolved. Any enemy who enters the area for the first time in a round or starts their turn there is knocked [prone](../../../condition/prone.md).
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
      name: Convocation of Verdure
      target: Self or one elemental
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Melee 3
      effects:
        - effect: |-
            **Trigger:** A creature or object within distance deals damage to the field.
            **Effect:** The target takes 6 damage, and if they have A < 2, they are [bleeding](../../../condition/bleeding.md) (save ends).
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Melee
      name: Rose Thorn Lash
      target: The triggering creature or object
      type: feature
      usage: Triggered action
    - effects:
        - effect: The field can't be [restrained](../../../condition/restrained.md), [slowed](../../../condition/slowed.md), or knocked [prone](../../../condition/prone.md), and they ignore [difficult terrain](../../../movement/difficult-terrain.md).
      feature_type: trait
      icon: ⭐️
      name: Fickle and Free
      type: feature
    - effects:
        - effect: The field can target any creature touching the ground with their abilities, even if they don't have line of effect to that creature.
      feature_type: trait
      icon: ⭐️
      name: Roots Run Deep
      type: feature
free_strike: 6
immunities:
    - Poison 5
intuition: 2
keywords:
    - Elemental
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.elemental.statblock/field-of-growth
    source: mcdm.monsters.v1
might: 2
movement: Climb
name: Field of Growth
organization: Elite
presence: 2
reason: 0
role: Controller
size: "3"
speed: 8
stability: 2
stamina: "120"
type: statblock
```
