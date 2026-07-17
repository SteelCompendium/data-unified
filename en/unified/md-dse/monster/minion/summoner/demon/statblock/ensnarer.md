---
agility: 0
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: ensnarer
file_dpath: monster/minion/summoner/demon/statblock
flavor: This vaguely humanoid form is warped and distorted by a demon nestled inside them. They extend long tongues from multiple orifices to drag victims in close.
free_strike: 2
immunities: []
intuition: -1
item_id: ensnarer
item_name: Ensnarer
keywords:
    - Abyssal
    - Demon
might: 2
movement: —
name: Ensnarer
organization: Minion
presence: -1
reason: -1
role: Brute
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/ensnarer
size: 1M
source: mcdm.summoner.v1
speed: 5
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
        - effect: The ensnarer's melee [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) have a distance of 3 and inflict [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1. The [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) distance increases by 1 for each additional ensnarer striking the same target. Choose the ensnarer that the target is being pulled to before applying [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement).
      feature_type: trait
      icon: ⭐️
      name: Extended Barbed Strike
      type: feature
    - effects:
        - effect: Each creature adjacent to the ensnarer can't be [hidden](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: This vaguely humanoid form is warped and distorted by a demon nestled inside them. They extend long tongues from multiple orifices to drag victims in close.
free_strike: 2
immunities: []
intuition: -1
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/ensnarer
    source: mcdm.summoner.v1
might: 2
movement: —
name: Ensnarer
organization: Minion
presence: -1
reason: -1
role: Brute
size: 1M
speed: 5
stability: 0
stamina: "2"
type: statblock
weaknesses:
    - Holy 1
```
