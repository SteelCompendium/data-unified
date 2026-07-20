---
agility: 0
ev: "20"
free_strike: 5
intuition: 1
keywords:
    - Dwarf
    - Humanoid
level: 3
might: 3
name: Dwarf Marauder
organization: Leader
presence: 0
reason: 2
scc: mcdm.monsters.v1/monster.dwarf.statblock/dwarf-marauder
size: 1M
speed: 5
stability: 4
stamina: "132"
type: statblock
---

|  Dwarf, Humanoid  |         -         |      Level 3       |        Leader         |        EV 20         | 
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:| 
|  **1M**<br>Size   |  **5**<br>Speed   | **132**<br>Stamina |  **4**<br>Stability   | **5**<br>Free Strike | 
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   | 
|  **+3**<br>Might  | **+0**<br>Agility |  **+2**<br>Reason  |  **+1**<br>Intuition  |  **+0**<br>Presence  |

> ⚔️ **Levitating Axes (Signature Ability)**
>
> | **Melee, Psionic, Ranged, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |--------------------------------------------|--------------------------------:|
> | **📏 Melee 1 or ranged 10**                | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 12 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3
> - **17+:** 15 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 5
>
> **Effect:** A target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by a dwarf can be force moved by this ability. This forced movement doesn't end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) condition unless the Director determines otherwise.
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** A target force moved [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to an ally of the marauder lord is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the end of their next turn.

> 🏹 **Magnetomancy**
>
> | **Psionic, Ranged** |                  **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------|------------------------------:|
> | **📏 Ranged 10**    | **🎯 One creature or object** |
>
> **Effect:** The target vertical [slides](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 5 squares. A target [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by a dwarf can be force moved by this ability. This forced movement doesn't end the [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) condition unless the Director determines otherwise.
>
> **5 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** This ability takes the Area keyword and loses the Ranged keyword, its distance becomes a 10 burst, and it targets each [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) creature in the area.

> ❗️ **Your Weapon Is Useless**
>
> | **Psionic, Ranged** |    **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |---------------------|------------------------:|
> | **📏 Ranged 10**    | **🎯 Self or one ally** |
>
> **Trigger:** A creature makes a melee strike against the target.
>
> **Effect:** The target halves any damage from the strike and the triggering creature takes 4 damage.

> ⭐️ **End Effect**
>
> At the end of each of their turns, the marauder lord can take 5 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.

> ☠️ **Ajax Will Pay Well for These Specimens (Villain Action 1)**
>
> | **Area, Psionic, Ranged, Weapon** | **-** |
> |-----------------------------------|------------------------------:|
> | **📏 5 cube within 10**           | **🎯 Each enemy in the area** |
>
> **Effect:** The marauder lord uses Levitating Axes against each target, making one power roll against all targets.

> ☠️ **Don't Let Them Escape! (Villain Action 2)**
>
> | **Area**       |                        **-** |
> |----------------|-----------------------------:|
> | **📏 5 burst** | **🎯 Each ally in the area** |
>
> **Effect:** Each target shifts up to their speed. The marauder lord then uses Levitating Axes.

> ☠️ **Test Your Metal! (Villain Action 3)**
>
> | **Psionic, Ranged** |          **-** |
> |---------------------|---------------:|
> | **📏 Ranged 10**    | **🎯 Special** |
>
> **Effect:** The marauder lord creates three size 2 metal objects in unoccupied spaces within distance. Whenever the marauder lord uses Magnetomancy, they can additionally target one of these objects.
