---
agility: 2
ev: "40"
free_strike: 8
intuition: 2
keywords:
    - Giant
    - Stone Giant
level: 8
might: 4
movement: Burrow
name: Basalt Stone Giant
organization: Elite
presence: 1
reason: 1
role: Controller
scc: mcdm.monsters.v1/monster.giant.statblock/basalt-stone-giant
size: "4"
speed: 7
stability: 10
stamina: "207"
type: statblock
---

| Giant, Stone Giant |           -            |      Level 8       |   Elite Controller    |        EV 40         |
|:------------------:|:----------------------:|:------------------:|:---------------------:|:--------------------:|
|   **4**<br>Size    |     **7**<br>Speed     | **207**<br>Stamina |  **10**<br>Stability  | **8**<br>Free Strike |
| **-**<br>Immunity  | **Burrow**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|  **+4**<br>Might   |   **+2**<br>Agility    |  **+1**<br>Reason  |  **+2**<br>Intuition  |  **+1**<br>Presence  |

> 🗡 **Rune-Signed Blade (Signature Ability)**
>
> | **Magic, Melee, Strike, Weapon** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |----------------------------------|--------------------------------:|
> | **📏 Melee 3**                   | **🎯 Two creatures or objects** |
>
> **Power Roll + 4:**
>
> - **≤11:** 12 damage; M < 2 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **12-16:** 17 damage; M < 3 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
> - **17+:** 21 damage; M < 4 [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
>
> **Effect:** If a target was already [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), that condition continues but their speed is 0 until the end of their next turn.

> ⚔️ **Forked Knife (3 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Melee, Ranged, Strike, Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-----------------------------------|------------------------------:|
> | **📏 Melee 3 or ranged 12**       | **🎯 One creature or object** |
>
> **Power Roll + 4:**
>
> - **≤11:** 10 damage; A < 2 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **12-16:** 16 damage; A < 3 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
> - **17+:** 20 damage; [prone](scc.v1:mcdm.heroes.v1/condition/prone); A < 4 [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
>
> **Effect:** The knife lands in the target's square, and has 30 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) and damage immunity 5. Whenever the knife takes damage, it deals 4 sonic damage to each enemy within 3 squares. The knife lasts until the end of the encounter, and can't be picked up or manipulated.

> 👤 **Cobblestone Shape**
>
> | **-**       | **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------|-------------:|
> | **📏 Self** |  **🎯 Self** |
>
> **Effect:** The basalt stone giant moves up to their speed. Each square that they leave during this move is [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies. Giants ignore this [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).

> ❗️ **Resonate Rune**
>
> | **Area, Magic** |          **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-----------------|------------------------------:|
> | **📏 2 burst**  | **🎯 Each enemy in the area** |
>
> **Trigger:** The basalt stone giant takes damage.
>
> **Effect:** The target is [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 3 squares, or if they have A < 3, they are [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) up to 6 squares and knocked [prone](scc.v1:mcdm.heroes.v1/condition/prone).

> ⭐️ **Stonebreaker Flesh**
>
> Whenever an enemy obtains a tier 1 outcome on a melee ability used against the basalt stone giant, they take a bane on that ability until the end of the encounter.

> ⭐️ **Stone Steps**
>
> The basalt stone giant ignores [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain).

> ⭐️ **Stone Swim**
>
> The basalt stone giant can [burrow](scc.v1:mcdm.heroes.v1/movement/burrow) through stone, but can't drag other creatures underground when they do so.
