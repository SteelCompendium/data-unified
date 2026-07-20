---
agility: 2
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: archer-spittlich
file_dpath: monster/minion/summoner/demon/statblock
flavor: These minor demons resemble larger pitlings. They can spit a nerve-numbing phlegm at long distance that makes it easy to catch their next meal.
free_strike: 5
free_strike_damage_type: Poison
immunities: []
intuition: -1
item_id: archer-spittlich
item_name: Archer Spittlich
keywords:
    - Abyssal
    - Demon
might: 0
movement: —
name: Archer Spittlich
organization: Minion
presence: 0
reason: -1
role: Artillery
scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/archer-spittlich
size: 1S
source: mcdm.summoner.v1
speed: 5
stability: 2
stamina: 5 | 5
type: statblock
weaknesses:
    - Holy 1
---

```ds-sb
agility: 2
cost: 3 essence for two minions
ev: ""
features:
    - effects:
        - effect: The spittlich's ranged [free strikes](../../../../../feature/common/main-actions/free-strike.md) have a distance of 10 and deal 2 poison damage to an enemy adjacent to the target. Creatures that take poison damage from this spittlich can't [shift](../../../../../movement/shifting.md) until the start of the spittlich's next turn.
      feature_type: trait
      icon: ⭐️
      name: Splash Strike
      type: feature
    - effects:
        - effect: Each creature adjacent to the spittlich can't be [hidden](../../../../../feature/common/maneuvers/hide.md) from them.
      feature_type: trait
      icon: ⭐️
      name: Soulsight
      type: feature
flavor: These minor demons resemble larger pitlings. They can spit a nerve-numbing phlegm at long distance that makes it easy to catch their next meal.
free_strike: 5
immunities: []
intuition: -1
keywords:
    - Abyssal
    - Demon
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.demon.statblock/archer-spittlich
    source: mcdm.summoner.v1
might: 0
movement: —
name: Archer Spittlich
organization: Minion
presence: 0
reason: -1
role: Artillery
size: 1S
speed: 5
stability: 2
stamina: 5 | 5
type: statblock
weaknesses:
    - Holy 1
```
