---
agility: 2
ev: "36"
file_basename: werewolf
file_dpath: monster/werewolf/statblock
free_strike: 5
intuition: 1
item_id: werewolf
item_name: Werewolf
keywords:
    - Accursed
    - Humanoid
    - Werebeast
level: 1
might: 3
name: Werewolf
organization: Solo
presence: 1
reason: -1
scc: mcdm.monsters.v1/monster.werewolf.statblock/werewolf
size: 1M
source: mcdm.monsters.v1
speed: 7
stability: 0
stamina: "200"
type: statblock
---

| Accursed, Humanoid, Werebeast |         -          |      Level 1       |         Solo          |        EV 36         |
|:-----------------------------:|:------------------:|:------------------:|:---------------------:|:--------------------:|
|        **1M**<br>Size         |   **7**<br>Speed   | **200**<br>Stamina |  **0**<br>Stability   | **5**<br>Free Strike |
|       **-**<br>Immunity       | **- **<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|        **+3**<br>Might        | **+2**<br>Agility  |  **-1**<br>Reason  |  **+1**<br>Intuition  |  **+1**<br>Presence  |

> ☠️ **Solo Monster**
>
> **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect):** At the end of each of their turns, the werewolf can take 5 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.
>
> **Solo Turns:** The werewolf can take two turns each round. They can't take turns consecutively.

> ⭐️ **Accursed Rage**
>
> The werewolf's ferocity is expressed through rage, and their abilities can inflict rage points on any enemy except a stormwight [fury](scc.v1:mcdm.heroes.v1/class/fury). A creature who starts their turn with 10 or more rage expends their rage. Then before taking their turn, they must [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed toward the nearest creature and make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them. A creature who takes damage from this [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) gains 1 rage. Accumulated rage disappears after a character finishes a respite.

> ⭐️ **Shapeshifter**
>
> The werewolf enters combat in their hybrid humanoid form. Their shape can't be changed by any external effect.

> ⭐️ **Vukenstep**
>
> The werewolf ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).

> 🗡 **Accursed Bite ([Signature Ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability))**
>
> | **Charge, Melee, Strike, Weapon** |               **Main action** |
> |-----------------------------------|------------------------------:|
> | **📏 Melee 1**                    | **🎯 One creature or object** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; the target gains 2 rage
> - **12-16:** 13 damage; the target gains 4 rage
> - **17+:** 16 damage; the target gains 5 rage
>
> **2 Malice:** If the target has P < 0, they are afflicted with lycanthpy. Each time the target is unaffected by the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effect, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) increases by 1 the next time the werewolf uses the ability against the same target. A creature afflicted with lycanthropy gains 2 rage at the end of each of their turns whenever they're in combat. Their rage doesn't disappear after finishing a respite and they must complete the Find a Cure downtime project in "Draw Steel: Heroes" to end this effect.

> 🗡 **Ripping Claws**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 1**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 8 damage; M < 1 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 11 damage; the target gains 1 rage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 14 damage; the target gains 3 rage; M < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)

> ❇️ **Berserker Slash (3 Malice)**
>
> | **Area, Weapon** |                          **Main action** |
> |------------------|-----------------------------------------:|
> | **📏 1 burst**   | **🎯 Each enemy and object in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 4 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
> - **12-16:** 6 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; the target gains 1 rage
> - **17+:** 7 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; the target gains 3 rage
>
> **Effect:** The werewolf [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed before using this ability.

> 👤 **Wall Leap**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The werewolf jumps up to 4 squares. If they end this jump at a wall, the werewolf jumps off the wall up to 4 squares and can make a melee [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike). If the target of the [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) has M < 2, they are knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone).

> ❗️ **Facepalm and Head Slam (2 Malice)**
>
> | **Melee**      |           **Triggered action** |
> |----------------|-------------------------------:|
> | **📏 Melee 1** | **🎯 The triggering creature** |
>
> **Trigger:** A creature within distance targets the werewolf with a melee ability after charging or moving 2 or more squares in a straight line toward them.
>
> **Effect:** The target is knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone) and takes 5 damage before the [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) is resolved.

> ☠️ **Howl ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 1)**
>
> | **Area**       |                         **-** |
> |----------------|------------------------------:|
> | **📏 5 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** Each target makes an Intuition test.
>
> - **≤11:** The target must move their speed in a straight line away from the werewolf; [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** [Frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (EoT)
> - **17+:** No effect
>
> **Effect:** Any enemy in the encounter who has 1 or more rage gains 4 rage and howls along with the werewolf.

> ☠️ **Full Wolf ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 2)**
>
> | **-**       |       **-** |
> |-------------|------------:|
> | **📏 Self** | **🎯 Self** |
>
> **Effect:** The werewolf transforms into a massive wolf of size 3 until they die or until the end of the encounter. They move to a space that can accommodate their new size and [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creatures out of their way. While in wolf form, they have speed 10 and stability 2, their strikes gain a +2 damage bonus and bestow an additional 1 rage, and the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of Accursed Bite increases by 1.

> ☠️ **Rampage ([Villain Action](scc.v1:mcdm.monsters.v1/rule.monster/villain-action) 3)**
>
> | **Area, Weapon** |                             **-** |
> |------------------|----------------------------------:|
> | **📏 2 burst**   |  **🎯 Each creature in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 5 damage; the target gains 2 rage; M < 1 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 8 damage; the target gains 4 rage; M < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 11 damage; the target gains 8 rage; M < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
>
> **Effect:** The werewolf [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed before and after using this ability.
