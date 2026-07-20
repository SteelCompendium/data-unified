---
features:
    - distance: Ranged 5
      icon: ❗️
      keywords:
        - Ranged
        - Weapon
      level: 4
      name: Supporting Volley
      sections:
        - label: Trigger
          text: The retainer's mentor makes a strike against a creature within distance.
        - label: Effect
          text: The retainer makes a ranged [free strike](../../../feature/common/main-actions/free-strike.md) against the target.
      target: The triggering creature
      usage: Triggered action
    - cost: Encounter
      distance: 10 x 1 line within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Weapon
      level: 7
      name: Line 'Em Up
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; M < STRONG [prone](../../../condition/prone.md)
            low: 7 damage; M < WEAK [prone](../../../condition/prone.md)
            mid: 11 damage; M < AVERAGE [prone](../../../condition/prone.md)
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Ranged
        - Strike
        - Weapon
      level: 10
      name: Ricochet Shot
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 19 damage
            low: 9 damage
            mid: 14 damage
      sections:
        - label: Effect
          text: The retainer can target a second creature or object within 5 squares of the original target and that has line of effect to the original target. The retainer doesn't need line of effect to the second target but must be aware of their location.
      target: One creature or object
      usage: Main action
name: Artillery Abilities
scc: mcdm.monsters.v1/monster.retainer.role-advancement/artillery
type: featureblock
---

> **Level 4 Role Advancement Ability**

> ❗️ **Supporting Volley**
>
> | **Ranged, Weapon** |           **[Triggered action](../../../rule/combat/triggered-action.md)** |
> |--------------------|-------------------------------:|
> | **📏 Ranged 5**    | **🎯 The triggering creature** |
>
> **Trigger:** The retainer's mentor makes a strike against a creature within distance.
>
> **Effect:** The retainer makes a ranged [free strike](../../../feature/common/main-actions/free-strike.md) against the target.

> **Level 7 Role Advancement Ability**

> 🔳 **Line 'Em Up (Encounter)**
>
> | **Area, Weapon**            |               **[Main action](../../../rule/combat/turn.md)** |
> |-----------------------------|------------------------------:|
> | **📏 10 x 1 line within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage; M < WEAK [prone](../../../condition/prone.md)
> - **12-16:** 11 damage; M < AVERAGE [prone](../../../condition/prone.md)
> - **17+:** 16 damage; M < STRONG [prone](../../../condition/prone.md)

> **Level 10 Role Advancement Ability**

> 🏹 **Ricochet Shot (Encounter)**
>
> | **Ranged, Strike, Weapon** | **[Main action](../../../rule/combat/turn.md)** |
> | --- | ---:|
> | **📏 Ranged 5** | **🎯 One creature or object** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 9 damage
> - **12-16:** 14 damage
> - **17+:** 19 damage
>
> **Effect:** The retainer can target a second creature or object within 5 squares of the original target and that has line of effect to the original target. The retainer doesn't need line of effect to the second target but must be aware of their location.
