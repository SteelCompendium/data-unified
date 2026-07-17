---
agility: 2
ev: "24"
file_basename: wyvern-predator
file_dpath: monster/wyvern/statblock
free_strike: 6
immunities:
    - Acid 5
intuition: 1
item_id: wyvern-predator
item_name: Wyvern Predator
keywords:
    - Beast
    - Wyvern
level: 4
might: 3
movement: Fly
name: Wyvern Predator
organization: Elite
presence: 0
reason: -1
role: Brute
scc: mcdm.monsters.v1/monster.wyvern.statblock/wyvern-predator
size: "3"
source: mcdm.monsters.v1
speed: 7
stability: 3
stamina: "140"
type: statblock
---

```ds-sb
agility: 2
ev: "24"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage
          tier2: 14 damage; M < 2 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 17 damage; M < 3 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Strike
        - Weapon
      name: Sedating Stinger
      target: Two creatures or objects
      type: feature
      usage: Main action
    - distance: 6 x 3 line within 1
      effects:
        - roll: Power Roll + 3
          tier1: 6 damage; A < 1 3 acid damage
          tier2: 11 damage; A < 2 3 acid damage
          tier3: 14 damage; A < 3 3 acid damage
      feature_type: ability
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Tail Sweep
      target: Each enemy and object in the area
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Melee 2
      effects:
        - roll: Power Roll + 3
          tier1: 9 damage; A < 1 [grabbed](../../../condition/grabbed.md)
          tier2: 14 damage; A < 2 [grabbed](../../../condition/grabbed.md)
          tier3: 17 damage; A < 3 [grabbed](../../../condition/grabbed.md) and the target takes a bane on the Escape Grab maneuver
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Magic
        - Strike
        - Weapon
      name: Grasping Jaws
      target: One creature or object
      type: feature
      usage: Maneuver
    - cost: 1 Malice
      distance: Melee 3
      effects:
        - effect: |-
            **Trigger:** A creature within distance deals damage to the predator with a melee ability.
            **Effect:** The predator uses Sedating Stinger against the target, then [shifts](../../../movement/shifting.md) up to 3 squares.
      feature_type: ability
      icon: ❗️
      keywords:
        - Melee
      name: Deterring Sting
      target: The triggering creature
      type: feature
      usage: Triggered action
    - effects:
        - effect: While [winded](../../../rule/health/winded.md) or within 10 squares of another wyvern, the predator can't be made [dazed](../../../condition/dazed.md) or [frightened](../../../condition/frightened.md).
      feature_type: trait
      icon: ⭐️
      name: Stubborn Rage
      type: feature
    - effects:
        - effect: Any creature affected by a condition imposed by a wyvern can't be hidden from the predator.
      feature_type: trait
      icon: ⭐️
      name: Tenacious Hunter
      type: feature
free_strike: 6
immunities:
    - Acid 5
intuition: 1
keywords:
    - Beast
    - Wyvern
level: 4
metadata:
    scc: mcdm.monsters.v1/monster.wyvern.statblock/wyvern-predator
    source: mcdm.monsters.v1
might: 3
movement: Fly
name: Wyvern Predator
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
