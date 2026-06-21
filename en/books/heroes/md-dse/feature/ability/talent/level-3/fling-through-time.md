---
action_type: Main action
class: talent
cost: 7 Clarity
cost_amount: "7"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: A target who is flung through time is removed from the encounter map until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), reappearing in their original space or the nearest unoccupied space.
feature_type: ability
file_basename: fling-through-time
file_dpath: feature/ability/talent/level-3
flavor: You hurl the target through the annals of time, forcing them to witness every moment of their existence all at once.
item_id: fling-through-time
item_name: Fling Through Time
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
level: "3"
name: Fling Through Time
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.talent.level-3/fling-through-time
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + P corruption damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 5 + P corruption damage; the target is flung through time, and if P < AVERAGE, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 8 + P corruption damage; the target is flung through time, and if P < STRONG, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---

```ds-feature
cost: 7 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: A target who is flung through time is removed from the encounter map until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), reappearing in their original space or the nearest unoccupied space.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 3 + P corruption damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 5 + P corruption damage; the target is flung through time, and if P < AVERAGE, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 8 + P corruption damage; the target is flung through time, and if P < STRONG, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
feature_type: ability
flavor: You hurl the target through the annals of time, forcing them to witness every moment of their existence all at once.
keywords:
    - Chronopathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
metadata:
    action_type: Main action
    class: talent
    cost: 7 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: A target who is flung through time is removed from the encounter map until the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), reappearing in their original space or the nearest unoccupied space.
    flavor: You hurl the target through the annals of time, forcing them to witness every moment of their existence all at once.
    keywords:
        - Chronopathy
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Strike
    level: "3"
    name: Fling Through Time
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-3/fling-through-time
    target: One creature or object
    tier1: 3 + P corruption damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 5 + P corruption damage; the target is flung through time, and if P < AVERAGE, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 8 + P corruption damage; the target is flung through time, and if P < STRONG, they are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    type: ability
name: Fling Through Time
target: One creature or object
type: feature
usage: Main action
```
