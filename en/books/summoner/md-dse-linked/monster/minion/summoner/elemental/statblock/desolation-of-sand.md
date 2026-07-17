---
agility: 2
cost: 3 essence for two minions
cost_amount: "3"
cost_resource: essence for two minions
file_basename: desolation-of-sand
file_dpath: monster/minion/summoner/elemental/statblock
flavor: The desolations have vaguely humanoid sand forms with no legs. Their glass hose “arms” shift and bristle before firing high pressure streams of sand at their foes.
free_strike: 4
immunities:
    - Sonic R
intuition: 0
item_id: desolation-of-sand
item_name: Desolation of Sand
keywords:
    - Elemental (Air)
    - Elemental (Earth)
might: 1
movement: Burrow
name: Desolation of Sand
organization: Minion
presence: -2
reason: 0
role: Hexer
scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/desolation-of-sand
size: 1M
source: mcdm.summoner.v1
speed: 5
stability: 1
stamina: 5 | 5
type: statblock
weaknesses: []
---

```ds-sb
agility: 2
cost: 3 essence for two minions
ev: ""
features:
    - effects:
        - effect: The desolation's [free strikes](../../../../../feature/common/main-actions/free-strike.md) inflict M < AVERAGE [slowed](../../../../../condition/slowed.md) (save ends). If the target is already [slowed](../../../../../condition/slowed.md), then they are M < STRONG [restrained](../../../../../condition/restrained.md) ([EoT](../../../../../rule/combat/end-of-turn.md)).
      feature_type: trait
      icon: ⭐️
      name: Burying Strike
      type: feature
    - effects:
        - effect: The desolation doesn't provoke [opportunity attacks](../../../../../rule/combat/opportunity-attack.md) by moving.
      feature_type: trait
      icon: ⭐️
      name: Sand Through Your Fingers
      type: feature
flavor: The desolations have vaguely humanoid sand forms with no legs. Their glass hose “arms” shift and bristle before firing high pressure streams of sand at their foes.
free_strike: 4
immunities:
    - Sonic R
intuition: 0
keywords:
    - Elemental (Air)
    - Elemental (Earth)
level: 0
metadata:
    scc: mcdm.summoner.v1/monster.minion.summoner.elemental.statblock/desolation-of-sand
    source: mcdm.summoner.v1
might: 1
movement: Burrow
name: Desolation of Sand
organization: Minion
presence: -2
reason: 0
role: Hexer
size: 1M
speed: 5
stability: 1
stamina: 5 | 5
type: statblock
weaknesses: []
```
