---
features:
    - cost: 3 Malice
      icon: ⭐️
      intro: Each orc [shifts](scc:mcdm.heroes.v1/movement/shifting) up to their speed, moving through enemy spaces if they can. Each enemy passed through during this movement makes a **Might test**.
      name: Overwhelming March
      power_roll:
        tiers:
            high: '[Push](scc:mcdm.heroes.v1/movement/forced-movement) 2'
            low: 6 damage; [prone](scc:mcdm.heroes.v1/condition/prone)
            mid: 4 damage; [prone](scc:mcdm.heroes.v1/condition/prone)
    - body: An orc acting this turn summons 2 **mohlers** out of the ground, who dig a trench that is a 10 x 1 line within 10 squares when they appear. The trench is 2 squares deep and is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain). The trench can't be created directly underneath creatures.
      cost: 5 Malice
      icon: "\U0001F533"
      name: Mohler Trench
    - cost: 7 Malice
      icon: "\U0001F533"
      intro: The ground shakes as a group of mohlers dig a 5 cube pit beneath an area where at least one creature is on the ground. The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain). Each orc in the area can [shift](scc:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit before it is completed. Each nonorc in the area makes an **Agility test**.
      name: Mohler Cavity
      power_roll:
        tiers:
            high: The target can [shift](scc:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit.
            low: 4 damage; the target falls; [prone](scc:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
            mid: 4 damage; the target falls
flavor: At the start of any orc's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Orc Malice
scc: mcdm.monsters.v1/monster.orc/orc-malice
type: featureblock
---

At the start of any orc's turn, you can spend [Malice](scc:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> ⭐️ **Overwhelming March (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Each orc [shifts](scc:mcdm.heroes.v1/movement/shifting) up to their speed, moving through enemy spaces if they can. Each enemy passed through during this movement makes a **Might test**.
>
> - **≤11:** 6 damage; [prone](scc:mcdm.heroes.v1/condition/prone)
> - **12-16:** 4 damage; [prone](scc:mcdm.heroes.v1/condition/prone)
> - **17+:** [Push](scc:mcdm.heroes.v1/movement/forced-movement) 2

> 🔳 **Mohler Trench (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> An orc acting this turn summons 2 **mohlers** out of the ground, who dig a trench that is a 10 x 1 line within 10 squares when they appear. The trench is 2 squares deep and is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain). The trench can't be created directly underneath creatures.

> 🔳 **Mohler Cavity (7 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> The ground shakes as a group of mohlers dig a 5 cube pit beneath an area where at least one creature is on the ground. The area is [difficult terrain](scc:mcdm.heroes.v1/movement/difficult-terrain). Each orc in the area can [shift](scc:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit before it is completed. Each nonorc in the area makes an **Agility test**.
>
> - **≤11:** 4 damage; the target falls; [prone](scc:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
> - **12-16:** 4 damage; the target falls
> - **17+:** The target can [shift](scc:mcdm.heroes.v1/movement/shifting) into the nearest unoccupied space outside the pit.
