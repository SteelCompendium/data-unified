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
          text: The shieldbearer blocks the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) (if [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the mentor) or throws their shield into the mentor's space. The triggering [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s damage is halved and the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects is reduced by 1. If the shieldbearer threw their shield, it bounces back to their hand.
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
          text: The shieldbearer straps their shield on their back and climbs onto their mentor's back, entering the mentor's space. While the shieldbearer is on their mentor's back, each of them gains 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) and can use Shield Block as a triggered action targeting an ally instead of the shieldbearer's mentor. Additionally, the shieldbearer moves with the mentor, and they can't use main actions, maneuvers, or move actions except to end this effect as a maneuver. The effect also ends if the shieldbearer is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) away from their mentor or knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone). If the shieldbearer is still in their mentor's space when the effect ends, they move into an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space of their choice.
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
            high: 14 damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            low: 6 damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
            mid: 10 damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      sections:
        - label: Effect
          text: If this ability is used as part of the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action, the shieldbearer gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) that can be used immediately.
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
> **Effect:** The shieldbearer blocks the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) (if [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the mentor) or throws their shield into the mentor's space. The triggering [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s damage is halved and the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects is reduced by 1. If the shieldbearer threw their shield, it bounces back to their hand.

> **Level 7 Retainer Advancement Ability**

> 🗡 **Living Backpack**
>
> | **Melee**      |                  **Main action** |
> |----------------|---------------------------------:|
> | **📏 Melee 1** | **🎯 The shieldbearer's mentor** |
>
> **Effect:** The shieldbearer straps their shield on their back and climbs onto their mentor's back, entering the mentor's space. While the shieldbearer is on their mentor's back, each of them gains 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) and can use Shield Block as a triggered action targeting an ally instead of the shieldbearer's mentor. Additionally, the shieldbearer moves with the mentor, and they can't use main actions, maneuvers, or move actions except to end this effect as a maneuver. The effect also ends if the shieldbearer is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) away from their mentor or knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone). If the shieldbearer is still in their mentor's space when the effect ends, they move into an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space of their choice.

> **Level 10 Retainer Advancement Ability**

> 🗡 **Let's Go Sledding (Encounter)**
>
> | **Charge, Melee, Strike, Weapon** |      **Main action** |
> |-----------------------------------|---------------------:|
> | **📏 Melee 1**                    | **🎯 Three enemies** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 6 damage; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **12-16:** 10 damage; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
> - **17+:** 14 damage; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
>
> **Effect:** If this ability is used as part of the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action, the shieldbearer gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) that can be used immediately.
