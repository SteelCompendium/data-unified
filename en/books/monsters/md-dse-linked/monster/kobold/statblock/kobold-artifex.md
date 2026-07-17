---
agility: 2
ev: "3"
file_basename: kobold-artifex
file_dpath: monster/kobold/statblock
free_strike: 1
intuition: 0
item_id: kobold-artifex
item_name: Kobold Artifex
keywords:
    - Humanoid
    - Kobold
level: 1
might: 0
name: Kobold Artifex
organization: Horde
presence: 0
reason: 1
role: Controller
scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-artifex
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "10"
type: statblock
---

```ds-sb
agility: 2
ev: "3"
features:
    - ability_type: Signature Ability
      distance: Ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 3 damage; pull 1
          tier2: 4 damage; pull 2
          tier3: 5 damage; pull 3
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Chain Hook
      target: One creature or object
      type: feature
      usage: Main action
    - distance: Ranged 10
      effects:
        - effect: |-
            **Effect:** The trap or terrain object instantly triggers.
            **3 [Malice](../../../rule/monster/malice.md):** The artifex places a new trap in the encounter and can instantly trigger it. The artifex prefers working with angry beehives, flammable oil, snare traps, and spike traps (see Dynamic Terrain).
      feature_type: ability
      icon: ⭐️
      keywords:
        - Ranged
      name: Activate Trap
      target: One trap or other terrain object
      type: feature
      usage: Maneuver
    - effects:
        - effect: While [adjacent](../../../rule/combat/adjacent.md) to an ally who also has this trait, the artifex has stability 1, has cover, and grants cover to allies.
      feature_type: trait
      icon: ⭐️
      name: Shield? Shield!
      type: feature
free_strike: 1
intuition: 0
keywords:
    - Humanoid
    - Kobold
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.kobold.statblock/kobold-artifex
    source: mcdm.monsters.v1
might: 0
name: Kobold Artifex
organization: Horde
presence: 0
reason: 1
role: Controller
size: 1S
speed: 5
stability: 0
stamina: "10"
type: statblock
```
