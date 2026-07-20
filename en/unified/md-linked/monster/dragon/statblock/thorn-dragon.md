---
agility: 3
ev: "48"
free_strike: 5
immunities:
    - Poison 5
intuition: 1
keywords:
    - Dragon
    - Elemental
level: 2
might: 2
movement: Fly
name: Thorn Dragon
organization: Solo
presence: 2
reason: -1
scc: mcdm.monsters.v1/monster.dragon.statblock/thorn-dragon
size: "3"
speed: 8
stability: 6
stamina: "250"
type: statblock
---

|    Dragon, Elemental     |          -          |      Level 2       |         Solo          |        EV 48         |
|:------------------------:|:-------------------:|:------------------:|:---------------------:|:--------------------:|
|      **3**<br>Size       |   **8**<br>Speed    | **250**<br>Stamina |  **6**<br>Stability   | **5**<br>Free Strike |
| **Poison 5**<br>Immunity | **Fly**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|     **+2**<br>Might      |  **+3**<br>Agility  |  **-1**<br>Reason  |  **+1**<br>Intuition  |  **+2**<br>Presence  |

> ☠️ **[Solo](../../../rule/organization/solo.md) Monster**
>
> **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

> ❇️ **Withering Wyrmscale Aura**
>
> The dragon's scales create a 2 aura of withering green magic around them. Any creature other than the dragon who regains [Stamina](../../../rule/health/stamina.md) in the area regains only half the expected amount. Any [winded](../../../rule/health/winded.md) creature who enters the area for the first time in a round or starts their turn there takes 1d3 corruption damage.

> 🔳 **Virulent Breath (Signature Ability)**
>
> | **Area, Magic**             |                          **[Main action](../../../rule/combat/turn.md)** |
> |-----------------------------|-----------------------------------------:|
> | **📏 10 x 1 line within 1** | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes a **Might test**.
>
> - **≤11:** 12 poison damage; the target is dragonsealed (save ends)
> - **12-16:** 9 poison damage; the target is dragonsealed (save ends)
> - **17+:** 5 poison damage
>
> A dragonsealed creature has their wounds bound by nettles and thorns, causing them to take an extra 1d3 damage whenever they take damage rolled as a d6 or a d3.

> 🗡 **Spinous Tail Swing**
>
> | **Charge, Melee, Strike, Weapon** |               **[Main action](../../../rule/combat/turn.md)** |
> |-----------------------------------|------------------------------:|
> | **📏 Melee 2**                    | **🎯 Two enemies or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; push 2
> - **12-16:** 12 damage; push 4
> - **17+:** 15 damage; push 8
>
> **2 [Malice](../../../rule/monster/malice.md):** Each target takes an extra 1d3 damage, and if they have A < 2, they are [bleeding](../../../condition/bleeding.md) (save ends).

> ⭐️ **Provoking Nettles**
>
> Once per turn, the dragon [shifts](../../../movement/shifting.md) up to 5 squares and can move through enemies' spaces at their usual speed. The first time the dragon moves through an enemy's space during this movement, the enemy takes 3 damage.

> ❇️ **Investiture of Verdure (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Area**        |                  **[Maneuver](../../../rule/combat/turn.md)** |
> |-----------------|------------------------------:|
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target must be dragonsealed. Each target is pulled up to 5 squares toward the dragon, who gains 5 [temporary Stamina](../../../rule/health/temporary-stamina.md) for each target pulled.

> ❗️ **Prickly Situation**
>
> | **Magic, Ranged** |      **Free [triggered action](../../../rule/combat/triggered-action.md)** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 10**  | **🎯 The triggering creature** |
>
> **Trigger:** A dragonsealed creature within distance ends the dragonsealed effect.
>
> **Effect:** The target is pulled up to 5 squares toward the dragon, and if they have A < 2, they are [restrained](../../../condition/restrained.md) until the end of their next turn.

> ❗️ **Thorny Scales (1 [Malice](../../../rule/monster/malice.md))**
>
> | **Melee**      |      **Free [triggered action](../../../rule/combat/triggered-action.md)** |
> |----------------|-------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the dragon with a melee strike.
>
> **Effect:** The dragon makes a [free strike](../../../feature/common/main-actions/free-strike.md) against the target, and if the target has M < 2, they are [bleeding](../../../condition/bleeding.md) until the end of their next turn.

> ☠️ **Briar Bindings ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 4 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 damage; A < 1 [restrained](../../../condition/restrained.md) (save ends)
> - **12-16:** 9 damage; A < 2 [restrained](../../../condition/restrained.md) (save ends)
> - **17+:** 12 damage; A < 3 [restrained](../../../condition/restrained.md) (save ends)

> ☠️ **Thorned Armor ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The thorns upon the dragon's scales grow longer and sharper. Until the end of the encounter, any [adjacent](../../../rule/combat/adjacent.md) creature who targets the dragon with a melee strike takes 3 damage. The dragon then uses their Provoking Nettles ability.

> ☠️ **Malign Thicket ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **-**          |          **-** |
> |----------------|---------------:|
> | **📏 Special** | **🎯 Special** |
>
> **Effect:** Poisonous overgrowth and seeking vines cover all surfaces on the encounter map. The dragon uses their Bramble Barricade Malice feature twice at no cost. Until the end of the encounter, any creature [force moved](../../../movement/forced-movement.md) by the dragon takes 1d3 poison damage, and if they have M < 2, they are [weakened](../../../condition/weakened.md) (save ends).
>
> **Special:** If the Thorn Dragon's Domain [trait](../../../rule/monster/monster-trait.md) is in effect, any creature other than the dragon who starts their turn on the encounter map takes 1d3 poison damage.
