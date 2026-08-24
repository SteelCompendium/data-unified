---
agility: 2
cost: 5 essence for three minions
cost_amount: "5"
cost_resource: essence for three minions
file_basename: dancing-silk
file_dpath: monster/minion/summoner/elemental/statblock
flavor: The silks are akin to baby spiders ballooning through the air on strands of webbing. They spin silk from their legs as they fly, eventually turning huge swaths of the environment into tangled web mazes.
free_strike: 3
immunities:
    - Poison R
intuition: 0
item_id: dancing-silk
item_name: Dancing Silk
keywords:
    - Elemental (Earth)
    - Elemental (Air)
    - Elemental (Green)
might: -1
movement: Fly
name: Dancing Silk
organization: Minion
presence: -1
reason: 3
role: Controller
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/dancing-silk
size: 1T
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: 4 | 4 | 4
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 5 essence for three minions
ev: ""
features:
    - effects:
        - effect: The silk's ranged [free strikes](../../../../../feature/common/main-actions/free-strike.md) inflict A < AVERAGE [restrained](../../../../../condition/restrained.md) (EoT). Each creature [adjacent](../../../../../rule/combat/adjacent.md) to the target is A < WEAK [slowed](../../../../../condition/slowed.md) (EoT).
      feature_type: trait
      icon: ⭐️
      name: Entangling Strike
      type: feature
    - cost: 1 Essence
      effects:
        - effect: When the silk is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), they launch ribbons of webbing into an area equal to their [size](../../../../../rule/character/size.md) + 1 within 5 before being destroyed. The affected area is considered [difficult terrain](../../../../../movement/difficult-terrain.md) for enemies until the end of the encounter. An enemy that ends their [turn](../../../../../rule/combat/turn.md) in the webbing is M < STRONG [slowed](../../../../../condition/slowed.md) (EoT).
      feature_type: trait
      icon: ⭐️
      name: Web
      type: feature
flavor: The silks are akin to baby spiders ballooning through the air on strands of webbing. They spin silk from their legs as they fly, eventually turning huge swaths of the environment into tangled web mazes.
free_strike: 3
immunities:
    - Poison R
intuition: 0
keywords:
    - Elemental (Earth)
    - Elemental (Air)
    - Elemental (Green)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/dancing-silk
    source: mcdm.summoner.v1
might: -1
movement: Fly
name: Dancing Silk
organization: Minion
presence: -1
reason: 3
role: Controller
size: 1T
speed: 5
stability: 0
stamina: 4 | 4 | 4
type: statblock
weaknesses: []
```
