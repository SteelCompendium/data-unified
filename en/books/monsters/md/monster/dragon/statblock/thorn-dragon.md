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

> ☠️ **[Solo](scc.v1:mcdm.monsters.v1/rule.organization/solo) Monster**
>
> **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect):** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

> ❇️ **Withering Wyrmscale Aura**
>
> The dragon's scales create a 2 aura of withering green magic around them. Any creature other than the dragon who regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) in the area regains only half the expected amount. Any [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) creature who enters the area for the first time in a round or starts their turn there takes 1d3 corruption damage.

> 🔳 **Virulent Breath (Signature Ability)**
>
> | **Area, Magic**             |                          **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
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
> | **Charge, Melee, Strike, Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------------------------|------------------------------:|
> | **📏 Melee 2**                    | **🎯 Two enemies or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; push 2
> - **12-16:** 12 damage; push 4
> - **17+:** 15 damage; push 8
>
> **2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** Each target takes an extra 1d3 damage, and if they have A < 2, they are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends).

> ⭐️ **Provoking Nettles**
>
> Once per turn, the dragon [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 5 squares and can move through enemies' spaces at their usual speed. The first time the dragon moves through an enemy's space during this movement, the enemy takes 3 damage.

> ❇️ **Investiture of Verdure (5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Area**        |                  **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------|------------------------------:|
> | **📏 10 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target must be dragonsealed. Each target is pulled up to 5 squares toward the dragon, who gains 5 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) for each target pulled.

> ❗️ **Prickly Situation**
>
> | **Magic, Ranged** |      **Free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 10**  | **🎯 The triggering creature** |
>
> **Trigger:** A dragonsealed creature within distance ends the dragonsealed effect.
>
> **Effect:** The target is pulled up to 5 squares toward the dragon, and if they have A < 2, they are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.

> ❗️ **Thorny Scales (1 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee**      |      **Free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |----------------|-------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance deals damage to the dragon with a melee strike.
>
> **Effect:** The dragon makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target, and if the target has M < 2, they are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the end of their next turn.

> ☠️ **Briar Bindings ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 4 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 damage; A < 1 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **12-16:** 9 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **17+:** 12 damage; A < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)

> ☠️ **Thorned Armor ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The thorns upon the dragon's scales grow longer and sharper. Until the end of the encounter, any [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature who targets the dragon with a melee strike takes 3 damage. The dragon then uses their Provoking Nettles ability.

> ☠️ **Malign Thicket ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **-**          |          **-** |
> |----------------|---------------:|
> | **📏 Special** | **🎯 Special** |
>
> **Effect:** Poisonous overgrowth and seeking vines cover all surfaces on the encounter map. The dragon uses their Bramble Barricade Malice feature twice at no cost. Until the end of the encounter, any creature [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) by the dragon takes 1d3 poison damage, and if they have M < 2, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends).
>
> **Special:** If the Thorn Dragon's Domain [trait](scc.v1:mcdm.monsters.v1/rule.monster/monster-trait) is in effect, any creature other than the dragon who starts their turn on the encounter map takes 1d3 poison damage.
