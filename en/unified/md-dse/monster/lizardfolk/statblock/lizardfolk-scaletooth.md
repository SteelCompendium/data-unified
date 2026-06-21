---
agility: 1
ev: "6"
file_basename: lizardfolk-scaletooth
file_dpath: monster/lizardfolk/statblock
free_strike: 4
intuition: 0
item_id: lizardfolk-scaletooth
item_name: Lizardfolk Scaletooth
keywords:
    - Humanoid
    - Lizardfolk
level: 1
might: 2
movement: Swim
name: Lizardfolk Scaletooth
organization: Platoon
presence: 0
reason: 0
role: Brute
scc: mcdm.monsters.v1/monster.lizardfolk.statblock/lizardfolk-scaletooth
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 0
stamina: "46"
type: statblock
---

| Humanoid, Lizardfolk |          -           |      Level 1      |     Platoon Brute     |         EV 6         |
|:--------------------:|:--------------------:|:-----------------:|:---------------------:|:--------------------:|
|    **1M**<br>Size    |    **5**<br>Speed    | **46**<br>Stamina |  **0**<br>Stability   | **4**<br>Free Strike |
|  **-**<br>Immunity   | **Swim**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|   **+2**<br>Might    |  **+1**<br>Agility   |  **0**<br>Reason  |  **0**<br>Intuition   |  **0**<br>Presence   |

> 🗡 **Razor Bite (Signature Ability)**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 6 damage
> - **12-16:** 9 damage
> - **17+:** 12 damage; A < 2 bleeding (save ends)
>
> **Effect:** If the scaletooth has the target [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) of this ability increases by 1.

> 🗡 **Tail Whip (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Strike, Weapon** |                 **Main action** |
> |---------------------------|--------------------------------:|
> | **📏 Melee 2**            | **🎯 Two creatures or objects** |
>
> **Power Roll + 2:**
>
> - **≤11:** 5 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
> - **12-16:** 8 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < 1 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) if within 2 squares of the scaletooth
> - **17+:** 10 damage; [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < 2 [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) if within 2 squares of the scaletooth

> ⭐️ **Reptilian Escape**
>
> While the scaletooth has a tail, whenever they are [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed), [prone](scc.v1:mcdm.heroes.v1/condition/prone), [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), or [weakened](scc.v1:mcdm.heroes.v1/condition/weakened), they can lose their tail to immediately end that condition, then [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 2 squares.
