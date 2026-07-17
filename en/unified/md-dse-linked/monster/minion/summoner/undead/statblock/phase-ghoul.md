---
agility: 3
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: phase-ghoul
file_dpath: monster/minion/summoner/undead/statblock
flavor: Phase ghouls are bilocated undead caught between two different manifolds, rapidly flickering between them. They almost appear transparent save for their long, bright blue tongues that appears to lag behind their movements by a full second.
free_strike: 3
immunities:
    - Corruption R
    - Poison R
intuition: 0
item_id: phase-ghoul
item_name: Phase Ghoul
keywords:
    - Undead
might: 2
movement: Teleport
name: Phase Ghoul
organization: Minion
presence: 1
reason: -2
role: Harrier
scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/phase-ghoul
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: 5 | 5 | 5
type: statblock
weaknesses: []
---

```ds-sb
agility: 3
cost: 5 essence for three minions
ev: ""
features:
    - effects:
        - effect: The ghoul [teleports](../../../../../movement/teleport.md) 5 squares before making a melee [free strike](../../../../../feature/common/main-actions/free-strike.md). The target is M < AVERAGE knocked [prone](../../../../../condition/prone.md). If the target is in the air, the [potency](../../../../../rule/character/potency.md) increases by 1.
      feature_type: trait
      icon: ⭐️
      name: Leaping Strike
      type: feature
    - effects:
        - effect: The ghoul takes no [damage](../../../../../rule/damage/damage.md) from [falling](../../../../../rule/health/falling.md) and always lands on their feet.
      feature_type: trait
      icon: ⭐️
      name: Nerveless
      type: feature
flavor: Phase ghouls are bilocated undead caught between two different manifolds, rapidly flickering between them. They almost appear transparent save for their long, bright blue tongues that appears to lag behind their movements by a full second.
free_strike: 3
immunities:
    - Corruption R
    - Poison R
intuition: 0
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.undead.statblock/phase-ghoul
    source: mcdm.summoner.v1
might: 2
movement: Teleport
name: Phase Ghoul
organization: Minion
presence: 1
reason: -2
role: Harrier
size: 1M
speed: 5
stability: 0
stamina: 5 | 5 | 5
type: statblock
weaknesses: []
```
