---
agility: -2
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: principle-of-the-swamp
file_dpath: monster/minion/summoner/elemental/statblock
flavor: The manes of these equine sludge dwellers extend and hook into things like strong, fraying arms. This allows the principle of the swamp to either pull themselves onto dry land, or pull their prey into the dank depths.
free_strike: 4
immunities:
    - Corruption R
    - Poison R
intuition: 2
item_id: principle-of-the-swamp
item_name: Principle of the Swamp
keywords:
    - Elemental (Green)
    - Elemental (Water)
    - Elemental (Rot)
might: 3
movement: Swim
name: Principle of the Swamp
organization: Minion
presence: -2
reason: 0
role: Brute
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/principle-of-the-swamp
size: "2"
source: mcdm.summoner.v1
speed: 4
stamina: 5 | 5 | 5
type: statblock
weaknesses: []
---

```ds-sb
agility: -2
cost: 5 essence for three minions
ev: ""
features:
    - effects:
        - effect: The principle's melee [free strikes](../../../../../feature/common/main-actions/free-strike.md) have a distance of R and inflict M < STRONG [grabbed](../../../../../condition/grabbed.md). The principle can have an unlimited number of creatures or objects [grabbed](../../../../../condition/grabbed.md). A creature [grabbed](../../../../../condition/grabbed.md) by this [strike](../../../../../rule/combat/strike.md) still has their normal [speed](../../../../../rule/character/speed.md), but can't move farther away from the principle.
      feature_type: trait
      icon: ⭐️
      name: Encroaching Strike
      type: feature
flavor: The manes of these equine sludge dwellers extend and hook into things like strong, fraying arms. This allows the principle of the swamp to either pull themselves onto dry land, or pull their prey into the dank depths.
free_strike: 4
immunities:
    - Corruption R
    - Poison R
intuition: 2
keywords:
    - Elemental (Green)
    - Elemental (Water)
    - Elemental (Rot)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/principle-of-the-swamp
    source: mcdm.summoner.v1
might: 3
movement: Swim
name: Principle of the Swamp
organization: Minion
presence: -2
reason: 0
role: Brute
size: "2"
speed: 4
stability: 0
stamina: 5 | 5 | 5
type: statblock
weaknesses: []
```
