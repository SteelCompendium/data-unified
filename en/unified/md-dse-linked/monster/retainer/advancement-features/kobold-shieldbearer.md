---
features:
    - cost: Encounter
      distance: Ranged 5
      icon: ❗️
      keywords:
        - Ranged
      level: 4
      name: Shield Block
      sections:
        - label: Trigger
          text: The mentor takes damage from a strike while within distance.
        - label: Effect
          text: The shieldbearer blocks the [strike](../../../rule/combat/strike.md) (if [adjacent](../../../rule/combat/adjacent.md) to the mentor) or throws their shield into the mentor's space. The triggering [strike](../../../rule/combat/strike.md)'s damage is halved and the [potency](../../../rule/character/potency.md) of any [potency](../../../rule/character/potency.md) effects is reduced by 1. If the shieldbearer threw their shield, it bounces back to their hand.
      target: The shieldbearer's mentor
      usage: Triggered action
    - distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Melee
      level: 7
      name: Living Backpack
      sections:
        - label: Effect
          text: The shieldbearer straps their shield on their back and climbs onto their mentor's back, entering the mentor's space. While the shieldbearer is on their mentor's back, each of them gains 10 [temporary Stamina](../../../rule/health/temporary-stamina.md) and can use Shield Block as a triggered action targeting an ally instead of the shieldbearer's mentor. Additionally, the shieldbearer moves with the mentor, and they can't use main actions, maneuvers, or move actions except to end this effect as a maneuver. The effect also ends if the shieldbearer is [force moved](../../../movement/forced-movement.md) away from their mentor or knocked [prone](../../../condition/prone.md). If the shieldbearer is still in their mentor's space when the effect ends, they move into an [adjacent](../../../rule/combat/adjacent.md) unoccupied space of their choice.
      target: The shieldbearer's mentor
      usage: Main action
    - cost: Encounter
      distance: Melee 1
      icon: "\U0001F5E1"
      keywords:
        - Charge
        - Melee
        - Strike
        - Weapon
      level: 10
      name: Let's Go Sledding
      power_roll:
        formula: + highest characteristic
        tiers:
            high: 14 damage; M < STRONG [prone](../../../condition/prone.md)
            low: 6 damage; M < WEAK [prone](../../../condition/prone.md)
            mid: 10 damage; M < AVERAGE [prone](../../../condition/prone.md)
      sections:
        - label: Effect
          text: If this ability is used as part of the [Charge](../../../feature/common/main-actions/charge.md) main action, the shieldbearer gains 2 [surges](../../../rule/resource/surge.md) that can be used immediately.
      target: Three enemies
      usage: Main action
file_basename: kobold-shieldbearer
file_dpath: monster/retainer/advancement-features
item_id: kobold-shieldbearer
item_name: Kobold Shieldbearer Advancement Features
name: Kobold Shieldbearer Advancement Features
scc: mcdm.monsters.v1/monster.retainer.advancement-features/kobold-shieldbearer
source: mcdm.monsters.v1
type: featureblock
---

> **Level 4 Retainer Advancement Ability**

> ❗️ **Shield Block (Encounter)**
>
> | **Ranged**      |             **Triggered action** |
> |-----------------|---------------------------------:|
> | **📏 Ranged 5** | **🎯 The shieldbearer's mentor** |
>
> **Trigger:** The mentor takes damage from a strike while within distance.
>
> **Effect:** The shieldbearer blocks the [strike](../../../rule/combat/strike.md) (if [adjacent](../../../rule/combat/adjacent.md) to the mentor) or throws their shield into the mentor's space. The triggering [strike](../../../rule/combat/strike.md)'s damage is halved and the [potency](../../../rule/character/potency.md) of any [potency](../../../rule/character/potency.md) effects is reduced by 1. If the shieldbearer threw their shield, it bounces back to their hand.

> **Level 7 Retainer Advancement Ability**

> 🗡 **Living Backpack**
>
> | **Melee**      |                  **Main action** |
> |----------------|---------------------------------:|
> | **📏 Melee 1** | **🎯 The shieldbearer's mentor** |
>
> **Effect:** The shieldbearer straps their shield on their back and climbs onto their mentor's back, entering the mentor's space. While the shieldbearer is on their mentor's back, each of them gains 10 [temporary Stamina](../../../rule/health/temporary-stamina.md) and can use Shield Block as a triggered action targeting an ally instead of the shieldbearer's mentor. Additionally, the shieldbearer moves with the mentor, and they can't use main actions, maneuvers, or move actions except to end this effect as a maneuver. The effect also ends if the shieldbearer is [force moved](../../../movement/forced-movement.md) away from their mentor or knocked [prone](../../../condition/prone.md). If the shieldbearer is still in their mentor's space when the effect ends, they move into an [adjacent](../../../rule/combat/adjacent.md) unoccupied space of their choice.

> **Level 10 Retainer Advancement Ability**

> 🗡 **Let's Go Sledding (Encounter)**
>
> | **Charge, Melee, Strike, Weapon** |      **Main action** |
> |-----------------------------------|---------------------:|
> | **📏 Melee 1**                    | **🎯 Three enemies** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 damage; M < WEAK [prone](../../../condition/prone.md)
> - **12-16:** 10 damage; M < AVERAGE [prone](../../../condition/prone.md)
> - **17+:** 14 damage; M < STRONG [prone](../../../condition/prone.md)
>
> **Effect:** If this ability is used as part of the [Charge](../../../feature/common/main-actions/charge.md) main action, the shieldbearer gains 2 [surges](../../../rule/resource/surge.md) that can be used immediately.
