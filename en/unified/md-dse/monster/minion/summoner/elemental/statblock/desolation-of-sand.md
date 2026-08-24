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
        - effect: The desolation's [free strikes](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) inflict M < AVERAGE [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends). If the target is already [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), then they are M < STRONG [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn)).
      feature_type: trait
      icon: ⭐️
      name: Burying Strike
      type: feature
    - effects:
        - effect: The desolation doesn't provoke [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) by moving.
      feature_type: trait
      icon: ⭐️
      name: Sand Through Your Fingers
      type: feature
    - cost: 1 Essence
      effects:
        - effect: When the desolation is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), the area within 1 square of the desolation becomes [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for enemies until the end of the encounter. You or an ally that enters the affected area can immediately [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 3.
      feature_type: trait
      icon: ⭐️
      name: Shifting Sand Pit
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
