---
agility: 4
cost: 7 essence for three minions
cost_amount: "7"
cost_resource: essence for three minions
file_basename: iron-reaver
file_dpath: monster/minion/summoner/elemental/statblock
flavor: Iron reavers are long, gnashing lines of centipede-like bladed legs. Their bodies endlessly shed metal shavings and hard sheets of iron as they move.
free_strike: 6
immunities:
    - Poison R
intuition: 0
item_id: iron-reaver
item_name: Iron Reaver
keywords:
    - Elemental (Earth)
    - Elemental (Fire)
    - Elemental (Void)
might: 3
movement: Burrow
name: Iron Reaver
organization: Minion
presence: -1
reason: 0
role: Harrier
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/iron-reaver
size: 1L
source: mcdm.summoner.v1
speed: 6
stamina: 10 | 10 | 10
type: statblock
weaknesses: []
---

```ds-sb
agility: 4
cost: 7 essence for three minions
ev: ""
features:
    - effects:
        - effect: The reaver has [cover](../../../../../rule/combat/cover.md) while [adjacent](../../../../../rule/combat/adjacent.md) to another reaver they were summoned with. Whenever they receive an effect that allows them to move or [shift](../../../../../movement/shifting.md) outside of their move action, they share the effect with each [adjacent](../../../../../rule/combat/adjacent.md) reaver they were summoned with.
      feature_type: trait
      icon: ⭐️
      name: Decentralized Segments
      type: feature
    - effects:
        - effect: The reaver's [free strikes](../../../../../feature/common/main-actions/free-strike.md) inflict M < WEAK [bleeding](../../../../../condition/bleeding.md) (save ends). Each time the reaver inflicts [bleeding](../../../../../condition/bleeding.md) on a creature, they can [shift](../../../../../movement/shifting.md) 2 and make an additional [free strike](../../../../../feature/common/main-actions/free-strike.md) on a new target.
      feature_type: trait
      icon: ⭐️
      name: Bladed Strike
      type: feature
flavor: Iron reavers are long, gnashing lines of centipede-like bladed legs. Their bodies endlessly shed metal shavings and hard sheets of iron as they move.
free_strike: 6
immunities:
    - Poison R
intuition: 0
keywords:
    - Elemental (Earth)
    - Elemental (Fire)
    - Elemental (Void)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/iron-reaver
    source: mcdm.summoner.v1
might: 3
movement: Burrow
name: Iron Reaver
organization: Minion
presence: -1
reason: 0
role: Harrier
size: 1L
speed: 6
stability: 0
stamina: 10 | 10 | 10
type: statblock
weaknesses: []
```
