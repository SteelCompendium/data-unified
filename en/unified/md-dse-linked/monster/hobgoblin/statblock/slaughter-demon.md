---
agility: 0
ev: "24"
file_basename: slaughter-demon
file_dpath: monster/hobgoblin/statblock
free_strike: 6
immunities:
    - Fire 5
intuition: 1
item_id: slaughter-demon
item_name: Slaughter Demon
keywords:
    - Abyssal
    - Demon
    - Hobgoblin
level: 4
might: 3
movement: Burrow
name: Slaughter Demon
organization: Elite
presence: 0
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.hobgoblin.statblock/slaughter-demon
size: "3"
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "140"
type: statblock
---

```ds-sb
agility: 0
ev: "24"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage
          tier2: 14 damage; A < 2 [bleeding](../../../condition/bleeding.md) (save ends)
          tier3: 17 damage; A < 3 [bleeding](../../../condition/bleeding.md) and [restrained](../../../condition/restrained.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Steely Skewer
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Melee 5
      effects:
        - roll: Power Roll + 3
          tier1: 10 poison damage; M < 1 [weakened](../../../condition/weakened.md) (save ends)
          tier2: 16 poison damage; M < 2 [weakened](../../../condition/weakened.md) (save ends)
          tier3: 20 poison damage; M < 3 [weakened](../../../condition/weakened.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Tail Stinger
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: The slaughter demon can make a [free strike](../../../feature/common/main-actions/free-strike.md) as part of using the Dig maneuver. If the target of the [free strike](../../../feature/common/main-actions/free-strike.md) has M < 2, they are [grabbed](../../../condition/grabbed.md) and take a bane on the Escape Grab maneuver.
      feature_type: trait
      icon: ⭐️
      name: Drag Below
      type: feature
    - distance: 5 burst
      effects:
        - effect: |-
            **Trigger:** A creature within distance who has a soul dies.
            **Effect:** The target can't be brought back to life. Until the end of the encounter, the slaughter demon gains an edge on power rolls.
      feature_type: ability
      icon: ❗️
      keywords:
        - Area
        - Magic
      name: Devour Soul
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: Any creature within 2 squares of the slaughter demon can't be hidden from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
    - effects:
        - effect: While the slaughter demon is [winded](../../../rule/health/winded.md), they gain an edge on strikes, and any strike made against them gains an edge.
      feature_type: trait
      icon: ⭐️
      name: Lethe
      type: feature
free_strike: 6
immunities:
    - Fire 5
intuition: 1
keywords:
    - Abyssal
    - Demon
    - Hobgoblin
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.hobgoblin.statblock/slaughter-demon
    source: mcdm.monsters.v1
might: 3
movement: Burrow
name: Slaughter Demon
organization: Elite
presence: 0
reason: -1
role: Brute
size: "3"
speed: 7
stability: 3
stamina: "140"
type: statblock
```
