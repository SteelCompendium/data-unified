---
features:
    - cost: Encounter
      distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
      level: 4
      name: Watch Out!
      sections:
        - label: Trigger
          text: The target takes damage from a strike.
        - label: Effect
          text: The retainer [pushes](../../../movement/forced-movement.md) the target or the attacking creature up to 2 squares. If that moves the mentor out of distance of the strike, the strike has no effect.
      target: The retainer's mentor
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: It's Me You Want!
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; [taunted](../../../condition/taunted.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 7 damage; [taunted](../../../condition/taunted.md) (EoT)
            mid: 11 damage; [taunted](../../../condition/taunted.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Two creatures
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Weapon
      level: 10
      name: Last Stand
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 17 damage
            low: 8 damage
            mid: 13 damage
      sections:
        - label: Effect
          text: The retainer and their mentor each gain 10 [temporary Stamina](../../../rule/health/temporary-stamina.md). Additionally, each [winded](../../../rule/health/winded.md) ally within 2 squares of the retainer can spend a [Recovery](../../../rule/health/recoveries.md).
      target: One enemy
      usage: Main action
name: Defender Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/defender
type: featureblock
---

> **Level 4 Role Advancement Ability**

> ❗️ **Watch Out! (Encounter)**
>
> | **Melee**      |         **[Triggered action](../../../rule/combat/triggered-action.md)** |
> |----------------|-----------------------------:|
> | **📏 Melee 1** | **🎯 The retainer's mentor** |
>
> **Trigger:** The target takes damage from a strike.
>
> **Effect:** The retainer [pushes](../../../movement/forced-movement.md) the target or the attacking creature up to 2 squares. If that moves the mentor out of distance of the strike, the strike has no effect.

> **Level 7 Role Advancement Ability**

> 🗡 **It's Me You Want! (Encounter)**
>
> | **Melee, Strike, Weapon** |      **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|---------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage; [taunted](../../../condition/taunted.md) (EoT)
> - **12-16:** 11 damage; [taunted](../../../condition/taunted.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 16 damage; [taunted](../../../condition/taunted.md) ([save](../../../rule/general/saving-throw.md) ends)

> **Level 10 Role Advancement Ability**

> 🗡 **Last Stand (Encounter)**
>
> | **Melee, Weapon** |  **[Main action](../../../rule/combat/turn.md)** |
> |-------------------|-----------------:|
> | **📏 Melee 1**    | **🎯 One enemy** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 damage
> - **12-16:** 13 damage
> - **17+:** 17 damage
>
> **Effect:** The retainer and their mentor each gain 10 [temporary Stamina](../../../rule/health/temporary-stamina.md). Additionally, each [winded](../../../rule/health/winded.md) ally within 2 squares of the retainer can spend a [Recovery](../../../rule/health/recoveries.md).
