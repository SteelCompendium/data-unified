---
action_type: Triggered
class: summoner
distance: Summoner's Range
effect: The target gains a [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) for each of your minions [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them (up to a maximum of 3 surges), which they can use on the triggering damage.
feature_source: summoner
feature_type: ability
file_basename: focus-fire
file_dpath: feature/ability/summoner/level-1
flavor: You ensure the enemy can't escape the incoming attack.
item_id: focus-fire
item_name: Focus Fire!
keywords:
    - —
level: "1"
name: Focus Fire!
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/focus-fire
source: mcdm.summoner.v1
spend: '1 Essence: If the triggering damage is from an ability that uses a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).'
target: Self or one ally
trigger: The target deals [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to another creature.
type: ability
---

```ds-feature
distance: Summoner's Range
effects:
    - effect: The target gains a [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) for each of your minions [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them (up to a maximum of 3 surges), which they can use on the triggering damage.
    - effect: '1 Essence: If the triggering damage is from an ability that uses a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).'
      name: Spend
feature_type: ability
flavor: You ensure the enemy can't escape the incoming attack.
keywords:
    - —
metadata:
    action_type: Triggered
    class: summoner
    distance: Summoner's Range
    effect: The target gains a [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) for each of your minions [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them (up to a maximum of 3 surges), which they can use on the triggering damage.
    feature_source: summoner
    flavor: You ensure the enemy can't escape the incoming attack.
    keywords:
        - —
    level: "1"
    name: Focus Fire!
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/focus-fire
    spend: '1 Essence: If the triggering damage is from an ability that uses a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).'
    target: Self or one ally
    trigger: The target deals [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to another creature.
    type: ability
name: Focus Fire!
target: Self or one ally
trigger: The target deals [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage) to another creature.
type: feature
usage: Triggered
```
