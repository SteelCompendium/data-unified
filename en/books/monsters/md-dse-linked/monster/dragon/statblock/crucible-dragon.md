---
agility: -1
ev: "96"
file_basename: crucible-dragon
file_dpath: monster/dragon/statblock
free_strike: 7
immunities:
    - Fire 6
intuition: 3
item_id: crucible-dragon
item_name: Crucible Dragon
keywords:
    - Dragon
    - Elemental
level: 6
might: 4
name: Crucible Dragon
organization: Solo
presence: 2
reason: 3
scc: mcdm.monsters.v1/monster.dragon.statblock/crucible-dragon
size: "4"
source: mcdm.monsters.v1
speed: 8
stability: 6
stamina: "450"
type: statblock
---

|   Dragon, Elemental    |         -         |      Level 6       |         Solo          |        EV 96         |   
|:----------------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|   
|     **4**<br>Size      |  **8**<br>Speed   | **450**<br>Stamina |  **6**<br>Stability   | **7**<br>Free Strike |   
| **Fire 6**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |   
|    **+4**<br>Might     | **-1**<br>Agility |  **+3**<br>Reason  |  **+3**<br>Intuition  |  **+2**<br>Presence  |

> ☠️ **[Solo](../../../rule/organization/solo.md) Monster**
>
> **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the dragon can take 10 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

> ❇️ **Magnetized Wyrmscale Aura**
>
> The dragon's scales create a 3 aura of magnetism around them that affects large masses of metal. Any creature who enters the area for the first time in a round or starts their turn there while wearing metal or while slagged (see Slag Spew) is pulled up to 2 squares toward the dragon. A creature pulled this way who has M < 3 is unable to willingly move away from the dragon.

> 🔳 **Slag Spew (Signature Ability)**
>
> | **Area, Magic**             |                             **Main action** |
> |-----------------------------|--------------------------------------------:|
> | **📏 10 x 2 line within 1** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target makes an Agility test.
>
> - **≤11:** 13 fire damage; the target is slagged (save ends)
> - **12-16:** 10 fire damage; the target is slagged (save ends)
> - **17+:** 6 fire damage
>
> A slagged target is coated in molten metal and takes 2d6 fire damage at the start of each of their turns. If a slagged target has M < 3 they are [restrained](../../../condition/restrained.md) (save ends) whenever they take cold damage.

> 🗡 **Forge Hammer Tail Slam**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 3**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 11 damage; M < 2 [prone](../../../condition/prone.md)
> - **12-16:** 17 damage; M < 3 [prone](../../../condition/prone.md)
> - **17+:** 20 damage; M < 4 [prone](../../../condition/prone.md)
>
> **Effect:** The dragon can make a [free strike](../../../feature/common/main-actions/free-strike.md) against each slagged target knocked [prone](../../../condition/prone.md) this way.
>
> **1 [Malice](../../../rule/monster/malice.md):** The strike deals 1d6 cold damage.

> ⭐️ **Heat Buffer**
>
> Once per round while the dragon is [flying](../../../movement/fly.md) using their Thermodynamic Flight ability, they give off a blast of steam to extend the duration of their flight until the end of the next round. Each creature in a 4 cube within 1 underneath the dragon when they use this ability takes 7 fire damage.

> ❇️ **Thermodynamic Flight (1 [Malice](../../../rule/monster/malice.md))**
>
> | **Area**       |                  **Maneuver** |
> |----------------|------------------------------:|
> | **📏 2 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** The dragon expels blistering steam, dealing 7 fire damage to each target in the area. The dragon then [shifts](../../../movement/shifting.md) up to their speed vertically and can [fly](../../../movement/fly.md) until the end of the round.

> ❗️ **Hammer and Anvil (1 [Malice](../../../rule/monster/malice.md))**
>
> | **-**       | **Free triggered action** |
> |-------------|--------------------------:|
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** While [flying](../../../movement/fly.md), the dragon starts their turn or moves.
>
> **Effect:** The dragon drops to the ground and uses Forge Hammer Tail Slam, which deals an extra 4 damage for each square they descended.

> ❗️ **Polarize Aura (1 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Magic** |                        **Triggered action** |
> |-----------------|--------------------------------------------:|
> | **📏 3 burst**  | **🎯 Each creature and object in the area** |
>
> **Trigger:** The dragon is targeted by two melee strikes in the current turn.
>
> **Special:** The target must be size 2 or smaller.
>
> **Power Roll + 4:**
>
> - **≤11:** Push 5
> - **12-16:** Push 7
> - **17+:** Push 10, ignoring [stability](../../../rule/character/stability.md)

> ☠️ **Heart of the Forge ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 6 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 4:**
>
> - **≤11:** 4 fire damage; I < 2 [frightened](../../../condition/frightened.md) (save ends)
> - **12-16:** 6 fire damage; I < 3 [frightened](../../../condition/frightened.md) (save ends)
> - **17+:** 8 fire damage; I < 4 [frightened](../../../condition/frightened.md) (save ends)

> ☠️ **Subdermal Shielding ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** Shields embedded under the dragon's scales emerge, and the dragon gains damage immunity 6 at the start of each round until the end of the encounter. If the dragon takes any damage, they lose this immunity until the end of the current round.

> ☠️ **Polarity Chaos ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **-**           |                                       **-** |
> |-----------------|--------------------------------------------:|
> | **📏 10 burst** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target makes a **Might test**.
>
> - **≤11:** 16 damage; pull 10 or push 10
> - **12-16:** 13 damage; pull 8 or push 8
> - **17+:** 7 damage; pull 5 or push 5.
