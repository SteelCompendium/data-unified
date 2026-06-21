---
features:
    - body: The olothec takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
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
            high: 20 psychic damage; A < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
            low: 11 psychic damage; A < 2 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
            mid: 17 psychic damage; A < 3 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      sections:
        - label: Effect
          text: The olothec can [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) a target [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them. While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, a target can't make [saving throws](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) to end any other effects, and the olothec has a double edge on strikes against them.
      target: One slimed, transformed, or devolved creature
      usage: Main action
    - body: The olothec broadcasts their memory of the universe in its primordial state—a sweeping cacophony of transcendental irrationality and unceasing change. Until the end of the encounter, any creature who starts their turn within 3 squares of the olothec and has R < 3 is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the end of their next turn).
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

At the start of an olothec's turn, you can spend Malice to activate one of the following features.

> ☠️ **Solo Action (4 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The olothec takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).

> 🗡 **Writhing Envelopment (4 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Strike, Weapon** |                                      **Main action** |
> |---------------------------|-----------------------------------------------------:|
> | **📏 Melee 3**            | **🎯 One slimed, transformed, or devolved creature** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 psychic damage; A < 2 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 17 psychic damage; A < 3 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 20 psychic damage; A < 4 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
>
> **Effect:** The olothec can [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) a target [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them. While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, a target can't make [saving throws](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) to end any other effects, and the olothec has a double edge on strikes against them.

> ❇️ **Memory of Chaos (6 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The olothec broadcasts their memory of the universe in its primordial state—a sweeping cacophony of transcendental irrationality and unceasing change. Until the end of the encounter, any creature who starts their turn within 3 squares of the olothec and has R < 3 is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the end of their next turn).
