---
action_type: Main action
ancestry: time-raider
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: concussive-slam
file_dpath: feature/ability/time-raider
flavor: You slam an invisible force down upon the target.
item_id: concussive-slam
item_name: Concussive Slam
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
name: Concussive Slam
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.time-raider/concussive-slam
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + R, I, or P damage;
tier2: 5 + R, I, or P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier3: 7 + R, I, or P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < STRONG, [prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 2 + R, I, or P damage;
      tier2: 5 + R, I, or P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 7 + R, I, or P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < STRONG, [prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: You slam an invisible force down upon the target.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    ancestry: time-raider
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You slam an invisible force down upon the target.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    name: Concussive Slam
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.time-raider/concussive-slam
    subtype: signature
    target: One creature or object
    tier1: 2 + R, I, or P damage;
    tier2: 5 + R, I, or P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 7 + R, I, or P damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < STRONG, [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Concussive Slam
target: One creature or object
type: feature
usage: Main action
```
