---
agility: -2
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: crux-of-ash
file_dpath: monster/minion/summoner/elemental/statblock
flavor: The crux is a curtain of billowing hot ash with an avian head. They cover their victims in a burning cloak of charcoal and soot.
free_strike: 5
immunities:
    - Fire R
    - Sonic R
intuition: 0
item_id: crux-of-ash
item_name: Crux of Ash
keywords:
    - Elemental (Fire)
    - Elemental (Air)
might: -2
movement: Fly
name: Crux of Ash
organization: Minion
presence: 1
reason: 0
role: Ambusher
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/crux-of-ash
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 0
stamina: 6 | 6
type: statblock
weaknesses: []
---

```ds-sb
agility: -2
cost: 3 essence for two minions
ev: ""
features:
    - effects:
        - effect: The crux's melee [free strikes](../../../../../feature/common/main-actions/free-strike.md) M < AVERAGE automatically [hide](../../../../../feature/common/maneuvers/hide.md) each ally from the target until the start of the crux's next turn, until the target uses a [maneuver](../../../../../rule/combat/turn.md) to clear the soot, until the crux takes damage, or until the crux is destroyed.
      feature_type: trait
      icon: ⭐️
      name: Soot Strike
      type: feature
    - cost: 1 Essence
      effects:
        - effect: When the crux is reduced to 0 [Stamina](../../../../../rule/health/stamina.md), the area within 1 square of the crux is clouded by ash until it is dispersed by wind. You or any ally are [concealed](../../../../../rule/combat/concealment.md) while occupying an affected square. An enemy can't establish [line of effect](../../../../../rule/combat/line-of-effect.md) beyond the ash while occupying an affected square.
      feature_type: trait
      icon: ⭐️
      name: Ashen Cloud
      type: feature
flavor: The crux is a curtain of billowing hot ash with an avian head. They cover their victims in a burning cloak of charcoal and soot.
free_strike: 5
immunities:
    - Fire R
    - Sonic R
intuition: 0
keywords:
    - Elemental (Fire)
    - Elemental (Air)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/crux-of-ash
    source: mcdm.summoner.v1
might: -2
movement: Fly
name: Crux of Ash
organization: Minion
presence: 1
reason: 0
role: Ambusher
size: 1M
speed: 5
stability: 0
stamina: 6 | 6
type: statblock
weaknesses: []
```
