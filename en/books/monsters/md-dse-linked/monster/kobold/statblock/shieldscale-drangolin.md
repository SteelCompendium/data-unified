---
agility: 1
ev: "12"
file_basename: shieldscale-drangolin
file_dpath: monster/kobold/statblock
free_strike: 5
intuition: 0
item_id: shieldscale-drangolin
item_name: Shieldscale Drangolin
keywords:
    - Kobold
    - Beast
level: 1
might: 2
movement: Burrow
name: Shieldscale Drangolin
organization: Elite
presence: -2
reason: -3
role: Brute
scc: mcdm.monsters.v1/monster.kobold.statblock/shieldscale-drangolin
size: 2 or 3
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "80"
type: statblock
---

```ds-sb
agility: 1
ev: "12"
features:
    - ability_type: Signature Ability
      distance: Melee 1
      effects:
        - roll: Power Roll + 2
          tier1: 7 fire damage
          tier2: 10 fire damage
          tier3: 13 fire damage
      feature_type: ability
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Fiery Claws
      target: Two creatures or objects
      type: feature
      usage: Main action
    - cost: 5 Malice
      distance: Self; see below
      effects:
        - effect: '**Effect:** The drangolin [shifts](../../../movement/shifting.md) up to their speed and uses Fiery Claws against each creature who comes [adjacent](../../../rule/combat/adjacent.md) to them during the shift. The drangolin makes one power roll against all targets.'
      feature_type: ability
      icon: "\U0001F464"
      keywords: []
      name: Drangolin Plume
      target: Self
      type: feature
      usage: Main action
    - cost: 3 Malice
      distance: 2 burst
      effects:
        - roll: Power Roll + 2
          tier1: 6 damage; [push](../../../movement/forced-movement.md) 1; A < 0 [prone](../../../condition/prone.md)
          tier2: 8 damage; [push](../../../movement/forced-movement.md) 3; A < 0 [prone](../../../condition/prone.md)
          tier3: 11 damage; [push](../../../movement/forced-movement.md) 5; A < 0 [prone](../../../condition/prone.md)
      feature_type: ability
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Erupt
      target: Each creature in the area
      type: feature
      usage: Main action
    - effects:
        - effect: Any ally [adjacent](../../../rule/combat/adjacent.md) to the drangolin has concealment.
      feature_type: trait
      icon: ⭐️
      name: Ashen Cloud
      type: feature
    - effects:
        - effect: When the drangolin burrows, each [adjacent](../../../rule/combat/adjacent.md) size 1S or smaller ally can move with them.
      feature_type: trait
      icon: ⭐️
      name: Burrow Bond
      type: feature
free_strike: 5
intuition: 0
keywords:
    - Kobold
    - Beast
level: 1
metadata:
    scc: mcdm.monsters.v1/monster.kobold.statblock/shieldscale-drangolin
    source: mcdm.monsters.v1
might: 2
movement: Burrow
name: Shieldscale Drangolin
organization: Elite
presence: -2
reason: -3
role: Brute
size: 2 or 3
speed: 7
stability: 0
stamina: "80"
type: statblock
```
