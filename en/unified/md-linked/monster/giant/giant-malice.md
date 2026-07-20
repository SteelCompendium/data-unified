---
features:
    - cost: 3 Malice
      distance: 4 cube within 10
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Hurl Landscape
      power_roll:
        tiers:
            high: 9 damage
            low: 18 damage; [prone](../../condition/prone.md) and can't stand (save ends)
            mid: 14 damage; [prone](../../condition/prone.md)
      sections:
        - label: Effect
          text: A giant unearths a structure, hazard, or chunk of the encounter map and launches it to fill the area. Each target makes an **Agility test**.
      target: Each enemy in the area
      usage: Main action
    - body: Each giant in the encounter takes a deep breath and yells, [pushing](../../movement/forced-movement.md) each creature within 3 squares of them up to 10 squares. A creature who can be pushed by more than one giant is pushed by one giant of your choice.
      cost: 5 Malice
      icon: ❇️
      name: Bellow
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: A giant creates a fissure along the ground, either in a 15 x 2 line within 1 or a 10 x 3 line within 2, and that opens up to a depth of 6 squares. Each giant in the area can [shift](../../movement/shifting.md) into the nearest unoccupied space outside the fissure. Each non-giant in the area makes an **Agility test**.
      name: Titanic Tear
      power_roll:
        tiers:
            high: The target can [shift](../../movement/shifting.md) into the nearest unoccupied space outside the fissure.
            low: 10 damage; the target falls into the fissure, and is [prone](../../condition/prone.md) and can't stand (EoT)
            mid: 10 damage; the target is [prone](../../condition/prone.md) and hanging onto the edge of the fissure
flavor: At the start of any giant's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Giant Malice
scc: mcdm.monsters.v1/monster.giant/giant-malice
type: featureblock
---

At the start of any giant's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> 🔳 **Hurl Landscape (3 [Malice](../../rule/monster/malice.md))**
>
> | **Area, Ranged, Weapon** |               **[Main action](../../rule/combat/turn.md)** |
> |--------------------------|------------------------------:|
> | **📏 4 cube within 10**  | **🎯 Each enemy in the area** |
>
> **Effect:** A giant unearths a structure, hazard, or chunk of the encounter map and launches it to fill the area. Each target makes an **Agility test**.
>
> - **≤11:** 18 damage; [prone](../../condition/prone.md) and can't stand (save ends)
> - **12-16:** 14 damage; [prone](../../condition/prone.md)
> - **17+:** 9 damage

> ❇️ **Bellow (5 [Malice](../../rule/monster/malice.md))**
>
> Each giant in the encounter takes a deep breath and yells, [pushing](../../movement/forced-movement.md) each creature within 3 squares of them up to 10 squares. A creature who can be pushed by more than one giant is pushed by one giant of your choice.

> 🔳 **Titanic Tear (7 [Malice](../../rule/monster/malice.md))**
>
> A giant creates a fissure along the ground, either in a 15 x 2 line within 1 or a 10 x 3 line within 2, and that opens up to a depth of 6 squares. Each giant in the area can [shift](../../movement/shifting.md) into the nearest unoccupied space outside the fissure. Each non-giant in the area makes an **Agility test**.
>
> - **≤11:** 10 damage; the target falls into the fissure, and is [prone](../../condition/prone.md) and can't stand (EoT)
> - **12-16:** 10 damage; the target is [prone](../../condition/prone.md) and hanging onto the edge of the fissure
> - **17+:** The target can [shift](../../movement/shifting.md) into the nearest unoccupied space outside the fissure.
