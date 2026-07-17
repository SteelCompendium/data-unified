---
agility: 1
ev: "20"
file_basename: lightbender-pouncer
file_dpath: monster/lightbender/statblock
free_strike: 5
intuition: 1
item_id: lightbender-pouncer
item_name: Lightbender Pouncer
keywords:
    - Beast
    - Lightbender
level: 3
might: 2
name: Lightbender Pouncer
organization: Elite
presence: -1
reason: -3
role: Harrier
scc: mcdm.monsters.v1/monster.lightbender.statblock/lightbender-pouncer
size: "2"
source: mcdm.monsters.v1
speed: 10
stability: 1
stamina: "100"
type: statblock
---

```ds-sb
agility: 1
ev: "20"
features:
    - ability_type: Signature Ability
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage
          tier2: 11 damage; A < 1 [prone](../../../condition/prone.md)
          tier3: 14 damage; A < 2 [prone](../../../condition/prone.md)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      name: Pounce
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 2 burst
      effects:
        - roll: Power Roll + 2
          tier1: 4 damage
          tier2: 7 damage; A < 1 the target is dazzled (save ends)
          tier3: 10 damage; A < 2 the target is dazzled (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Sparkling Tail Whip
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: 3 cube within 10
      effects:
        - roll: Power Roll + 2
          tier1: I < 0 [dazed](../../../condition/dazed.md) (save ends)
          tier2: I < 1 [dazed](../../../condition/dazed.md) (save ends)
          tier3: I < 2 [dazed](../../../condition/dazed.md) (save ends)
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
        - Ranged
      name: Illusory Feint
      target: Each enemy in the area
      type: feature
      usage: Maneuver
    - distance: Self
      effects:
        - effect: |-
            **Trigger:** The pouncer takes damage from a strike.
            **Effect:** The pouncer halves the damage, ignores any nondamaging effects associated with it, and can [teleport](../../../movement/teleport.md) up to 5 squares. If they [teleport](../../../movement/teleport.md) into concealment or cover, the pouncer can immediately attempt to hide as a free maneuver.
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
      name: Striking Afterimage
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: Any effect on the pouncer that would be ended by a [saving throw](../../../rule/general/saving-throw.md) instead ends automatically at the end of their next turn.
      feature_type: trait
      icon: ⭐️
      name: Avoidance
      type: feature
free_strike: 5
intuition: 1
keywords:
    - Beast
    - Lightbender
level: 3
metadata:
    scc: mcdm.monsters.v1/monster.lightbender.statblock/lightbender-pouncer
    source: mcdm.monsters.v1
might: 2
name: Lightbender Pouncer
organization: Elite
presence: -1
reason: -3
role: Harrier
size: "2"
speed: 10
stability: 1
stamina: "100"
type: statblock
```
