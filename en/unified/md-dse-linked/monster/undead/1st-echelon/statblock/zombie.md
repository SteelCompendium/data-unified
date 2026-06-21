---
agility: 1
ev: "3"
file_basename: zombie
file_dpath: monster/undead/1st-echelon/statblock
free_strike: 2
immunities:
    - Corruption 1
    - poison 1
intuition: -2
item_id: zombie
item_name: Zombie
keywords:
    - Undead
    - Soulless
level: 1
might: 2
name: Zombie
organization: Horde
presence: 1
reason: -5
role: Brute
scc: mcdm.monsters.v1/monster.undead.1st-echelon.statblock/zombie
size: 1M
source: mcdm.monsters.v1
speed: 5
stability: 1
stamina: "20"
type: statblock
---

|            Undead, Soulless            |         -         |      Level 1      |      Horde Brute      |         EV 3         |
|:--------------------------------------:|:-----------------:|:-----------------:|:---------------------:|:--------------------:|
|             **1M**<br>Size             |  **5**<br>Speed   | **20**<br>Stamina |  **1**<br>Stability   | **2**<br>Free Strike |
| **Corruption 1, poison 1**<br>Immunity | **-**<br>Movement |         -         | **-**<br>With Captain |  **-**<br>Weakness   |
|            **+2**<br>Might             | **+1**<br>Agility | **-5**<br>Reason  |  **-2**<br>Intuition  |  **+1**<br>Presence  |

> 🗡 **Clobber and Clutch ([Signature Ability](../../../../rule/combat/signature-ability.md))**
>
> | **Melee, Strike, Weapon** |               **Main action** |
> |---------------------------|------------------------------:|
> | **📏 Melee 1**            | **🎯 One creature or object** |
>
> **Power Roll + 2:**
>
> - **≤11:** 4 damage
> - **12-16:** 6 damage
> - **17+:** 7 damage; [grabbed](../../../../condition/grabbed.md)
>
> **Effect:** A target who starts their turn [grabbed](../../../../condition/grabbed.md) by the zombie takes 2 corruption damage. A creature who takes 5 or more corruption damage this way becomes insatiably hungry for flesh, and must complete the Find a Cure downtime project in Draw Steel: Heroes to end this effect.

> ❇️ **Zombie Dust (3 [Malice](../../../../rule/monster/malice.md))**
>
> | **Area**       |                  **Maneuver** |
> |----------------|------------------------------:|
> | **📏 2 burst** | **🎯 Each enemy in the area** |
>
> **Effect:** The zombie falls [prone](../../../../condition/prone.md), expelling a wave of rot and dust.
>
> **Power Roll + 2:**
>
> - **≤11:** 2 corruption damage
> - **12-16:** 3 corruption damage; M < 1 [weakened](../../../../condition/weakened.md) (save ends)
> - **17+:** 4 corruption damage; M < 2 [dazed](../../../../condition/dazed.md) (save ends)

> ⭐️ **Endless Knight**
>
> The first time the zombie is reduced to 0 [Stamina](../../../../rule/health/stamina.md) by damage that isn't fire damage or holy damage and their body isn't destroyed, they instead have 10 [Stamina](../../../../rule/health/stamina.md) and fall [prone](../../../../condition/prone.md).
