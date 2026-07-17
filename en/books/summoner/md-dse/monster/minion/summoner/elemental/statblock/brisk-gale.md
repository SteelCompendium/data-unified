---
agility: 2
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: brisk-gale
file_dpath: monster/minion/summoner/elemental/statblock
flavor: The gales are twisting ribbons of cloud and debris endlessly dancing in place. They disrupt the air and allow their allies to move freely.
free_strike: 1
immunities:
    - Sonic R
intuition: 0
item_id: brisk-gale
item_name: Brisk Gale
keywords:
    - Elemental (Air)
might: -2
movement: Fly
name: Brisk Gale
organization: Minion
presence: 1
reason: 0
role: Harrier
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/brisk-gale
size: 1S
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: "2"
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: The gale doesn't provoke [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) by moving.
      feature_type: trait
      icon: ⭐️
      name: Cutting the Air
      type: feature
    - effects:
        - effect: When the gale is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), winds whip in their space until the end of the encounter. You or an ally that enters this space or starts their turn there can immediately [shift](scc.v1:mcdm.heroes.v1/movement/shifting) (including vertically).
      feature_type: trait
      icon: ⭐️
      name: Whirlwind
      type: feature
flavor: The gales are twisting ribbons of cloud and debris endlessly dancing in place. They disrupt the air and allow their allies to move freely.
free_strike: 1
immunities:
    - Sonic R
intuition: 0
keywords:
    - Elemental (Air)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/brisk-gale
    source: mcdm.summoner.v1
might: -2
movement: Fly
name: Brisk Gale
organization: Minion
presence: 1
reason: 0
role: Harrier
size: 1S
speed: 5
stability: 0
stamina: "2"
type: statblock
weaknesses: []
```
