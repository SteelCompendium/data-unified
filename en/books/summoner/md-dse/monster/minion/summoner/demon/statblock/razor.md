---
agility: 2
cost: 1 essence per minion summoned
cost_amount: "1"
cost_resource: essence per minion summoned
file_basename: razor
file_dpath: monster/minion/summoner/demon/statblock
flavor: Razors appear to be a diminutive variant of the ruinant demon. Their bodies are swift, tumbling mounds of scarred flesh and deadly claws.
free_strike: 1
immunities: []
intuition: -1
item_id: razor
item_name: Razor
keywords:
    - Abyssal
    - Demon
might: 0
movement: —
name: Razor
organization: Minion
presence: -1
reason: -1
role: Harrier
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/razor
size: 1M
source: mcdm.summoner.v1
speed: 6
stability: 0
stamina: "2"
type: statblock
weaknesses:
    - Holy 1
---

```ds-sb
agility: 2
cost: 1 essence per minion summoned
ev: ""
features:
    - effects:
        - effect: Once per turn, whenever an adjacent enemy [grabs](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/grab) the razor or uses a melee ability against them, that enemy takes 1 damage for each razor adjacent to them.
      feature_type: trait
      icon: ⭐️
      name: Teeth!
      type: feature
    - effects:
        - effect: Each creature adjacent to the razor can't be [hidden](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/hide) from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: Razors appear to be a diminutive variant of the ruinant demon. Their bodies are swift, tumbling mounds of scarred flesh and deadly claws.
free_strike: 1
immunities: []
intuition: -1
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/razor
    source: mcdm.summoner.v1
might: 0
movement: —
name: Razor
organization: Minion
presence: -1
reason: -1
role: Harrier
size: 1M
speed: 6
stability: 0
stamina: "2"
type: statblock
weaknesses:
    - Holy 1
```
