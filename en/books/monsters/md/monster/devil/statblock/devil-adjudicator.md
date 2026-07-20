---
agility: 1
ev: "32"
free_strike: 7
immunities:
    - Fire 5
intuition: 1
keywords:
    - Devil
    - Infernal
level: 6
might: 0
movement: Fly
name: Devil Adjudicator
organization: Elite
presence: 3
reason: 2
role: Controller
scc: mcdm.monsters.v1/monster.devil.statblock/devil-adjudicator
size: 1M
speed: 6
stability: 1
stamina: "140"
type: statblock
---

|    Devil, Infernal     |          -          |      Level 6       |   Elite Controller    |        EV 32         |
|:----------------------:|:-------------------:|:------------------:|:---------------------:|:--------------------:|
|     **1M**<br>Size     |   **6**<br>Speed    | **140**<br>Stamina |  **1**<br>Stability   | **7**<br>Free Strike |
| **Fire 5**<br>Immunity | **Fly**<br>Movement |         -          | **-**<br>With Captain |  **-**<br>Weakness   |
|    **+0**<br>Might     |  **+1**<br>Agility  |  **+2**<br>Reason  |  **+1**<br>Intuition  |  **+3**<br>Presence  |

> 🏹 **Infernal Injunction (Signature Ability)**
>
> | **Magic, Ranged, Strike** |                 **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |---------------------------|--------------------------------:|
> | **📏 Ranged 10**          | **🎯 Two creatures or objects** |
>
> **Power Roll + 3:**
>
> - **≤11:** 10 fire damage; I < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **12-16:** 15 fire damage; I < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
> - **17+:** 18 fire damage; I < 1 [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
>
> **Effect:** The adjudicator can slide a target [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) by this ability up to 2 squares.

> 🏹 **Adjudicator's Interdiction**
>
> | **Magic, Ranged** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------|--------------------:|
> | **📏 Ranged 10**  | **🎯 One creature** |
>
> **Effect:** The target makes a Presence test.
>
> - **≤11:** The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on power rolls, and can't regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) (save ends).
> - **12-16:** The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) and takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on power rolls (save ends).
> - **17+:** [Slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)

> 🏹 **Quid Pro Quo**
>
> | **Magic, Ranged** |                           **[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
> |-------------------|---------------------------------------:|
> | **📏 Ranged 10**  | **🎯 One ally or [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) creature** |
>
> **Effect:** The adjudicator and the target [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) to switch places.

> ❗️ **Devilish Charm (2 [Malice](scc.v1:mcdm.monsters.v1/rule.monster/malice))**
>
> | **Magic, Ranged** |           **[Triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)** |
> |-------------------|-------------------------------:|
> | **📏 Ranged 5**   | **🎯 The triggering creature** |
>
> **Trigger:** A creature targets the adjudicator with a strike.
>
> **Effect:** The target makes a Presence test.
>
> - **≤11:** The adjudicator chooses a new target for the strike.
> - **12-16:** The adjudicator halves the triggering damage.
> - **17+:** The target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on the strike.

> ⭐️ **Vexatious Litigation**
>
> Any creature within 10 squares of the adjudicator who has P < 3 takes a −2 penalty to saving throws.

> ⭐️ **True Name**
>
> If a creature within 10 squares speaks the adjudicator's true name, the adjudicator loses their damage immunities, any nondamaging effects of their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability), and their Devilish Charm ability until the end of the encounter.
