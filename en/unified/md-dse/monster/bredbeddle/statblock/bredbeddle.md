---
agility: 0
ev: "60"
file_basename: bredbeddle
file_dpath: monster/bredbeddle/statblock
free_strike: 6
intuition: 2
item_id: bredbeddle
item_name: Bredbeddle
keywords:
    - Bredbeddle
    - Giant
level: 3
might: 3
name: Bredbeddle
organization: Solo
presence: 2
reason: -3
scc: mcdm.monsters.v1/monster.bredbeddle.statblock/bredbeddle
size: "2"
source: mcdm.monsters.v1
speed: 5
stability: 4
stamina: "300"
type: statblock
---

| Bredbeddle, Giant |         -         |      Level 3       |         Solo          |        EV 60         |
|:-----------------:|:-----------------:|:------------------:|:---------------------:|:--------------------:|
|   **2**<br>Size   |  **5**<br>Speed   | **300**<br>Stamina |  **4**<br>Stability   | **6**<br>Free Strike |
| **-**<br>Immunity | **-**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+3**<br>Might  | **+0**<br>Agility |  **-3**<br>Reason  |  **+2**<br>Intuition  |  **+2**<br>Presence  |

> ☠️ **Solo Monster**
>
> **[End Effect](scc.v1:mcdm.monsters.v1/rule.monster/end-effect):** At the end of each of their turns, the bredbeddle can take 5 damage to end one effect on them that can be ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw). This damage can't be reduced in any way.
>
> **Solo Turns:** The bredbeddle can take two turns each round. They can't take turns consecutively.

> ⭐️ **Heady or Not**
>
> While headless, the bredbeddle can move into a space containing a severed head and attach it to their neck as a main action. Doing so physically transforms the bredbeddle, who takes on the appearance, size, weight, and stability of the head's original owner. If the bredbeddle takes the form of a creature of size 1L or smaller, the distance of their melee and burst area abilities decreases by 1. These effects last until the bredbeddle is killed or beheaded, or until the head falls off after 24 hours. A head that falls off this way can no longer be attached to this bredbeddle.
>
> A creature must succeed on a **hard Might test** made as a maneuver to rip a head off the bredbeddle. If they fail, the bredbeddle can make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against them.

> ⭐️ **Resilient Form**
>
> The bredbeddle can't be physically transformed in any way except by their Heady or Not trait.

> ❇️ **Executioner's Swing (Signature Ability)**
>
> | **Area, Weapon** |               **Main action** |
> |------------------|------------------------------:|
> | **📏 2 burst**   | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** 2 damage; A < 1 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **12-16:** 4 damage; A < 2 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
> - **17+:** 5 damage; A < 3 [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); M < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
>
> **3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice):** The bredbeddle [shifts](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares, and can target additional enemies who come within distance of this ability during the shift.

> 🗡 **Lop (3 Malice)**
>
> | **Magic, Melee, Strike, Weapon** |     **Main action** |
> |----------------------------------|--------------------:|
> | **📏 Melee 2**                   | **🎯 One creature** |
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); or if the target has M < 1 they are beheaded
> - **12-16:** 13 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); or if the target has M < 2 they are beheaded
> - **17+:** 16 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); or if the target has M < 3 they are beheaded
>
> **Effect:** A beheaded target has their head fall into an unoccupied square adjacent to the bredbeddle, but they remain alive. While beheaded this way, the target is [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) and has line of effect only to adjacent squares. The beheaded target can survive without their head for 24 hours, and can reattach their head as a maneuver by entering its square. A target who remains beheaded for 24 hours dies.

> 👤 **Scramble**
>
> | **-**       | **Maneuver** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** While the bredbeddle is headless, they [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to their speed. Each time a creature comes adjacent to the bredbeddle during the shift, the bredbeddle can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) that creature 1 square. Each square the bredbeddle exits during the shift is difficult terrain.

> 🏹 **Headway (5 Malice)**
>
> | **Ranged, Strike, Weapon** |                  **Maneuver** |
> |----------------------------|------------------------------:|
> | **📏 Ranged 20**           | **🎯 One creature or object** |
>
> **Effect:** The bredbeddle must have a head in their possession (attached to them or not), which they throw at the target. If the head was attached, the bredbeddle is left headless.
>
> **Power Roll + 3:**
>
> - **≤11:** 9 damage; M < 1 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **12-16:** 13 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone); M < 2 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
> - **17+:** 16 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone); M < 3 [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)

> ❗️ **Envious Imitation (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic**   | **Triggered action** |
> |-------------|---------------------:|
> | **📏 Self** |          **🎯 Self** |
>
> **Trigger:** A creature targets the bredbeddle with a ranged strike.
>
> **Effect:** The bredbeddle uses the same ability against the triggering creature after the triggering strike is resolved, using that creature's bonus to any power rolls they make.

> ☠️ **Turn Green (Villain Action 1)**
>
> | **Area, Magic** |                         **-** |
> |-----------------|------------------------------:|
> | **📏 3 burst**  | **🎯 Each enemy in the area** |
>
> **Power Roll + 3:**
>
> - **≤11:** P < 1 the target turns green (save ends)
> - **12-16:** P < 2 the target turns green (save ends)
> - **17+:** P < 3 the target turns green until the end of the encounter
>
> **Effect:** Green shadows crawl out from under the bredbeddle's feet and turn each target green. The bredbeddle has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on power rolls against any target turned green this way.

> ☠️ **Challenge (Villain Action 2)**
>
> | **Ranged**      |            **-** |
> |-----------------|-----------------:|
> | **📏 Ranged 5** | **🎯 One enemy** |
>
> **Effect:** The bredbeddle points at the target and issues them a challenge. If the target refuses, they turn green until the end of the encounter (see Turn Green). If the target accepts the challenge, the bredbeddle shifts adjacent to the target, who makes a **Might test** with no additional modifiers.
>
> - **≤11:** The target is beheaded (see Lop).
> - **12-16:** The target makes the test again.
> - **17+:** The target can choose to deal 40 damage to the bredbeddle or remove the bredbeddle's head.

> ☠️ **Headlam Rampage (Villain Action 3)**
>
> | **Melee, Strike, Weapon** |                 **-** |
> |---------------------------|----------------------:|
> | **📏 Melee 2**            | **🎯 Four creatures** |
>
> **Power Roll + 3:**
>
> - **≤11:** 6 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); or if the target has A < 1 they are beheaded (see Lop).
> - **12-16:** 7 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); or if the target has A < 2 they are beheaded
> - **17+:** 8 damage; [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends); or if the target has A < 3 they are beheaded
