---
features:
    - cost: 3 Malice
      icon: ⭐️
      intro: Each orc [shifts](../../movement/shifting.md) up to their speed, moving through enemy spaces if they can. Each enemy passed through during this movement makes a **Might test**.
      name: Overwhelming March
      power_roll:
        tiers:
            high: '[Push](../../movement/forced-movement.md) 2'
            low: 6 damage; [prone](../../condition/prone.md)
            mid: 4 damage; [prone](../../condition/prone.md)
    - body: An orc acting this turn summons 2 **mohlers** out of the ground, who dig a trench that is a 10 x 1 line within 10 squares when they appear. The trench is 2 squares deep and is [difficult terrain](../../movement/difficult-terrain.md). The trench can't be created directly underneath creatures.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Mohler Trench
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: The ground shakes as a group of mohlers dig a 5 cube pit beneath an area where at least one creature is on the ground. The area is [difficult terrain](../../movement/difficult-terrain.md). Each orc in the area can [shift](../../movement/shifting.md) into the nearest unoccupied space outside the pit before it is completed. Each nonorc in the area makes an **Agility test**.
      name: Mohler Cavity
      power_roll:
        tiers:
            high: The target can [shift](../../movement/shifting.md) into the nearest unoccupied space outside the pit.
            low: 4 damage; the target falls; [prone](../../condition/prone.md) and can't stand (EoT)
            mid: 4 damage; the target falls
flavor: At the start of any orc's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Orc Malice
scc: mcdm.monsters.v1/monster.orc/orc-malice
type: featureblock
---

At the start of any orc's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> ⭐️ **Overwhelming March (3 [Malice](../../rule/monster/malice.md))**
>
> Each orc [shifts](../../movement/shifting.md) up to their speed, moving through enemy spaces if they can. Each enemy passed through during this movement makes a **Might test**.
>
> - **≤11:** 6 damage; [prone](../../condition/prone.md)
> - **12-16:** 4 damage; [prone](../../condition/prone.md)
> - **17+:** [Push](../../movement/forced-movement.md) 2

> 🔳 **Mohler Trench (5 [Malice](../../rule/monster/malice.md))**
>
> An orc acting this turn summons 2 **mohlers** out of the ground, who dig a trench that is a 10 x 1 line within 10 squares when they appear. The trench is 2 squares deep and is [difficult terrain](../../movement/difficult-terrain.md). The trench can't be created directly underneath creatures.

> 🔳 **Mohler Cavity (7 [Malice](../../rule/monster/malice.md))**
>
> The ground shakes as a group of mohlers dig a 5 cube pit beneath an area where at least one creature is on the ground. The area is [difficult terrain](../../movement/difficult-terrain.md). Each orc in the area can [shift](../../movement/shifting.md) into the nearest unoccupied space outside the pit before it is completed. Each nonorc in the area makes an **Agility test**.
>
> - **≤11:** 4 damage; the target falls; [prone](../../condition/prone.md) and can't stand (EoT)
> - **12-16:** 4 damage; the target falls
> - **17+:** The target can [shift](../../movement/shifting.md) into the nearest unoccupied space outside the pit.
