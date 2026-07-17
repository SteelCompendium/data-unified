---
agility: 4
cost: 1 Malice per minion summoned
cost_amount: "1"
cost_resource: Malice per minion summoned
file_basename: skeleton
file_dpath: monster/rival/3rd-echelon/summoner/minion/statblock
free_strike: 1
immunities:
    - Corruption 4
    - poison 4
intuition: 2
item_id: skeleton
item_name: Skeleton
keywords:
    - Undead
might: 0
movement: Climb
name: Skeleton
organization: Minion
presence: 0
reason: 2
role: Harrier
scc: mcdm.summoner.v1/monster.rival.3rd-echelon.summoner.minion.statblock/skeleton
size: 1M
source: mcdm.summoner.v1
speed: 6
stability: 0
stamina: "4"
type: statblock
weaknesses: []
---

```ds-sb
agility: 4
cost: 1 Malice per minion summoned
ev: ""
features:
    - effects:
        - effect: When the skeleton is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), their square becomes [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies. The first time any enemy enters this space, they take 2 damage and end this effect.
      feature_type: trait
      icon: ⭐️
      name: Bonetrops
      type: feature
free_strike: 1
immunities:
    - Corruption 4
    - poison 4
intuition: 2
keywords:
    - Undead
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.rival.3rd-echelon.summoner.minion.statblock/skeleton
    source: mcdm.summoner.v1
might: 0
movement: Climb
name: Skeleton
organization: Minion
presence: 0
reason: 2
role: Harrier
size: 1M
speed: 6
stability: 0
stamina: "4"
type: statblock
weaknesses: []
```
