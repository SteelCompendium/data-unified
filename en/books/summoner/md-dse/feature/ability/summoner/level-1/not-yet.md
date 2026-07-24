---
action_type: Triggered
class: summoner
distance: Summoner's Range
effects:
    - effect: If the target is a minion, they must be the only minion remaining in their squad.
      name: Special
    - effect: The [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) the target receives is reduced by an amount that leaves the target alive with 1 point of [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
      name: Effect
feature_source: summoner
feature_type: ability
file_basename: not-yet
file_dpath: feature/ability/summoner/level-1
flavor: I command you to not die.
item_id: not-yet
item_name: Not Yet!
keywords: []
level: "1"
name: Not Yet!
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/not-yet
source: mcdm.summoner.v1
target: One ally
trigger: The target receives enough damage to die or be destroyed.
type: ability
---

```ds-feature
distance: Summoner's Range
effects:
    - effect: If the target is a minion, they must be the only minion remaining in their squad.
      name: Special
    - effect: The [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) the target receives is reduced by an amount that leaves the target alive with 1 point of [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
      name: Effect
feature_type: ability
flavor: I command you to not die.
keywords: []
metadata:
    action_type: Triggered
    class: summoner
    distance: Summoner's Range
    effects:
        - effect: If the target is a minion, they must be the only minion remaining in their squad.
          name: Special
        - effect: The [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) the target receives is reduced by an amount that leaves the target alive with 1 point of [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
          name: Effect
    feature_source: summoner
    flavor: I command you to not die.
    keywords: []
    level: "1"
    name: Not Yet!
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/not-yet
    target: One ally
    trigger: The target receives enough damage to die or be destroyed.
    type: ability
name: Not Yet!
target: One ally
trigger: The target receives enough damage to die or be destroyed.
type: feature
usage: Triggered
```
