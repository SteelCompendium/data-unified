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
          text: The griffon flies up to their speed, and can make a [free strike](../../feature/common/main-actions/free-strike.md) against each creature who makes an [opportunity attack](../../rule/combat/opportunity-attack.md) against them during this movement.
      target: Self
      usage: Maneuver
    - cost: 5 Malice
      icon: ❇️
      intro: A griffon acting this turn unleashes a hideous screech at one enemy within 5 squares of them, forcing that creature to make an **Intuition test**.
      name: Piercing Cry
      power_roll:
        tiers:
            high: No effect.
            low: '[Frightened](../../condition/frightened.md) (save ends)'
            mid: '[Frightened](../../condition/frightened.md) (EoT)'
    - body: Winds bluster and blow across the encounter map. Until the end of the encounter, each creature who can't fly or isn't mounted on a flying creature takes a −3 penalty to [stability](../../rule/character/stability.md), and any [forced movement](../../movement/forced-movement.md) effect targeting such a creature moves them an additional 5 squares.
      cost: 10 Malice
      icon: "\U0001F300"
      name: Wildwinds
flavor: At the start of any griffon's turn, you can spend Malice to activate one of the following features.
kind: malice
name: Griffon Malice
scc: mcdm.monsters.v1/monster.griffon/griffon-malice
type: featureblock
---

At the start of any griffon's turn, you can spend [Malice](../../rule/monster/malice.md) to activate one of the following features.

> 👤 **Swoop (3 [Malice](../../rule/monster/malice.md))**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The griffon flies up to their speed, and can make a [free strike](../../feature/common/main-actions/free-strike.md) against each creature who makes an [opportunity attack](../../rule/combat/opportunity-attack.md) against them during this movement.

> ❇️ **Piercing Cry (5 [Malice](../../rule/monster/malice.md))**
>
> A griffon acting this turn unleashes a hideous screech at one enemy within 5 squares of them, forcing that creature to make an **Intuition test**.
>
> - **≤11:** [Frightened](../../condition/frightened.md) (save ends)
> - **12-16:** [Frightened](../../condition/frightened.md) (EoT)
> - **17+:** No effect.

> 🌀 **Wildwinds (10 [Malice](../../rule/monster/malice.md))**
>
> Winds bluster and blow across the encounter map. Until the end of the encounter, each creature who can't fly or isn't mounted on a flying creature takes a −3 penalty to [stability](../../rule/character/stability.md), and any [forced movement](../../movement/forced-movement.md) effect targeting such a creature moves them an additional 5 squares.
