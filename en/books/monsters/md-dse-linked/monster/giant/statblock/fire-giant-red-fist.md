---
agility: 2
ev: "44"
file_basename: fire-giant-red-fist
file_dpath: monster/giant/statblock
free_strike: 10
immunities:
    - Fire 9
intuition: 2
item_id: fire-giant-red-fist
item_name: Fire Giant Red Fist
keywords:
    - Fire Giant
    - Giant
level: 9
might: 4
name: Fire Giant Red Fist
organization: Elite
presence: 1
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.giant.statblock/fire-giant-red-fist
size: "4"
source: mcdm.monsters.v1
speed: 8
stability: 5
stamina: "240"
type: statblock
---

```ds-sb
agility: 2
ev: "44"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 4
          tier1: 14 fire damage; [push](../../../movement/forced-movement.md) 2
          tier2: 19 fire damage; [push](../../../movement/forced-movement.md) 4; A < 3 burning (save ends)
          tier3: 23 fire damage; [push](../../../movement/forced-movement.md) 6; A < 4 burning (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Flaming Punch
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Special
      effects:
        - roll: Power Roll + 4
          tier1: The distance is a 2 burst; 8 fire damage; M < 2 [pull](../../../movement/forced-movement.md) 2
          tier2: The distance is a 3 burst; 12 fire damage; M < 3 [pull](../../../movement/forced-movement.md) 4
          tier3: The distance is a 4 burst; 15 fire damage; M < 4 [pull](../../../movement/forced-movement.md) 6
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Caldera
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - distance: Self
      effects:
        - effect: '**Effect:** The red fist jumps up to 5 squares. Each creature [adjacent](../../../rule/combat/adjacent.md) to them when they land takes 5 fire damage.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Blazing Leap
      target: Self
      type: feature
      usage: Maneuver
    - distance: Melee 3
      effects:
        - roll: ""
          tier1: '[Weakened](../../../condition/weakened.md) and [slowed](../../../condition/slowed.md) (save ends)'
          tier2: '[Weakened](../../../condition/weakened.md) (EoT)'
          tier3: No effect
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Heat and Pressure
      target: The triggering creature
      type: feature
      usage: Free triggered action
    - distance: Melee 3
      effects:
        - effect: |-
            **Trigger:** An ally within distance is targeted by an enemy's ability.
            **Effect:** The red fist becomes the target of the triggering ability, then can make a [free strike](../../../feature/common/main-actions/free-strike.md) against the enemy after the ability resolves.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Guardian Block
      target: Self
      type: feature
      usage: Triggered action
    - effects:
        - effect: Whenever an [adjacent](../../../rule/combat/adjacent.md) enemy [grabs](../../../condition/grabbed.md) the red fist or uses a melee ability against them, that enemy takes 5 fire damage.
      feature_type: trait
      icon: ⭐️
      name: Searing Skin
      type: feature
free_strike: 10
immunities:
    - Fire 9
intuition: 2
keywords:
    - Fire Giant
    - Giant
level: 9
metadata:
    scc: mcdm.monsters.v1/monster.giant.statblock/fire-giant-red-fist
    source: mcdm.monsters.v1
might: 4
name: Fire Giant Red Fist
organization: Elite
presence: 1
reason: 0
role: Brute
size: "4"
speed: 8
stability: 5
stamina: "240"
type: statblock
```
