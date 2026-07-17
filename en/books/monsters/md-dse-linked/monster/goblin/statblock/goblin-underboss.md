---
agility: 2
ev: "3"
file_basename: goblin-underboss
file_dpath: monster/goblin/statblock
free_strike: 1
intuition: 0
item_id: goblin-underboss
item_name: Goblin Underboss
keywords:
    - Goblin
    - Humanoid
level: 1
might: -1
movement: Climb
name: Goblin Underboss
organization: Horde
presence: 1
reason: 0
role: Support
scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-underboss
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "15"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage
          tier2: 4 damage
          tier3: 5 damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Swordplay
      target: One creature or object
      type: feature
      usage: Main action
    - distance: 5 burst
      effects:
        - effect: |-
            **Effect:** Until the start of the underboss's next turn, each target gains an edge on strikes, and any strike made against a target gains an edge.
            **2 [Malice](../../../rule/monster/malice.md):** Strikes made against targets no longer gain an edge.
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
      name: Get Reckless!
      target: Each ally in the area
      type: feature
      usage: Maneuver
    - effects:
        - effect: The underboss doesn't provoke [opportunity attacks](../../../rule/combat/opportunity-attack.md) by moving.
      feature_type: trait
      icon: ⭐️
      name: Crafty
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Goblin
    - Humanoid
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.goblin.statblock/goblin-underboss
    source: mcdm.monsters.v1
might: -1
movement: Climb
name: Goblin Underboss
organization: Horde
presence: 1
reason: 0
role: Support
size: 1S
speed: 5
stability: 0
stamina: "15"
type: statblock
```
