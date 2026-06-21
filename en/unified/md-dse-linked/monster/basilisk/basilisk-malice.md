---
features:
    - body: A basilisk acting this turn can [burrow](../../movement/burrow.md) until the start of their next turn, and moves up to their speed. They have damage immunity 2 while underground. The basilisk can burrow through stone, but can't drag other creatures underground when they do so. At the start of each of the basilisk's turns, the Director can spend 1 [Malice](../../rule/monster/malice.md) to let the basilisk continue burrowing.
      cost: 3+ Malice
      icon: ⭐️
      name: Stone Swim
    - cost: 5 Malice
      distance: 3 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      name: Upchuck
      power_roll:
        formula: + 2
        tiers:
            high: 4 damage; A < 2 5 damage, [prone](../../condition/prone.md) and can't stand (save ends)
            low: 4 damage
            mid: 4 damage; A < 1 2 damage, [prone](../../condition/prone.md)
      sections:
        - label: Effect
          text: The basilisk spits up a chunk of partly digested stone.
      target: Each enemy in the area
      usage: Main action
    - body: A basilisk spews reflective spittle across an adjacent vertical surface in a 3-square-by-3-square area. The basilisk can use their Petrifying Eye Beams ability to target a square in the area, causing the area and distance of that ability to become a 20 x 3 line within 1 square of the wall.
      cost: 7 Malice
      icon: "\U0001F533"
      name: Walleye
file_basename: basilisk-malice
file_dpath: monster/basilisk
flavor: At the start of any basilisk's turn, you can spend Malice to activate one of the following features.
item_id: basilisk-malice
item_name: Basilisk Malice
kind: malice
name: Basilisk Malice
scc: mcdm.monsters.v1/monster.basilisk/basilisk-malice
source: mcdm.monsters.v1
type: featureblock
---

At the start of any basilisk's turn, you can spend Malice to activate one of the following features.

> ⭐️ **Stone Swim (3+ [Malice](../../rule/monster/malice.md))**
>
> A basilisk acting this turn can [burrow](../../movement/burrow.md) until the start of their next turn, and moves up to their speed. They have damage immunity 2 while underground. The basilisk can burrow through stone, but can't drag other creatures underground when they do so. At the start of each of the basilisk's turns, the Director can spend 1 [Malice](../../rule/monster/malice.md) to let the basilisk continue burrowing.

> 🔳 **Upchuck (5 [Malice](../../rule/monster/malice.md))**
>
>
> | **Area, Weapon**        |               **Main action** |
> |-------------------------|------------------------------:|
> | **📏 3 cube within 10** | **🎯 Each enemy in the area** |
>
> **Effect:** The basilisk spits up a chunk of partly digested stone.
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 4 damage; A < 1 2 damage, [prone](../../condition/prone.md)
> - **17+:** 4 damage; A < 2 5 damage, [prone](../../condition/prone.md) and can't stand (save ends)

> 🔳 **Walleye (7 [Malice](../../rule/monster/malice.md))**
>
> A basilisk spews reflective spittle across an adjacent vertical surface in a 3-square-by-3-square area. The basilisk can use their Petrifying Eye Beams ability to target a square in the area, causing the area and distance of that ability to become a 20 x 3 line within 1 square of the wall.
