---
agility: 2
ev: 3 for four minions
file_basename: lizardfolk-tonguer
file_dpath: monster/lizardfolk/statblock
free_strike: 2
intuition: 1
item_id: lizardfolk-tonguer
item_name: Lizardfolk Tonguer
keywords:
    - Humanoid
    - Lizardfolk
level: 1
might: 0
movement: Swim
name: Lizardfolk Tonguer
organization: Minion
presence: 0
reason: 0
role: Artillery
scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-tonguer
size: 1S
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +1 bonus to strikes
---

```ds-sb
agility: 2
ev: 3 for four minions
features:
    - ability_type: Signature Ability
      distance: Melee 8
      effects:
        - roll: Power Roll + 2
          tier1: 2 damage; [pull](../../../movement/forced-movement.md) 1, or the tonguer can [shift](../../../movement/shifting.md) 1 square toward the target
          tier2: 4 damage; [pull](../../../movement/forced-movement.md) 2, or the tonguer [shifts](../../../movement/shifting.md) up to 2 squares toward the target
          tier3: 5 damage; [pull](../../../movement/forced-movement.md) 3, or the tonguer [shifts](../../../movement/shifting.md) up to 3 squares toward the target
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Tonguelash
      target: One creature or object per minion
      type: feature
      usage: Main action
    - effects:
        - effect: While the tonguer has a tail, whenever they are [grabbed](../../../condition/grabbed.md), [prone](../../../condition/prone.md), [slowed](../../../condition/slowed.md), or [weakened](../../../condition/weakened.md), they can lose their tail to immediately end that condition, then [shift](../../../movement/shifting.md) up to 2 squares.
      feature_type: trait
      icon: ⭐️
      name: Reptilian Escape
      type: feature
free_strike: 2
intuition: 1
keywords:
    - Humanoid
    - Lizardfolk
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-tonguer
    source: mcdm.monsters.v1
might: 0
movement: Swim
name: Lizardfolk Tonguer
organization: Minion
presence: 0
reason: 0
role: Artillery
size: 1S
speed: 5
stability: 0
stamina: "3"
type: statblock
with_captain: +1 bonus to strikes
```
