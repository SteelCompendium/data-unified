---
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 4
      name: Grab and Bite
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; M < STRONG [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
            low: 7 damage; M < WEAK [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
            mid: 11 damage; M < AVERAGE [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Death to Death
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 17 corruption damage; P < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 8 corruption damage; P < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            mid: 13 corruption damage; P < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      sections:
        - label: Effect
          text: Before making the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the servitor can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 10 squares to a space containing a dead creature, then burst out of the creature's body.
      target: One creature
      usage: Maneuver
    - cost: Encounter
      distance: 2 burst
      icon: ❗️
      keywords:
        - Area
        - Magic
      level: 10
      name: Death Miasma
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 14 corruption damage
            low: 6 corruption damage
            mid: 10 corruption damage
      sections:
        - label: Trigger
          text: The servitor is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
        - label: Effect
          text: The servitor explodes.
      target: Each enemy in the area
      usage: Free triggered action
name: Undead Servitor Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/undead-servitor
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🗡 **Grab and Bite (Encounter)**
>
> | **Melee, Strike, Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage; M < WEAK [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **12-16:** 11 damage; M < AVERAGE [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
> - **17+:** 16 damage; M < STRONG [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)

########Level 7 Retainer Advancement Ability

> 🏹 **Death to Death (Encounter)**
>
> | **Magic, Ranged, Strike** |        **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------:|
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 corruption damage; P < WEAK [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **12-16:** 13 corruption damage; P < AVERAGE [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **17+:** 17 corruption damage; P < STRONG [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
>
> **Effect:** Before making the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the servitor can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 10 squares to a space containing a dead creature, then burst out of the creature's body.

> **Level 10 Retainer Advancement Ability**

> ❗️ **Death Miasma (Encounter)**
>
> | **Area, Magic** |     **Free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-----------------|------------------------------:|
> | **📏 2 burst**  | **🎯 Each enemy in the area** |
>
> **Trigger:** The servitor is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
>
> **Effect:** The servitor explodes.
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 corruption damage
> - **12-16:** 10 corruption damage
> - **17+:** 14 corruption damage
