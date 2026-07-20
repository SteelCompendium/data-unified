---
features:
    - cost: Encounter
      distance: Ranged 3
      icon: "\U0001F3F9"
      keywords:
        - Ranged
      level: 4
      name: Stim Charge
      sections:
        - label: Effect
          text: The target can spend 1 [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and has their speed doubled until the end of their next turn.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: Ranged 3
      icon: "\U0001F3F9"
      keywords:
        - Psionic
        - Ranged
        - Strike
      level: 7
      name: Mind Whelm
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 17 psychic damage; R < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: 8 psychic damage; R < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            mid: 13 psychic damage; R < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 2 burst
      icon: ❇️
      keywords:
        - Area
        - Psionic
      level: 10
      name: Psychic Short Circuit
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 21 psychic damage
            low: 11 psychic damage
            mid: 16 psychic damage
      sections:
        - label: Effect
          text: If the mind healer is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), [frightened](scc.v1:mcdm.heroes.v1/condition/frightened), or [taunted](scc.v1:mcdm.heroes.v1/condition/taunted), they can end one of those conditions and impose the same condition on one enemy in the area. Additionally, they can do the same for their mentor if the mentor is in the area and is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), [frightened](scc.v1:mcdm.heroes.v1/condition/frightened), or [taunted](scc.v1:mcdm.heroes.v1/condition/taunted).
      target: Each enemy in the area
      usage: Main action
name: Time Raider Mind Healer Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/time-raider-mind-healer
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🏹 **Stim Charge (Encounter)**
>
> | **Ranged**      |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------|--------------------:|
> | **📏 Ranged 3** | **🎯 One creature** |
>
> **Effect:** The target can spend 1 [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and has their speed doubled until the end of their next turn.

> **Level 7 Retainer Advancement Ability**

> 🏹 **Mind Whelm (Encounter)**
>
> | **Psionic, Ranged, Strike** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------------------|--------------------:|
> | **📏 Ranged 3**             | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 8 psychic damage; R < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **12-16:** 13 psychic damage; R < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **17+:** 17 psychic damage; R < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)

> **Level 10 Retainer Advancement Ability**

> ❇️ **Psychic Short Circuit (Encounter)**
>
> | **Area, Psionic** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------|------------------------------:|
> | **📏 2 burst**    | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 11 psychic damage
> - **12-16:** 16 psychic damage
> - **17+:** 21 psychic damage
>
> **Effect:** If the mind healer is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), [frightened](scc.v1:mcdm.heroes.v1/condition/frightened), or [taunted](scc.v1:mcdm.heroes.v1/condition/taunted), they can end one of those conditions and impose the same condition on one enemy in the area. Additionally, they can do the same for their mentor if the mentor is in the area and is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), [frightened](scc.v1:mcdm.heroes.v1/condition/frightened), or [taunted](scc.v1:mcdm.heroes.v1/condition/taunted).
