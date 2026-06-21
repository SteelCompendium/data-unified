---
features:
    - cost: Encounter
      distance: Melee 1
      icon: ❗️
      keywords:
        - Melee
      level: 4
      name: '''Scuse Me, Boss'
      sections:
        - label: Trigger
          text: The warrior's mentor is targeted by a strike while within distance.
        - label: Effect
          text: The warrior and the mentor switch places. The warrior is the strike's new target and the strike has a double bane.
      target: The warrior's mentor
      usage: Triggered action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Defensive Fighting
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage
            low: 7 damage
            mid: 11 damage
      sections:
        - label: Effect
          text: Until the start of the warrior's next turn, ability rolls against the warrior or any ally [adjacent](../../../rule/combat/adjacent.md) to the warrior have a double bane.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 1 burst
      icon: ❇️
      keywords:
        - Area
        - Charge
        - Weapon
      level: 10
      name: Whirlwind of Steel
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 24 damage
            low: 12 damage
            mid: 18 damage
      target: Each enemy in the area
      usage: Main action
name: Human Warrior Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/human-warrior
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> ❗️ **'Scuse Me, Boss (Encounter)**
>
> | **Melee**      |          **Triggered action** |
> |----------------|------------------------------:|
> | **📏 Melee 1** |   **🎯 The warrior's mentor** |
>
> **Trigger:** The warrior's mentor is targeted by a strike while within distance.
>
> **Effect:** The warrior and the mentor switch places. The warrior is the strike's new target and the strike has a double bane.

> **Level 7 Retainer Advancement Ability**

> 🗡 **Defensive Fighting (Encounter)**
>
> | **Melee, Strike, Weapon** |     **Main action** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage
> - **12-16:** 11 damage
> - **17+:** 16 damage
>
> **Effect:** Until the start of the warrior's next turn, ability rolls against the warrior or any ally [adjacent](../../../rule/combat/adjacent.md) to the warrior have a double bane.

> **Level 10 Retainer Advancement Ability**

> ❇️ **Whirlwind of Steel (Encounter)**
>
> | **Area, Charge, Weapon** |               **Main action** |
> |--------------------------|------------------------------:|
> | **📏 1 burst**           | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 12 damage
> - **12-16:** 18 damage
> - **17+:** 24 damage
