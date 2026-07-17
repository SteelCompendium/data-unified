---
features:
    - body: The olothec takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 4 Malice
      icon: ☠️
      name: Solo Action
    - cost: 4 Malice
      distance: Melee 3
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Writhing Envelopment
      power_roll:
        formula: + 4
        tiers:
            high: 20 psychic damage; A < 4 [grabbed](../../condition/grabbed.md)
            low: 11 psychic damage; A < 2 [grabbed](../../condition/grabbed.md)
            mid: 17 psychic damage; A < 3 [grabbed](../../condition/grabbed.md)
      sections:
        - label: Effect
          text: The olothec can [pull](../../movement/forced-movement.md) a target [grabbed](../../condition/grabbed.md) this way [adjacent](../../rule/combat/adjacent.md) to them. While [grabbed](../../condition/grabbed.md) this way, a target can't make [saving throws](../../rule/general/saving-throw.md) to end any other effects, and the olothec has a double edge on strikes against them.
      target: One slimed, transformed, or devolved creature
      usage: Main action
    - body: The olothec broadcasts their memory of the universe in its primordial state—a sweeping cacophony of transcendental irrationality and unceasing change. Until the end of the encounter, any creature who starts their turn within 3 squares of the olothec and has R < 3 is [dazed](../../condition/dazed.md) and [slowed](../../condition/slowed.md) until the end of their next turn).
      cost: 6 Malice
      icon: ❇️
      name: Memory of Chaos
file_basename: olothec-malice
file_dpath: monster/olothec
flavor: At the start of an olothec's turn, you can spend Malice to activate one of the following features.
item_id: olothec-malice
item_name: Olothec Malice
kind: malice
name: Olothec Malice
scc: mcdm.monsters.v1/monster.olothec/olothec-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: The olothec takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 4 Malice
      icon: ☠️
      name: Solo Action
    - cost: 4 Malice
      distance: Melee 3
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      name: Writhing Envelopment
      power_roll:
        formula: + 4
        tiers:
            high: 20 psychic damage; A < 4 [grabbed](../../condition/grabbed.md)
            low: 11 psychic damage; A < 2 [grabbed](../../condition/grabbed.md)
            mid: 17 psychic damage; A < 3 [grabbed](../../condition/grabbed.md)
      sections:
        - label: Effect
          text: The olothec can [pull](../../movement/forced-movement.md) a target [grabbed](../../condition/grabbed.md) this way [adjacent](../../rule/combat/adjacent.md) to them. While [grabbed](../../condition/grabbed.md) this way, a target can't make [saving throws](../../rule/general/saving-throw.md) to end any other effects, and the olothec has a double edge on strikes against them.
      target: One slimed, transformed, or devolved creature
      usage: Main action
    - body: The olothec broadcasts their memory of the universe in its primordial state—a sweeping cacophony of transcendental irrationality and unceasing change. Until the end of the encounter, any creature who starts their turn within 3 squares of the olothec and has R < 3 is [dazed](../../condition/dazed.md) and [slowed](../../condition/slowed.md) until the end of their next turn).
      cost: 6 Malice
      icon: ❇️
      name: Memory of Chaos
flavor: At the start of an olothec's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.olothec/olothec-malice
    source: mcdm.monsters.v1
name: Olothec Malice
type: featureblock
```
