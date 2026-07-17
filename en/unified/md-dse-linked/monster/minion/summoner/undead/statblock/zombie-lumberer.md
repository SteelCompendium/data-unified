---
agility: -2
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: zombie-lumberer
file_dpath: monster/minion/summoner/undead/statblock
flavor: These massive, animated ogre corpses still maintain their incredible grip strength. When a lumberer falls, they'll take anything within reach down with them.
free_strike: 1
immunities:
    - Corruption R
    - Poison R
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
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/zombie-lumberer
size: "2"
source: mcdm.summoner.v1
speed: 5
stamina: 8 | 8
type: statblock
weaknesses: []
---

```ds-sb
agility: -2
cost: 3 essence for two minions
ev: ""
features:
    - effects:
        - effect: The lumberer's melee [free strikes](../../../../../feature/common/main-actions/free-strike.md) inflict A < AVERAGE [grabbed](../../../../../condition/grabbed.md). A creature or object that starts their turn [grabbed](../../../../../condition/grabbed.md) by the lumberer takes corruption damage equal to your [Reason](../../../../../rule/character/reason.md).
      feature_type: trait
      icon: ⭐️
      name: Zombie Clutch
      type: feature
    - effects:
        - effect: When the lumberer is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), they can latch onto an adjacent enemy before being destroyed. The enemy is M < STRONG [restrained](../../../../../condition/restrained.md) ([EoT](../../../../../rule/combat/end-of-turn.md)).
      feature_type: trait
      icon: ⭐️
      name: Death Grasp
      type: feature
flavor: These massive, animated ogre corpses still maintain their incredible grip strength. When a lumberer falls, they'll take anything within reach down with them.
free_strike: 1
immunities:
    - Corruption R
    - Poison R
intuition: 0
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/zombie-lumberer
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
stability: 0
stamina: 8 | 8
type: statblock
weaknesses: []
```
