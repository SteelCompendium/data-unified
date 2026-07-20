---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: A target can't use [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) while their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is reduced this way.
feature_type: ability
file_basename: slow
file_dpath: feature/ability/talent/level-2
flavor: Perhaps they wonder why everyone else is moving so quickly?
item_id: slow
item_name: Slow
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Slow
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/slow
source: mcdm.heroes.v1
subclass: chronopathy
target: Three creatures or objects
tier1: The target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is halved (save ends), or if P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
tier2: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
tier3: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < STRONG, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: A target can't use [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) while their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is reduced this way.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: The target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is halved (save ends), or if P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
      tier2: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
      tier3: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < STRONG, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
feature_type: ability
flavor: Perhaps they wonder why everyone else is moving so quickly?
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: A target can't use [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) while their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is reduced this way.
    flavor: Perhaps they wonder why everyone else is moving so quickly?
    keywords:
        - Chronopathy
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Slow
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/slow
    subclass: chronopathy
    target: Three creatures or objects
    tier1: The target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is halved (save ends), or if P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends).
    tier2: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
    tier3: The target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends), or if P < STRONG, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 (save ends).
    type: ability
name: Slow
target: Three creatures or objects
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
