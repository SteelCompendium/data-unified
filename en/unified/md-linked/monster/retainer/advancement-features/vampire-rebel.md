---
features:
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
        - Strike
        - Weapon
      level: 7
      name: Blood Surge
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 7 damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 11 damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      sections:
        - label: Effect
          text: Before the [strike](../../../rule/combat/strike.md), the vampire rebel [shifts](../../../movement/shifting.md) up to their speed. If the vampire rebel has [temporary Stamina](../../../rule/health/temporary-stamina.md), they can expend it, dealing an extra 2 corruption damage for each point of [temporary Stamina](../../../rule/health/temporary-stamina.md) expended this way.
      target: One creature
      usage: Main action
    - cost: Encounter
      distance: 3 cube within 1
      icon: "\U0001F533"
      keywords:
        - Area
        - Magic
      level: 10
      name: Exsanguination
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 16 corruption damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            low: 7 corruption damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
            mid: 11 corruption damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
      target: Each enemy in the area
      usage: Main action
name: Vampire Rebel Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/vampire-rebel
type: featureblock
---

> **Level 7 Retainer Advancement Ability**

> 🗡 **Blood Surge (Encounter)**
>
> | **Melee, Strike, Weapon** |     **[Main action](../../../rule/combat/turn.md)** |
> |---------------------------|--------------------:|
> | **📏 Melee 1**            | **🎯 One creature** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 11 damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 16 damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
>
> **Effect:** Before the [strike](../../../rule/combat/strike.md), the vampire rebel [shifts](../../../movement/shifting.md) up to their speed. If the vampire rebel has [temporary Stamina](../../../rule/health/temporary-stamina.md), they can expend it, dealing an extra 2 corruption damage for each point of [temporary Stamina](../../../rule/health/temporary-stamina.md) expended this way.

> **Level 10 Retainer Advancement Ability**

> 🔳 **Exsanguination (Encounter)**
>
> | **Area, Magic**        |               **[Main action](../../../rule/combat/turn.md)** |
> |------------------------|------------------------------:|
> | **📏 3 cube within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 7 corruption damage; M < WEAK [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **12-16:** 11 corruption damage; M < AVERAGE [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
> - **17+:** 16 corruption damage; M < STRONG [bleeding](../../../condition/bleeding.md) ([save](../../../rule/general/saving-throw.md) ends)
