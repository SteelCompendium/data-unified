---
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Cavalry Charge
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 11 damage
            low: 6 damage
            mid: 8 damage
      sections:
        - label: Effect
          text: If this ability is used as part of the [Charge](../../../feature/common/main-actions/charge.md) main action, the mount's rider can use a free triggered action to make a melee [free strike](../../../feature/common/main-actions/free-strike.md) against the same target.
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Range 5
      icon: "\U0001F464"
      level: 7
      name: Giddyup!
      sections:
        - label: Effect
          text: The mount [shifts](../../../movement/shifting.md) twice their speed. They can jump as part of this movement.
      target: Self
      usage: Move action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Rearing Trample
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; M < STRONG [prone](../../../condition/prone.md)
            low: 10 damage; M < WEAK [prone](../../../condition/prone.md)
            mid: 15 damage; M < AVERAGE [prone](../../../condition/prone.md)
      sections:
        - label: Effect
          text: A target knocked [prone](../../../condition/prone.md) this way or who is already [prone](../../../condition/prone.md) takes an extra 5 damage.
      target: Each enemy in the area
      usage: Main action
file_basename: mount
file_dpath: monster/retainer/role-advancement
item_id: mount
item_name: Mount Abilities
name: Mount Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/mount
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Cavalry Charge
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 11 damage
            low: 6 damage
            mid: 8 damage
      sections:
        - label: Effect
          text: If this ability is used as part of the [Charge](../../../feature/common/main-actions/charge.md) main action, the mount's rider can use a free triggered action to make a melee [free strike](../../../feature/common/main-actions/free-strike.md) against the same target.
      target: One enemy
      usage: Main action
    - cost: Encounter
      distance: Range 5
      icon: "\U0001F464"
      level: 7
      name: Giddyup!
      sections:
        - label: Effect
          text: The mount [shifts](../../../movement/shifting.md) twice their speed. They can jump as part of this movement.
      target: Self
      usage: Move action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Rearing Trample
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 damage; M < STRONG [prone](../../../condition/prone.md)
            low: 10 damage; M < WEAK [prone](../../../condition/prone.md)
            mid: 15 damage; M < AVERAGE [prone](../../../condition/prone.md)
      sections:
        - label: Effect
          text: A target knocked [prone](../../../condition/prone.md) this way or who is already [prone](../../../condition/prone.md) takes an extra 5 damage.
      target: Each enemy in the area
      usage: Main action
metadata:
    scc: mcdm.monsters.v1/monster.retainer.role-advancement/mount
    source: mcdm.monsters.v1
name: Mount Abilities
type: featureblock
```
