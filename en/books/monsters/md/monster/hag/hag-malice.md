---
features:
    - cost: 5 Malice
      distance: 10 x 1 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      name: Hag Wyrd
      power_roll:
        formula: + 3
        tiers:
            high: 11 fire damage; R < 3 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
            low: 5 fire damage; R < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
            mid: 8 fire damage; R < 2 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      sections:
        - label: Effect
          text: After making the power roll, the hag can choose to replace the damage type and condition with lightning damage and [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), or cold damage and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).
      target: Each enemy in the area
      usage: Main action
    - body: The hag takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      icon: ☠️
      name: Solo Action
    - body: The hag's hut springs to life. It enters the encounter map within 10 squares of the hag if it isn't already there and takes its turn. The hut is size 4, has 75 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and damage immunity 3, and has speed 8 from its powerful set of animal legs. This feature can't be used if the hut is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). In addition to its move action, the house can take only the following main action.
      cost: 10 Malice
      icon: "\U0001F300"
      name: House Call
    - cost: Signature
      distance: 2 cube within 2
      icon: "\U0001F533"
      keywords:
        - Area
        - Ranged
        - Weapon
      name: Kick
      power_roll:
        formula: + 3
        tiers:
            high: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            mid: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; M < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      target: Each enemy in the area
      usage: Main action
flavor: At the start of a hag's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Hag Malice
scc: mcdm.monsters.v1/monster.hag/hag-malice
type: featureblock
---

At the start of a hag's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

❇️ **Casting Curses and Bodies (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**

The hag utters terrible words that [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) each enemy within 2 squares of them up to 3 squares.

> 🔳 **Hag Wyrd (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic**             |               **Main action** |
> |-----------------------------|------------------------------:|
> | **📏 10 x 1 line within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 fire damage; R < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** 8 fire damage; R < 2 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** 11 fire damage; R < 3 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** After making the power roll, the hag can choose to replace the damage type and condition with lightning damage and [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), or cold damage and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).

> ☠️ **Solo Action (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The hag takes an additional main action on their turn. They can use this feature even if they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).

> 🌀 **House Call (10 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> The hag's hut springs to life. It enters the encounter map within 10 squares of the hag if it isn't already there and takes its turn. The hut is size 4, has 75 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and damage immunity 3, and has speed 8 from its powerful set of animal legs. This feature can't be used if the hut is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina). In addition to its move action, the house can take only the following main action.

> 🔳 **Kick (Signature Ability)**
>
> | **Area, Ranged, Weapon** |               **Main action** |
> |--------------------------|------------------------------:|
> | **📏 2 cube within 2**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 1 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4; M < 2 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5; M < 3 [prone](scc.v1:mcdm.heroes.v1/condition/prone)
