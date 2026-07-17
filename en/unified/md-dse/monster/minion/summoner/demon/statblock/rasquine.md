---
agility: 0
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: rasquine
file_dpath: monster/minion/summoner/demon/statblock
flavor: The rasquine are skulking demons that shimmer in the light. They teleport into position before biting the necks of their prey.
free_strike: 2
immunities: []
intuition: -1
item_id: rasquine
item_name: Rasquine
keywords:
    - Abyssal
    - Demon
might: -1
movement: Teleport
name: Rasquine
organization: Minion
presence: 2
reason: -1
role: Ambusher
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/rasquine
size: 1S
source: mcdm.summoner.v1
speed: 4
stability: 0
stamina: "2"
type: statblock
weaknesses:
    - Holy 1
---

```ds-sb
agility: 0
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: Once per turn, the rasquine can [hide](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) as a [free maneuver](scc.v1:mcdm.heroes.v1/rule.combat/free-maneuver) after [teleporting](scc.v1:mcdm.heroes.v1/movement/teleport).
      feature_type: trait
      icon: ⭐️
      name: Skulker
      type: feature
    - effects:
        - effect: Each creature adjacent to the rasquine can't be [hidden](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: The rasquine are skulking demons that shimmer in the light. They teleport into position before biting the necks of their prey.
free_strike: 2
immunities: []
intuition: -1
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/rasquine
    source: mcdm.summoner.v1
might: -1
movement: Teleport
name: Rasquine
organization: Minion
presence: 2
reason: -1
role: Ambusher
size: 1S
speed: 4
stability: 0
stamina: "2"
type: statblock
weaknesses:
    - Holy 1
```
