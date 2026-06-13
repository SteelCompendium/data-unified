---
features:
    - cost: 3 Malice
      distance: Self
      icon: "\U0001F464"
      keywords:
        - '-'
      name: Swoop
      sections:
        - label: Effect
          text: The griffon flies up to their speed, and can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each creature who makes an [opportunity attack](scc:mcdm.heroes.v1/rule.combat/opportunity-attack) against them during this movement.
      target: Self
      usage: Maneuver
    - body: A griffon acting this turn unleashes a hideous screech at one enemy within 5 squares of them, forcing that creature to make an **Intuition test**.
      cost: 5 Malice
      icon: ❇️
      name: Piercing Cry
      power_roll:
        tiers:
            high: No effect.
            low: '[Frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)'
            mid: '[Frightened](scc:mcdm.heroes.v1/condition/frightened) (EoT)'
    - body: Winds bluster and blow across the encounter map. Until the end of the encounter, each creature who can't fly or isn't mounted on a flying creature takes a −3 penalty to [stability](scc:mcdm.heroes.v1/rule.character/stability), and any [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) effect targeting such a creature moves them an additional 5 squares.
      cost: 10 Malice
      icon: "\U0001F300"
      name: Wildwinds
flavor: At the start of any griffon's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Griffon Malice
scc: mcdm.monsters.v1/monster.griffons/griffon-malice
type: featureblock
---

At the start of any griffon's turn, you can spend [Malice](scc:mcdm.monsters.v1/rule.monster/malice) to activate one of the following features.

> 👤 **Swoop (3 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The griffon flies up to their speed, and can make a [free strike](scc:mcdm.heroes.v1/feature.common.main-actions/free-strike) against each creature who makes an [opportunity attack](scc:mcdm.heroes.v1/rule.combat/opportunity-attack) against them during this movement.

> ❇️ **Piercing Cry (5 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> A griffon acting this turn unleashes a hideous screech at one enemy within 5 squares of them, forcing that creature to make an **Intuition test**.
>
> - **≤11:** [Frightened](scc:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** [Frightened](scc:mcdm.heroes.v1/condition/frightened) (EoT)
> - **17+:** No effect.

> 🌀 **Wildwinds (10 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> Winds bluster and blow across the encounter map. Until the end of the encounter, each creature who can't fly or isn't mounted on a flying creature takes a −3 penalty to [stability](scc:mcdm.heroes.v1/rule.character/stability), and any [forced movement](scc:mcdm.heroes.v1/movement/forced-movement) effect targeting such a creature moves them an additional 5 squares.
