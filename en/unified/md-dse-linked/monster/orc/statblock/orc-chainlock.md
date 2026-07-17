---
agility: 2
ev: "6"
file_basename: orc-chainlock
file_dpath: monster/orc/statblock
free_strike: 3
intuition: 0
item_id: orc-chainlock
item_name: Orc Chainlock
keywords:
    - Humanoid
    - Orc
level: 1
might: 2
name: Orc Chainlock
organization: Platoon
presence: 0
reason: 1
role: Hexer
scc: mcdm.monsters.v1/monster.orc.statblock/orc-chainlock
size: 1L
source: mcdm.monsters.v1
speed: 5
stability: 2
stamina: "20"
type: statblock
---

```ds-sb
agility: 2
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 3
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; [pull](../../../movement/forced-movement.md) 1; M < 0 the target is hooked (save ends)
          tier2: 7 damage; [pull](../../../movement/forced-movement.md) 2; M < 1 the target is hooked (save ends)
          tier3: 9 damage; [pull](../../../movement/forced-movement.md) 3; M < 2 the target is hooked (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Hook and Chain
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: Ranged 5
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; A < 0 [slowed](../../../condition/slowed.md) (save ends)
          tier2: 7 damage; A < 1 [slowed](../../../condition/slowed.md) (save ends)
          tier3: 9 damage; [prone](../../../condition/prone.md); A < 2 [slowed](../../../condition/slowed.md) (save ends)
      feature_type: ability
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      name: Heavy Crossbolt
      target: One creature or object
      type: feature
      usage: Main action
    - effects:
        - effect: Whenever the chainlock is [force moved](../../../movement/forced-movement.md) by a creature's melee ability, the creature is [pulled](../../../movement/forced-movement.md) the same distance toward the chainlock after the [forced movement](../../../movement/forced-movement.md) is resolved.
      feature_type: trait
      icon: ⭐️
      name: Chain Link
      type: feature
    - effects:
        - effect: If the chainlock is reduced to 0 [Stamina](../../../rule/health/stamina.md), they can make a [free strike](../../../feature/common/main-actions/free-strike.md) before dying. If the target of the free strike is reduced to 0 [Stamina](../../../rule/health/stamina.md), the chainlock is reduced to 1 [Stamina](../../../rule/health/stamina.md) instead.
      feature_type: trait
      icon: ⭐️
      name: Relentless
      type: feature
free_strike: 3
intuition: 0
keywords:
    - Humanoid
    - Orc
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.orc.statblock/orc-chainlock
    source: mcdm.monsters.v1
might: 2
name: Orc Chainlock
organization: Platoon
presence: 0
reason: 1
role: Hexer
size: 1L
speed: 5
stability: 2
stamina: "20"
type: statblock
```
