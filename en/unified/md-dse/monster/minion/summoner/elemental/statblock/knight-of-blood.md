---
agility: 2
cost: 7 essence for two minions
cost_amount: "7"
cost_resource: essence for two minions
file_basename: knight-of-blood
file_dpath: monster/minion/summoner/elemental/statblock
flavor: These faceless suits of armor have visible rivers of deep red blood flowing throughout their being. Their blood has a powerful pull to it, causing any open wounds nearby to rip deeper and leak toward the knight.
free_strike: 7
immunities:
    - Corruption R
intuition: 0
item_id: knight-of-blood
item_name: Knight of Blood
keywords:
    - Elemental (Earth)
    - Elemental (Fire)
    - Elemental (Rot)
    - Elemental (Water)
might: 4
movement: —
name: Knight of Blood
organization: Minion
presence: 3
reason: 0
role: Controller
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/knight-of-blood
size: 1L
source: mcdm.summoner.v1
speed: 6
stamina: 16 | 16
type: statblock
weaknesses: []
---

These faceless suits of armor have visible rivers of deep red blood flowing throughout their being. Their blood has a powerful pull to it, causing any open wounds nearby to rip deeper and leak toward the knight.

| Elemental (Earth, Fire, Rot, Water) | - | - | Minion Controller | 7 essence for two minions |
|:---------------:|:-----------------------------------:|:-----------------:|:-:|:-------------------------:|
| **1L**<br>Size | **6**<br>Speed | **16 \| 16**<br>Stamina | **R**<br>Stability | **7**<br>Free Strike |
| **Corruption R**<br>Immunity | **—**<br>Movement | - | **—**<br>Weakness | **Corruption**<br>Free Strike Damage Type |
| **+4**<br>Might | **+2**<br>Agility | **0**<br>Reason | **0**<br>Intuition | **+3**<br>Presence |

> ⭐️ **Scarlet Death**
>
> The knight's melee [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike) inflict P < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends). While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target can't roll lower than a 3 on the die used to resolve [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) damage.

> ⭐️ **Red River** 2 Essence
>
> When the knight is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), they move up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) ignoring [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack). Each square that they exit during this movement pools with blood until the end of the encounter. Each affected square is considered [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies and deals 3 corruption [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to an enemy when they first enter it on a [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Whenever a [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) enemy starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) within 10 squares of the blood pool, they are pulled 2 toward the nearest affected square, ignoring [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
