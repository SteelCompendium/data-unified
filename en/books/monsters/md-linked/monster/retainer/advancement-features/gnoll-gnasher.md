---
features:
    - cost: Encounter
      distance: Self
      icon: ❗️
      level: 4
      name: Frenzied Bite
      sections:
        - label: Trigger
          text: An enemy within 5 squares is reduced to 0 [Stamina](../../../rule/health/stamina.md).
        - label: Effect
          text: The gnasher moves up to their speed and can use their [signature ability](../../../rule/combat/signature-ability.md).
      target: Self
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Flurry of Fangs
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      target: Three creatures or objects
      usage: Main action
    - cost: Encounter
      distance: Self
      icon: "\U0001F464"
      level: 10
      name: Horrific Feas
      sections:
        - label: Trigger
          text: The gnasher reduces a creature to 0 [Stamina](../../../rule/health/stamina.md).
        - label: Effect
          text: The gnasher consumes part of the target's body. The gnasher can spend a [Recovery](../../../rule/health/recoveries.md), and each enemy within 5 squares of the gnasher who has I < AVERAGE is [frightened](../../../condition/frightened.md) ([save](../../../rule/general/saving-throw.md) ends).
      target: Self
      usage: Main action
name: Gnoll Gnasher Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/gnoll-gnasher
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> ❗️ **Frenzied Bite (Encounter)**
>
> | **-**       | **[Triggered action](../../../rule/combat/triggered-action.md)** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** An enemy within 5 squares is reduced to 0 [Stamina](../../../rule/health/stamina.md).
>
> **Effect:** The gnasher moves up to their speed and can use their [signature ability](../../../rule/combat/signature-ability.md).

> **Level 7 Retainer Advancement Ability**

> 🗡 **Flurry of Fangs (Encounter)**
>
> | **Melee, Strike, Weapon** |                   **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|----------------------------------:|
> | **📏 Melee 1**            | **🎯 Three creatures or objects** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage
> - **17+:** 16 damage

> **Level 10 Retainer Advancement Ability**

> 👤 **Horrific Feas (Encounter)**
>
> | **-**       | **[Main action](../../../rule/combat/turn.md)** |
> |-------------|----------------:|
> | **📏 Self** |     **🎯 Self** |
>
> **Trigger:** The gnasher reduces a creature to 0 [Stamina](../../../rule/health/stamina.md).
>
> **Effect:** The gnasher consumes part of the target's body. The gnasher can spend a [Recovery](../../../rule/health/recoveries.md), and each enemy within 5 squares of the gnasher who has I < AVERAGE is [frightened](../../../condition/frightened.md) ([save](../../../rule/general/saving-throw.md) ends).
