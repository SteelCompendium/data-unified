---
action_type: Maneuver
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: Until the start of your next [turn](../../../../rule/combat/turn.md), each target gains a +5 [bonus](../../../../rule/dice/bonuses-and-penalties.md) to [speed](../../../../rule/character/speed.md), they can't be made [dazed](../../../../condition/dazed.md), and they can use an additional maneuver on their [turn](../../../../rule/combat/turn.md). If a target is already [dazed](../../../../condition/dazed.md), that [condition](../../../../rule/combat/condition.md) ends for them.
feature_type: ability
file_basename: applied-chronometrics
file_dpath: feature/ability/talent/level-2
flavor: Time slows down around you. Your heartbeat is the only gauge of the extra moments you've gained.
item_id: applied-chronometrics
item_name: Applied Chronometrics
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "2"
name: Applied Chronometrics
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/applied-chronometrics
source: mcdm.heroes.v1
target: Special
tier1: You target two creatures, one of which can be you.
tier2: You target three creatures, one of which can be you.
tier3: You target four creatures, one of which can be you.
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: Until the start of your next [turn](../../../../rule/combat/turn.md), each target gains a +5 [bonus](../../../../rule/dice/bonuses-and-penalties.md) to [speed](../../../../rule/character/speed.md), they can't be made [dazed](../../../../condition/dazed.md), and they can use an additional maneuver on their [turn](../../../../rule/combat/turn.md). If a target is already [dazed](../../../../condition/dazed.md), that [condition](../../../../rule/combat/condition.md) ends for them.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: You target two creatures, one of which can be you.
      tier2: You target three creatures, one of which can be you.
      tier3: You target four creatures, one of which can be you.
feature_type: ability
flavor: Time slows down around you. Your heartbeat is the only gauge of the extra moments you've gained.
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Maneuver
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: Until the start of your next [turn](../../../../rule/combat/turn.md), each target gains a +5 [bonus](../../../../rule/dice/bonuses-and-penalties.md) to [speed](../../../../rule/character/speed.md), they can't be made [dazed](../../../../condition/dazed.md), and they can use an additional maneuver on their [turn](../../../../rule/combat/turn.md). If a target is already [dazed](../../../../condition/dazed.md), that [condition](../../../../rule/combat/condition.md) ends for them.
    flavor: Time slows down around you. Your heartbeat is the only gauge of the extra moments you've gained.
    keywords:
        - Chronopathy
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "2"
    name: Applied Chronometrics
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/applied-chronometrics
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
