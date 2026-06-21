---
features:
    - body: Each wode elf who ends this turn hidden can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed while remaining hidden.
      cost: 3 Malice
      icon: ⭐️
      name: Forest Network
    - body: Until the end of the round, each wode elf gains an edge on abilities, and their strikes can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) a target up to 2 squares in addition to their usual effects. If a strike already imposes forced movement, this slide happens after that forced movement. A creature force moved by a wode elf's strike who ends this forced movement in [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.
      cost: 5 Malice
      icon: ⭐️
      name: Punishing Regrowth
    - cost: 7 Malice
      icon: "\U0001F300"
      intro: Vines rapidly grow across the entire encounter map. Each enemy in the encounter makes an **Agility test**.
      name: Vines Everywhere
      power_roll:
        tiers:
            high: No effect.
            low: 8 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
            mid: '[Restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)'
flavor: At the start of any wode elf's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Wode Elf Malice
scc: mcdm.monsters.v1/monster.elf-wode/wode-elf-malice
type: featureblock
---

At the start of any wode elf's turn, you can spend [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> ⭐️ **Forest Network (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Each wode elf who ends this turn hidden can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed while remaining hidden.

> ⭐️ **Punishing Regrowth (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Until the end of the round, each wode elf gains an edge on abilities, and their strikes can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) a target up to 2 squares in addition to their usual effects. If a strike already imposes forced movement, this slide happens after that forced movement. A creature force moved by a wode elf's strike who ends this forced movement in [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.

> 🌀 **Vines Everywhere (7 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> Vines rapidly grow across the entire encounter map. Each enemy in the encounter makes an **Agility test**.
>
> - **≤11:** 8 damage; [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **12-16:** [Restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (EoT)
> - **17+:** No effect.
