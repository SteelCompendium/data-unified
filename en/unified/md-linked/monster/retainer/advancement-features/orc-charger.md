---
features:
    - cost: Encounter
      distance: Self
      icon: "\U0001F464"
      keywords:
        - Self
      level: 4
      name: Blood Oath
      sections:
        - label: Effect
          text: Until the start of the charger's next turn, the charger and their mentor each have [temporary Stamina](../../../rule/health/temporary-stamina.md) equal to their Recovery value and a +2 bonus to speed, and they each gain an edge on reactive tests.
      target: Self
      usage: Maneuver
    - cost: Encounter
      distance: Self; See below
      icon: "\U0001F464"
      level: 7
      name: Mow 'Em Down
      sections:
        - label: Effect
          text: The charger moves in a straight line up to their speed. During this move, they ignore enemy [free strikes](../../../feature/common/main-actions/free-strike.md), and they can make a melee [free strike](../../../feature/common/main-actions/free-strike.md) against any creature they move [adjacent](../../../rule/combat/adjacent.md) to.
      target: Self
      usage: Main action
    - cost: Encounter
      distance: 2 burst
      icon: ❇️
      keywords:
        - Area
        - Psionic
      level: 10
      name: Vein Burst
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 24 psychic damage
            low: 12 psychic damage
            mid: 18 psychic damage
      sections:
        - label: Effect
          text: The charger takes psychic damage equal to the number of enemies affected. This damage can't be reducetd in any way.
      target: Each enemy in the area
      usage: Main action
name: Orc Charger Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/orc-charger
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 👤 **Blood Oath (Encounter)**
>
> | **Self**    | **[Maneuver](../../../rule/combat/turn.md)** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Until the start of the charger's next turn, the charger and their mentor each have [temporary Stamina](../../../rule/health/temporary-stamina.md) equal to their Recovery value and a +2 bonus to speed, and they each gain an edge on reactive tests.

> **Level 7 Retainer Advancement Ability**

> 👤 **Mow 'Em Down (Encounter)**
>
> | **-**                  | **[Main action](../../../rule/combat/turn.md)** |
> |------------------------|----------------:|
> | **📏 Self; See below** |     **🎯 Self** |
>
> **Effect:** The charger moves in a straight line up to their speed. During this move, they ignore enemy [free strikes](../../../feature/common/main-actions/free-strike.md), and they can make a melee [free strike](../../../feature/common/main-actions/free-strike.md) against any creature they move [adjacent](../../../rule/combat/adjacent.md) to.

> **Level 10 Retainer Advancement Ability**

> ❇️ **Vein Burst (Encounter)**
>
> | **Area, Psionic** |               **[Main action](../../../rule/combat/turn.md)** |
> |-------------------|------------------------------:|
> | **📏 2 burst**    | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 12 psychic damage
> - **12-16:** 18 psychic damage
> - **17+:** 24 psychic damage
>
> **Effect:** The charger takes psychic damage equal to the number of enemies affected. This damage can't be reducetd in any way.
