---
action_type: Maneuver
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each target gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), they can't be made [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), and they can use an additional maneuver on their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). If a target is already [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), that [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) ends for them.
feature_type: ability
file_basename: applied-chronometrics
file_dpath: feature/ability/talent/level-2
flavor: Time slows down around you. Your heartbeat is the only gauge of the extra moments you've gained.
item_id: applied-chronometrics
item_name: Applied Chronometrics
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Applied Chronometrics
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/applied-chronometrics
source: mcdm.heroes.v1
subclass: chronopathy
target: Special
tier1: You target two creatures, one of which can be you.
tier2: You target three creatures, one of which can be you.
tier3: You target four creatures, one of which can be you.
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each target gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), they can't be made [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), and they can use an additional maneuver on their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). If a target is already [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), that [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) ends for them.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: You target two creatures, one of which can be you.
      tier2: You target three creatures, one of which can be you.
      tier3: You target four creatures, one of which can be you.
feature_type: ability
flavor: Time slows down around you. Your heartbeat is the only gauge of the extra moments you've gained.
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Maneuver
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), each target gains a +5 [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed), they can't be made [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), and they can use an additional maneuver on their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). If a target is already [dazed](scc.v1:mcdm.heroes.v1/condition/dazed), that [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) ends for them.
    flavor: Time slows down around you. Your heartbeat is the only gauge of the extra moments you've gained.
    keywords:
        - Chronopathy
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Applied Chronometrics
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/applied-chronometrics
    subclass: chronopathy
    target: Special
    tier1: You target two creatures, one of which can be you.
    tier2: You target three creatures, one of which can be you.
    tier3: You target four creatures, one of which can be you.
    type: ability
name: Applied Chronometrics
target: Special
type: feature
usage: Maneuver
```
