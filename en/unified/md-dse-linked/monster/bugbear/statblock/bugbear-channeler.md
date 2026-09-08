---
agility: 1
ev: "16"
file_basename: bugbear-channeler
file_dpath: monster/bugbear/statblock
free_strike: 5
intuition: 2
item_id: bugbear-channeler
item_name: Bugbear Channeler
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
might: 1
name: Bugbear Channeler
organization: Elite
presence: 2
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-channeler
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "60"
type: statblock
---

```ds-sb
agility: 1
ev: "16"
features:
    - ability_type: Signature Ability
      distance: Ranged 8
      effects:
        - roll: Power Roll + 2
          tier1: 7 damage; pull 2
          tier2: 10 damage; pull 3
          tier3: 13 damage; pull 4
        - effect: Each target must be on the ground, and each square a target is pulled through is difficult terrain for enemies.
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Shadow Drag
      target: Two creatures or objects
      type: feature
      usage: Main Action
    - distance: 3 burst
      effects:
        - effect: 'The channeler chooses one of the following damage types: acid, cold, corruption, fire, or poison.'
          name: Effect
          roll: Power Roll + 2
          tier1: 2 damage; M < 0 [bleeding](../../../condition/bleeding.md) (save ends)
          tier2: 3 damage; M < 1 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 4 damage; M < 2 [bleeding](../../../condition/bleeding.md) (save ends)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Blistering Element
      target: Each enemy in the area
      type: feature
      usage: Main Action
    - cost: 5 Malice
      distance: Ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 5 corruption damage; P < 0 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 8 corruption damage; P < 1 the target is shapechanged (save ends)
          tier3: 11 corruption damage; P < 2 the target is shapechanged (save ends)
        - effect: A shapechanged creature is [slowed](../../../condition/slowed.md) and has fire weakness 10 as their limbs stretch and their skin becomes paper thin.
          name: Effect
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      name: Twist Shape
      target: One creature
      type: feature
      usage: Main Action
    - distance: Melee 1
      effects:
        - effect: The target must be [grabbed](../../../condition/grabbed.md) by the channeler.
          name: Special
        - effect: The target is vertical [pushed](../../../movement/forced-movement.md) up to 3 squares. An ally doesn't take damage from being [force moved](../../../movement/forced-movement.md) this way.
          name: Effect
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
        - effect: The target is [grabbed](../../../condition/grabbed.md) by the channeler.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Catcher
      target: The triggering creature or object
      trigger: A size 1 creature or object is [force moved](../../../movement/forced-movement.md) within distance, or a size 1 ally willingly moves within distance.
      type: feature
      usage: Free triggered action
    - distance: Ranged 5
      effects:
        - effect: The target is wrapped in shadow and halves the damage. The target can't be targeted by strikes until the start of their next turn.
          name: Effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Magic
        - Ranged
      name: Shadow Veil
      target: The triggering ally
      trigger: An ally within distance takes damage.
      type: feature
      usage: Triggered action
free_strike: 5
intuition: 2
keywords:
    - Bugbear
    - Fey
    - Goblin
    - Humanoid
level: 2
metadata:
    scc: mcdm.monsters.v1/monster.bugbear.statblock/bugbear-channeler
    source: mcdm.monsters.v1
might: 1
name: Bugbear Channeler
organization: Elite
presence: 2
reason: 2
role: Controller
size: 1L
speed: 5
stability: 0
stamina: "60"
type: statblock
```
