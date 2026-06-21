---
features:
    - cost: 3 Malice
      distance: Self
      icon: ❗️
      keywords:
        - '-'
      name: Aftershock
      sections:
        - label: Trigger
          text: A creature deals damage to the kingfissure worm or one of their tongues.
        - label: Effect
          text: Each creature within 5 squares of the kingfissure worm takes 5 damage, and if they have A < 4 they are knocked [prone](../../condition/prone.md). The kingfissure worm can use this ability only once per round.
      target: Self
      usage: Free triggered action
    - body: The kingfissure worm takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The kingfissure worm loses 35 [Stamina](../../rule/health/stamina.md) and regrows one tongue, to a maximum of three tongues. The worm is then [dazed](../../condition/dazed.md) until the end of their turn.
      cost: 5 Malice
      icon: "\U0001F464"
      name: Spontaneous Regeneration
    - cost: 7 Malice
      distance: 5 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      name: Megaquake
      power_roll:
        formula: + 5
        tiers:
            high: 17 damage; M < 5 [slide](../../movement/forced-movement.md) 5
            low: 8 damage; M < 3 [slide](../../movement/forced-movement.md) 5
            mid: 13 damage; M < 4 [slide](../../movement/forced-movement.md) 5
      sections:
        - label: Effect
          text: Until the end of the next round, each target takes a −3 penalty to stability, treats all terrain as [difficult terrain](../../movement/difficult-terrain.md), and takes 10 damage whenever they are knocked [prone](../../condition/prone.md).
      target: Each enemy and object in the area
      usage: Main action
file_basename: kingfissure-worm-malice
file_dpath: monster/kingfissure-worm
flavor: At the start of a kingfissure worm's turn or when an action's trigger occurs, you can spend Malice to activate one of the following features.
item_id: kingfissure-worm-malice
item_name: Kingfissure Worm Malice
kind: malice
name: Kingfissure Worm Malice
scc: mcdm.monsters.v1/monster.kingfissure-worm/kingfissure-worm-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of a kingfissure worm's turn or when an action's trigger occurs, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> ❗️ **Aftershock (3 [Malice](../../rule/monster/malice.md))**
>
> | **-**       | **Free triggered action** |
> |-------------|--------------------------:|
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** A creature deals damage to the kingfissure worm or one of their tongues.
>
> **Effect:** Each creature within 5 squares of the kingfissure worm takes 5 damage, and if they have A < 4 they are knocked [prone](../../condition/prone.md). The kingfissure worm can use this ability only once per round.

> ☠️ **Solo Action (5 [Malice](../../rule/monster/malice.md))**
>
> The kingfissure worm takes an additional main action on their turn. They can use this feature even if they are [dazed](../../condition/dazed.md).

> 👤 **Spontaneous Regeneration (5 [Malice](../../rule/monster/malice.md))**
>
> The kingfissure worm loses 35 [Stamina](../../rule/health/stamina.md) and regrows one tongue, to a maximum of three tongues. The worm is then [dazed](../../condition/dazed.md) until the end of their turn.

> ❇️ **Megaquake (7 [Malice](../../rule/monster/malice.md))**
>
> | **Area, Weapon** |                          **Main action** |
> |------------------|-----------------------------------------:|
> | **📏 5 burst**   | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 5:**
>
> - **≤11:** 8 damage; M < 3 [slide](../../movement/forced-movement.md) 5
> - **12-16:** 13 damage; M < 4 [slide](../../movement/forced-movement.md) 5
> - **17+:** 17 damage; M < 5 [slide](../../movement/forced-movement.md) 5
>
> **Effect:** Until the end of the next round, each target takes a −3 penalty to stability, treats all terrain as [difficult terrain](../../movement/difficult-terrain.md), and takes 10 damage whenever they are knocked [prone](../../condition/prone.md).
