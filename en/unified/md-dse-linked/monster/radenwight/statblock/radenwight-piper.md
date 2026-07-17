---
agility: 0
ev: "6"
file_basename: radenwight-piper
file_dpath: monster/radenwight/statblock
free_strike: 3
intuition: 2
item_id: radenwight-piper
item_name: Radenwight Piper
keywords:
    - Humanoid
    - Radenwight
level: 1
might: 0
movement: Climb
name: Radenwight Piper
organization: Platoon
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-piper
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "30"
type: statblock
---

```ds-sb
agility: 0
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 1 or ranged 10
      effects:
        - roll: Power Roll + 2
          tier1: 5 sonic damage; [push](../../../movement/forced-movement.md) 1
          tier2: 7 sonic damage; [push](../../../movement/forced-movement.md) 3
          tier3: 9 sonic damage; [push](../../../movement/forced-movement.md) 4
      feature_type: ability
      icon: ⚔️
      keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
      name: Piercing Trill
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 3 burst
      effects:
        - effect: |-
            **Effect:** Each target who has used their Ready Rodent ability this round regains the use of their triggered action.
            **2 [Malice](../../../rule/monster/malice.md):** The area increases to a 6 burst.
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Magic
      name: Vivace Vivace!
      target: Each ally in the area
      type: feature
      usage: Maneuver
    - distance: Melee 1
      effects:
        - effect: |-
            **Trigger:** An ally deals damage to the target.
            **Effect:** The piper makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
        - Weapon
      name: Ready Rodent
      target: One creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: At the end of the piper's turn, they can [slide](../../../movement/forced-movement.md) one [adjacent](../../../rule/combat/adjacent.md) creature up to 2 squares, ignoring stability.
      feature_type: trait
      icon: ⭐️
      name: Musical Suggestion
      type: feature
free_strike: 3
intuition: 2
keywords:
    - Humanoid
    - Radenwight
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.radenwight.statblock/radenwight-piper
    source: mcdm.monsters.v1
might: 0
movement: Climb
name: Radenwight Piper
organization: Platoon
presence: 1
reason: 0
role: Support
size: 1S
speed: 5
stability: 0
stamina: "30"
type: statblock
```
