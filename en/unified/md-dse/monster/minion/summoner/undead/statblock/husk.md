---
agility: 0
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: husk
file_dpath: monster/minion/summoner/undead/statblock
flavor: Husks have stiff corpses that snap and crackle with each sudden movement. Corrosive breath endlessly billows from their slackjawed faces.
free_strike: 1
immunities:
    - Damage 2
    - Corruption R
    - Poison R
intuition: -1
item_id: husk
item_name: Husk
keywords:
    - Undead
might: 2
movement: —
name: Husk
organization: Minion
presence: -1
reason: -1
role: Defender
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/husk
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 1
stamina: "3"
type: statblock
weaknesses: []
---

Husks have stiff corpses that snap and crackle with each sudden movement. Corrosive breath endlessly billows from their slackjawed faces.

| Undead | - | - | Signature Minion Defender | 1 essence per minion summoned |
|:----:|:------:|:-------------------------:|:-:|:-----------------------------:|
| **1M**<br>Size | **5**<br>Speed | **3**<br>Stamina | **1**<br>Stability | **1**<br>Free Strike |
| **Damage 2, Corruption R, Poison R**<br>Immunity | **—**<br>Movement | - | **—**<br>Weakness | **Corruption**<br>Free Strike Damage Type |
| **+2**<br>Might | **0**<br>Agility | **-1**<br>Reason | **-1**<br>Intuition | **-1**<br>Presence |

> ⭐️ **Rotting Strike**
>
> The husk's melee [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) inflict M < WEAK [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)). The [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) increases by 1 for each additional husk adjacent to the target (maximum +2).
