---
agility: -2
cost: 2 Malice for two minions
cost_amount: "2"
cost_resource: Malice for two minions
file_basename: zombie-lumberer
file_dpath: monster/rival/1st-echelon/summoner/minion/statblock
free_strike: 4
immunities:
    - Corruption 2
    - poison 2
intuition: 0
item_id: zombie-lumberer
item_name: Zombie Lumberer
keywords:
    - Undead
might: 2
movement: —
name: Zombie Lumberer
organization: Minion
presence: 1
reason: 0
role: Defender
scc: mcdm.summoner.v1/monster.rival.1st-echelon.summoner.minion.statblock/zombie-lumberer
size: "2"
source: mcdm.summoner.v1
speed: 5
stability: 2
stamina: 8 | 8
type: statblock
weaknesses: []
---

```ds-sb
agility: -2
cost: 2 Malice for two minions
ev: ""
features:
    - effects:
        - effect: The lumberer's melee [free strikes](../../../../../../feature/common/main-actions/free-strike.md) inflict A < 1 [grabbed](../../../../../../condition/grabbed.md). A creature or object that starts their turn [grabbed](../../../../../../condition/grabbed.md) by the lumberer takes 2 corruption damage.
      feature_type: trait
      icon: ⭐️
      name: Zombie Clutch
      type: feature
    - effects:
        - effect: When the lumberer is reduced to 0 [Stamina](../../../../../../rule/health/stamina.md), they can latch onto an [adjacent](../../../../../../rule/combat/adjacent.md) enemy before being destroyed. The enemy is M < 2 [restrained](../../../../../../condition/restrained.md) ([EoT](../../../../../../rule/combat/end-of-turn.md)).
      feature_type: trait
      icon: ⭐️
      name: Death Grasp
      type: feature
free_strike: 4
immunities:
    - Corruption 2
    - poison 2
intuition: 0
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.rival.1st-echelon.summoner.minion.statblock/zombie-lumberer
    source: mcdm.summoner.v1
might: 2
movement: —
name: Zombie Lumberer
organization: Minion
presence: 1
reason: 0
role: Defender
size: "2"
speed: 5
stability: 2
stamina: 8 | 8
type: statblock
weaknesses: []
```
