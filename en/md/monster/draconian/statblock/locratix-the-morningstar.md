---
agility: 3
ev: "32"
free_strike: 7
immunities:
    - Acid 6
intuition: 2
keywords:
    - Draconian
    - Dragon
    - Humanoid
level: 6
might: 1
movement: Fly
name: Locratix the Morningstar
organization: Elite
presence: 2
reason: 1
role: Harrier
scc: mcdm.monsters.v1/monster.draconian.statblock/locratix-the-morningstar
size: 1M
speed: 8
stability: 2
stamina: "160"
type: statblock
---

| Draconian, Dragon, Humanoid |          -          |      Level 6       |     Elite Harrier     |        EV 32         |       
|:---------------------------:|:-------------------:|:------------------:|:---------------------:|:--------------------:|       
|       **1M**<br>Size        |   **8**<br>Speed    | **160**<br>Stamina |  **2**<br>Stability   | **7**<br>Free Strike |       
|   **Acid 6**<br>Immunity    | **Fly**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |       
|       **+1**<br>Might       |  **+3**<br>Agility  |  **+1**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> 🗡 **Skewer (Signature Ability)**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** | 
>
> **Power Roll + 3:**
>
> - **≤11:** 10 damage
> - **12-16:** 15 damage; M < 1 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 18 damage; M < 2 [slowed](scc:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** Locratix deals 6 damage to each creature or object in a 2 x 1 line behind the target.

> 🔳 **Acidic Stun (2 [Malice](scc:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area, Magic**            |               **Main action** |
> |----------------------------|------------------------------:|
> | **📏 3 x 1 line within 1** | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 7 acid damage; M < 1 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
> - **12-16:** 12 acid damage; M < 2 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 15 acid damage; M < 3 [dazed](scc:mcdm.heroes.v1/condition/dazed) (save ends)
>
> **Effect:** While [dazed](scc:mcdm.heroes.v1/condition/dazed) this way, a target takes an extra 6 damage from Locratix's abilities.

> 👤 **Takeoff**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** Locratix [flies](scc:mcdm.heroes.v1/movement/fly) up to her speed. Any creature [adjacent](scc:mcdm.heroes.v1/rule.combat/adjacent) to the space on the ground she took off from who has A < 2 is knocked [prone](scc:mcdm.heroes.v1/condition/prone).

> ❗️ **Stay Back!**
>
> | **Melee**      |           **Triggered action** |
> |----------------|-------------------------------:|
> | **📏 Melee 2** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance moves or is [force moved](scc:mcdm.heroes.v1/movement/forced-movement).
>
> **Power Roll + 3:**
>
> - **≤11:** 7 acid damage; A < 1 the target's speed is 0 (EoT)
> - **12-16:** 12 acid damage; A < 2 the target's speed is 0 (EoT)
> - **17+:** 15 acid damage; A < 3 the target's speed is 0 (EoT)

> ⭐️ **Flighty**
>
> When Locratix deals rolled damage to an enemy, that enemy can't use Locratix as the trigger for any of their [triggered actions](scc:mcdm.heroes.v1/rule.combat/triggered-action) until the start of Locratix's next turn.

> ⭐️ **Absorbing Scales**
>
> When Locratix takes damage of any type for which she has damage immunity, she has damage immunity 6 against the next strike made against her.
