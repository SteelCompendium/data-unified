---
agility: 3
ev: "20"
free_strike: 5
intuition: 2
keywords:
    - Fey
    - Humanoid
    - Wode Elf
level: 3
might: 2
movement: Teleport
name: Wode Elf Warleader
organization: Leader
presence: 2
reason: 2
scc: mcdm.monsters.v1/monster.elf-wode.statblock/wode-elf-warleader
size: 1M
speed: 7
stability: 2
stamina: "120"
type: statblock
---

| Fey, Humanoid, Wode Elf |            -             |      Level 3       |        Leader         |        EV 20         |
|:-----------------------:|:------------------------:|:------------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size      |      **7**<br>Speed      | **120**<br>Stamina |  **2**<br>Stability   | **5**<br>Free Strike |
|    **-**<br>Immunity    | **Teleport**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|     **+2**<br>Might     |    **+3**<br>Agility     |  **+2**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Wodeblade (Signature Ability)**
>
> | **Magic, Melee, Strike, Weapon** |                 **[Main action](../../../rule/combat/turn.md)** |
> |----------------------------------|--------------------------------:|
> | **📏 Melee 1**                   | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; M < 1 [restrained](../../../condition/restrained.md) (save ends)
> - **12-16:** 12 damage; M < 2 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** 15 damage; M < 3 [restrained](../../../condition/restrained.md) (save ends)
>
> **Effect:** The warleader can [teleport](../../../movement/teleport.md) up to 3 squares between each strike.
>
> **2 [Malice](../../../rule/monster/malice.md):** A target [restrained](../../../condition/restrained.md) by this ability takes an extra 3 damage.

> ❇️ **Fairness Is a Human Concept (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Area**        |                 **[Maneuver](../../../rule/combat/turn.md)** |
> |-----------------|-----------------------------:|
> | **📏 10 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each non-[minion](../../../rule/organization/minion.md) target can make a [free strike](../../../feature/common/main-actions/free-strike.md), then each target [shifts](../../../movement/shifting.md) up to 3 squares. A target who has cover or concealment at the end of this shift can attempt to hide at the end of the warleader's turn.

> ❗️ **Wode Sickness**
>
> | **Ranged**       | **[Triggered action](../../../rule/combat/triggered-action.md)** |
> |------------------|---------------------:|
> | **📏 Ranged 10** |     **🎯 One enemy** |
>
> **Trigger:** An ally ends their turn.
>
> **Effect:** The target must not have taken their turn this round. The target takes their turn immediately, and if they have P < 2 they are [bleeding](../../../condition/bleeding.md) and take a bane on strikes until the end of their turn.

> ⭐️ **End Effect**
>
> At the end of each of their turns, the warleader can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

> ⭐️ **Into the Green**
>
> The warleader can attempt to hide at the end of each of their turns.

> ⭐️ **Masking Glamor**
>
> Abilities targeting the warleader that would take a bane from cover or concealment have a double bane instead.

> ☠️ **You Will All Witness my Blade (Villain Action 1)**
>
> | **Area**       |                         **-** |
> |----------------|------------------------------:|
> | **📏 5 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** The warleader uses Wodeblade against each target and gains an edge on the power roll.

> ☠️ **Suppressing Volley (Villain Action 2)**
>
> | **Area**       |                        **-** |
> |----------------|-----------------------------:|
> | **📏 5 burst** | **🎯 Each ally in the area** |
>
> **Effect:** The warleader can use Wodeblade. Each target can then make a [free strike](../../../feature/common/main-actions/free-strike.md).

> ☠️ **Is It Now or Is It Then? (Villain Action 3)**
>
> | **Area**       |                                 **-** |
> |----------------|--------------------------------------:|
> | **📏 5 burst** | **🎯 Self and each ally in the area** |
>
> **Effect:** Each target is invisible until the start of the next round. The warleader then uses Wodeblade.
