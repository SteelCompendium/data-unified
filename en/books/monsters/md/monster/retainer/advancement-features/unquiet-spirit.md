---
features:
    - cost: Encounter
      distance: Ranged 10
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 4
      name: Enervating Curse
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 14 corruption damage; the target has 3 levels of drain
            low: 6 corruption damage; the target has 1 level of drain
            mid: 10 corruption damage; the target has 2 levels of drain
      sections:
        - label: Effect
          text: The next creature to make a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against the target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) for each level of drain, which must be used on that [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 7
      name: Ectoplasm
      power_roll:
        formula: + highest characteristic
        tiers:
            high: A < STRONG [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            low: A < WEAK [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
            mid: A < AVERAGE [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
      target: Each enemy in the area
      usage: Main action
    - cost: Encounter
      distance: Ranged 5
      icon: "\U0001F3F9"
      keywords:
        - Magic
        - Ranged
        - Strike
      level: 10
      name: Death Phase
      sections:
        - label: Effect
          text: If the target has P < STRONG, they are phased until the end of their next turn. A phased target gains the unquiet spirit's Corruptive Phasing trait and can [fly](scc.v1:mcdm.heroes.v1/movement/fly). They are visible but can't affect or be affed by other creatures or objects. A willing creature not subject to the ability's [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) can choose to automatically be affected.
      target: One creature
      usage: Main action
name: Unquiet Spirit Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/unquiet-spirit
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> 🏹 **Enervating Curse (Encounter)**
>
> | **Magic, Ranged, Strike** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------:|
> | **📏 Ranged 10**          | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 corruption damage; the target has 1 level of drain
> - **12-16:** 10 corruption damage; the target has 2 levels of drain
> - **17+:** 14 corruption damage; the target has 3 levels of drain
>
> **Effect:** The next creature to make a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against the target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) for each level of drain, which must be used on that [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).

> **Level 7 Retainer Advancement Ability**

> 🔳 **Ectoplasm (Encounter)**
>
> | **Area, Magic**        |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |------------------------|------------------------------:|
> | **📏 3 cube within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** A < WEAK [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **12-16:** A < AVERAGE [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)
> - **17+:** A < STRONG [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) ([save](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) ends)

> **Level 10 Retainer Advancement Ability**

> 🏹 **Death Phase (Encounter)**
>
> | **Magic, Ranged, Strike** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------:|
> | **📏 Ranged 5**           | **🎯 One creature** |
>
> **Effect:** If the target has P < STRONG, they are phased until the end of their next turn. A phased target gains the unquiet spirit's Corruptive Phasing trait and can [fly](scc.v1:mcdm.heroes.v1/movement/fly). They are visible but can't affect or be affed by other creatures or objects. A willing creature not subject to the ability's [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) can choose to automatically be affected.
