---
agility: -1
cost: 6 Malice for one minion
cost_amount: "6"
cost_resource: Malice for one minion
file_basename: zombie-titan
file_dpath: monster/rival/4th-echelon/summoner/minion/statblock
free_strike: 7
immunities:
    - Corruption 5
    - poison 5
intuition: 4
item_id: zombie-titan
item_name: Zombie Titan
keywords:
    - Undead
might: 5
movement: —
name: Zombie Titan
organization: Minion
presence: 5
reason: 2
role: Defender
scc: mcdm.summoner.v1/monster.rival.4th-echelon.summoner.minion.statblock/zombie-titan
size: "4"
source: mcdm.summoner.v1
speed: 4
stability: 5
stamina: "50"
type: statblock
weaknesses: []
---

```ds-sb
agility: -1
cost: 6 Malice for one minion
ev: ""
features:
    - effects:
        - effect: The titan's melee [free strikes](../../../../../../feature/common/main-actions/free-strike.md) M < 5 knock the target [prone](../../../../../../condition/prone.md).
      feature_type: trait
      icon: ⭐️
      name: Big Stomp
      type: feature
    - effects:
        - effect: The titan can move through enemies at normal [speed](../../../../../../rule/character/speed.md). If the titan ends their turn in a [prone](../../../../../../condition/prone.md) [size](../../../../../../rule/character/size.md) 2 or smaller creature's space, the creature can't stand.
      feature_type: trait
      icon: ⭐️
      name: Overwhelming Size
      type: feature
    - effects:
        - effect: When the titan is reduced to 0 [Stamina](../../../../../../rule/health/stamina.md), their space becomes [difficult terrain](../../../../../../movement/difficult-terrain.md). If a creature was [prone](../../../../../../condition/prone.md) underneath the titan when the titan is killed, they take 10 damage and are [restrained](../../../../../../condition/restrained.md) (save ends).
      feature_type: trait
      icon: ⭐️
      name: Flesh to Mountains
      type: feature
free_strike: 7
immunities:
    - Corruption 5
    - poison 5
intuition: 4
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.rival.4th-echelon.summoner.minion.statblock/zombie-titan
    source: mcdm.summoner.v1
might: 5
movement: —
name: Zombie Titan
organization: Minion
presence: 5
reason: 2
role: Defender
size: "4"
speed: 4
stability: 5
stamina: "50"
type: statblock
weaknesses: []
```
