---
features:
    - distance: Self
      icon: "\U0001F464"
      keywords:
        - '-'
      level: 4
      name: Big Windup
      sections:
        - label: Effect
          text: Until the start of the retainer's next turn, strikes made against the retainer gain an edge. At the start of the retainer's next turn, they gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), and any ability they use before the end of their turn that [force moves](scc.v1:mcdm.heroes.v1/movement/forced-movement) a creature can move that creature 2 additional squares.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Overhand Swat
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 8 damage
            mid: 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      sections:
        - label: Effect
          text: If the target ends any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) from this ability in a square [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the retainer's mentor, the mentor can make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Weapon
      level: 10
      name: Dizzying Sweep
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 20 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
            low: 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
            mid: 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
      sections:
        - label: Effect
          text: The retainer is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) until the end of their next turn.
      target: Each creature in the area
      usage: Main action
name: Brute Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/brute
type: featureblock
---

> **Level 4 Role Advancement Ability**

> 👤 **Big Windup**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Until the start of the retainer's next turn, strikes made against the retainer gain an edge. At the start of the retainer's next turn, they gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), and any ability they use before the end of their turn that [force moves](scc.v1:mcdm.heroes.v1/movement/forced-movement) a creature can move that creature 2 additional squares.

> **Level 7 Role Advancement Ability**

> 🗡 **Overhand Swat (Encounter)**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage
> - **12-16:** 13 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 16 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
>
> **Effect:** If the target ends any [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) from this ability in a square [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the retainer's mentor, the mentor can make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.

> **Level 10 Role Advancement Ability**

> ❇️ **Dizzying Sweep (Encounter)**
>
> | **Area, Weapon** |                  **Main action** |
> |------------------|---------------------------------:|
> | **📏 1 burst**   | **🎯 Each creature in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 10 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 14 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **17+:** 20 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4
>
> **Effect:** The retainer is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) until the end of their next turn.
