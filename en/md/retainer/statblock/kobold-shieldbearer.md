---
agility: 1
ev: '-'
free_strike: 6
intuition: 0
keywords:
    - Humanoid
    - Kobold
level: 1
might: 2
name: Kobold Shieldbearer
organization: Retainer
presence: 0
reason: 0
role: Defender
scc: mcdm.monsters.v1/retainer.statblock/kobold-shieldbearer
size: "2"
speed: 5
stability: 4
stamina: "21"
type: statblock
---

| Humanoid, Kobold  |         -         |      Level 1       |   Defender Retainer   |         EV -         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|   **2**<br>Size   |  **5**<br>Speed   | **21**<br>Stamina  |  **4**<br>Stability   | **6**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+2**<br>Might  | **+1**<br>Agility |  **0**<br>Reason   |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🗡 **Gladius (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + highest characteristic:**
>
> - **≤11:** 3 damage
> - **12-16:** 5 damage
> - **17+:** 7 damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (EoT)

> ⭐️ **Shield, Boss?**
>
> While the shieldbearer is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to their mentor, both have a +1 bonus to [stability](scc.v1:mcdm.heroes.v1/rule.character/stability), have [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover), and grant [cover](scc.v1:mcdm.heroes.v1/rule.combat/cover) to allies.

######## Level 4 Retainer Advancement Ability

> ❗️ **Shield Block (Encounter)**
>
> | **Ranged**      |             **Triggered action** |
> |-----------------|---------------------------------:|
> | **📏 Ranged 5** | **🎯 The shieldbearer's mentor** |
>
> **Trigger:** The mentor takes damage from a strike while within distance.
>
> **Effect:** The shieldbearer blocks the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) (if [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the mentor) or throws their shield into the mentor's space. The triggering [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s damage is halved and the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects is reduced by 1. If the shieldbearer threw their shield, it bounces back to their hand.

######## Level 7 Retainer Advancement Ability

> 🗡 **Living Backpack**
>
> | **Melee**      |                  **Main action** |
> |----------------|---------------------------------:|
> | **📏 Melee 1** | **🎯 The shieldbearer's mentor** |
>
> **Effect:** The shieldbearer straps their shield on their back and climbs onto their mentor's back, entering the mentor's space. While the shieldbearer is on their mentor's back, each of them gains 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) and can use Shield Block as a triggered action targeting an ally instead of the shieldbearer's mentor. Additionally, the shieldbearer moves with the mentor, and they can't use main actions, maneuvers, or move actions except to end this effect as a maneuver. The effect also ends if the shieldbearer is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) away from their mentor or knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone). If the shieldbearer is still in their mentor's space when the effect ends, they move into an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space of their choice.

######## Level 10 Retainer Advancement Ability

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
