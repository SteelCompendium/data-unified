---
agility: 5
ev: "144"
file_basename: meteor-dragon
file_dpath: monster/dragon/statblock
free_strike: 10
intuition: 3
item_id: meteor-dragon
item_name: Meteor Dragon
keywords:
    - Dragon
    - Elemental
level: 10
might: 5
movement: Fly
name: Meteor Dragon
organization: Solo
presence: 5
reason: 3
scc: mcdm.monsters.v1/monster.dragon.statblock/meteor-dragon
size: "3"
source: mcdm.monsters.v1
speed: 15
stability: 6
stamina: "650"
type: statblock
---

| Dragon, Elemental |          -          |      Level 10      |         Solo          |        EV 144        |   
|:-----------------:|:-------------------:|:------------------:|:---------------------:|:--------------------:|   
|   **3**<br>Size   |   **15**<br>Speed   | **650**<br>Stamina |  **6**<br>Stability   | **10**<br>Free Strike |   
| **-**<br>Immunity | **Fly**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |   
|  **+5**<br>Might  |  **+5**<br>Agility  |  **+3**<br>Reason  |  **+3**<br>Intuition  |  **+5**<br>Presence  |

> ☠️ **[Solo](../../../rule/organization/solo.md) Monster**
>
> **[End Effect](../../../rule/monster/end-effect.md):** At the end of each of their turns, the dragon can take 20 damage to end one effect on them that can be ended by a saving throw. This damage can't be reduced in any way.
>
> **Solo Turns:** The dragon can take two turns each round. They can't take turns consecutively.

> ❇️ **Voidshroud Wyrmscale Aura**
>
> The dragon's scales create a 1 aura of void space around them. Any enemy who starts their turn in the area takes 10 cold damage and is suffocating. Each time the dragon takes damage, the area of the aura increases by 1 (to a maximum of 5), and they deal an extra 5 damage the next time they use an ability that deals rolled damage.

> 🔳 **Gravity Well (Signature Ability)**
>
> | **Area, Magic, Ranged** | **Main action** |
> |-------------------------|------------------------------:|
> | **📏 4 cube within 10** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target makes a **Might test**.
>
> - **≤11:** 20 sonic damage; the target is dragonsealed (save ends)
> - **12-16:** 16 sonic damage; the target is dragonsealed (save ends)
> - **17+:** 10 sonic damage
>
> A dragonsealed target emits a golden aura, and takes 2 damage per square moved when falling or when [force moved](../../../movement/forced-movement.md) into an obstacle.

> ⚔️ **Cosmic Tail Ray**
>
> | **Magic, Melee, Ranged, Strike** |                 **Main action** |
> |----------------------------------|--------------------------------:|
> | **📏 Melee 2 or ranged 15**      | **🎯 Two creatures or objects** |
>
> **Power Roll + 5:**
>
> - **≤11:** 15 holy damage; A < 4 [weakened](../../../condition/weakened.md) (save ends)
> - **12-16:** 21 holy damage; A < 5 [weakened](../../../condition/weakened.md) (save ends)
> - **17+:** 25 holy damage; A < 6 [weakened](../../../condition/weakened.md) (save ends)
>
> **Effect:** If a target made [weakened](../../../condition/weakened.md) this way is already [weakened](../../../condition/weakened.md), they are instead [dazed](../../../condition/dazed.md) until the end of their next turn.

> ⭐️ **Crescent Claws**
>
> Once per turn, the dragon chooses a target within 3 squares. The dragon can make a [free strike](../../../feature/common/main-actions/free-strike.md) against the target, and ignores [banes](../../../rule/dice/bane.md) when using abilities against the target until the start of their next turn.

> ❇️ **Investiture of Gravity (5 [Malice](../../../rule/monster/malice.md))**
>
> | **Area, Magic** |                  **Maneuver** |
> |-----------------|------------------------------:|
> | **📏 15 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target must be dragonsealed. The dragon chooses a direction and vertical slides each target 10 squares in that direction, ignoring [stability](../../../rule/character/stability.md). A target who strikes an obstacle takes damage as if they had fallen the [forced movement](../../../movement/forced-movement.md) distance.

> ❗️ **Field Collapse**
>
> | **-**       | **Free triggered action** |
> |-------------|--------------------------:|
> | **📏 Self** |               **🎯 Self** |
>
> **Trigger:** The dragon takes damage from an ability while the area of their Voidshroud Wyrmscale Aura is 2 or more.
>
> **Effect:** The dragon halves the damage. Each enemy and object in the area of the dragon's Voidshroud Wyrmscale Aura trait takes 5 sonic damage and is pulled up to 5 squares toward the dragon. The area of the wyrmscale aura then resets to 1.

> ❗️ **A Hero Faces the Void (2 [Malice](../../../rule/monster/malice.md))**
>
> | **Magic, Ranged** |      **Free triggered action** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance spends their Heroic Resource to use an ability.
>
> **Power Roll + 5:**
>
> - **≤11:** 10 psychic damage; P < 4 [frightened](../../../condition/frightened.md) (save ends)
> - **12-16:** 16 psychic damage; P < 5 [frightened](../../../condition/frightened.md) (save ends)
> - **17+:** 20 psychic damage; P < 6 [frightened](../../../condition/frightened.md) (save ends)
>
> **Effect:** While [frightened](../../../condition/frightened.md) this way, the target can't use the triggering ability.

> ☠️ **Impactful Arrival ([Villain Action](../../../rule/monster/villain-action.md) 1)**
>
> | **Area, Magic**     |                                       **-** |
> |---------------------|--------------------------------------------:|
> | **📏 1-mile burst** | **🎯 Each creature and object in the area** |
>
> **Effect:** Each target takes 30 fire damage, and if they have M < 5, they are knocked [prone](../../../condition/prone.md).
>
> **Special:** The dragon can use this ability before the encounter begins.

> ☠️ **Burning Aurora ([Villain Action](../../../rule/monster/villain-action.md) 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** Until the end of the encounter, each enemy who is dragonsealed and [weakened](../../../condition/weakened.md) and who the dragon has [line of effect](../../../rule/combat/line-of-effect.md) to loses 1 of their Heroic Resource at the start of each of their turns (to a minimum of 0). The dragon then uses their Cosmic Tail Ray ability with a double [edge](../../../rule/dice/edge.md), targeting four creatures or objects.

> ☠️ **Voidlight Breath ([Villain Action](../../../rule/monster/villain-action.md) 3)**
>
> | **Area, Magic**            |                                    **-** |
> |----------------------------|-----------------------------------------:|
> | **📏 ∞ x 3 line within 1** | **🎯 Each enemy and object in the area** |
>
> **Effect:** Each target makes an Agility test.
>
> - **≤11:** 25 damage; I < 6 the target is annihilated
> - **12-16:** 21 damage; I < 5 the target is annihilated
> - **17+:** 15 damage; I < 4 the target is annihilated
>
> An annihilated target must make the test again, decreasing the [potency](../../../rule/character/potency.md) for themself by 2 each time they are annihilated. A creature reduced to 0 [Stamina](../../../rule/health/stamina.md) by this dies and their soul is destroyed.
