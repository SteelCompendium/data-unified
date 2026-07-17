---
agility: 1
ev: "6"
file_basename: lizardfolk-scaletooth
file_dpath: monster/lizardfolk/statblock
free_strike: 4
intuition: 0
item_id: lizardfolk-scaletooth
item_name: Lizardfolk Scaletooth
keywords:
    - Humanoid
    - Lizardfolk
level: 1
might: 2
movement: Swim
name: Lizardfolk Scaletooth
organization: Platoon
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-scaletooth
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "46"
type: statblock
---

```ds-sb
agility: 1
ev: "6"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage
          tier2: 9 damage
          tier3: 12 damage; A < 2 bleeding (save ends)
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Razor Bite
      target: One creature or object
      type: feature
      usage: Main action
    - cost: 2 Malice
      distance: Melee 2
      effects:
        - roll: Power Roll + 2
          tier1: 5 damage; [slide](../../../movement/forced-movement.md) 1
          tier2: 8 damage; [slide](../../../movement/forced-movement.md) 2; M < 1 [grabbed](../../../condition/grabbed.md) if within 2 squares of the scaletooth
          tier3: 10 damage; [slide](../../../movement/forced-movement.md) 3; M < 2 [grabbed](../../../condition/grabbed.md) if within 2 squares of the scaletooth
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Tail Whip
      target: Two creatures or objects
      type: feature
      usage: Main action
    - effects:
        - effect: While the scaletooth has a tail, whenever they are [grabbed](../../../condition/grabbed.md), [prone](../../../condition/prone.md), [slowed](../../../condition/slowed.md), or [weakened](../../../condition/weakened.md), they can lose their tail to immediately end that condition, then [shift](../../../movement/shifting.md) up to 2 squares.
      feature_type: trait
      icon: ⭐️
      name: Reptilian Escape
      type: feature
free_strike: 4
intuition: 0
keywords:
    - Humanoid
    - Lizardfolk
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-scaletooth
    source: mcdm.monsters.v1
might: 2
movement: Swim
name: Lizardfolk Scaletooth
organization: Platoon
presence: 0
reason: 0
role: Brute
size: 1M
speed: 5
stability: 0
stamina: "46"
type: statblock
```
