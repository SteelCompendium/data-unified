---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 11 Wrath
cost_amount: "11"
cost_resource: Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: While the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, each of their allies who starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) within 5 squares of them must use a [free maneuver](scc.v1:mcdm.heroes.v1/rule.combat/free-maneuver) to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target. Additionally, while the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, each of their allies within 5 squares of them who can make a triggered [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a different creature must make the [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target instead.
feature_type: ability
file_basename: your-allies-turn-on-you
file_dpath: feature/ability/censor/level-8
flavor: You [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) your enemies' ire to the target.
item_id: your-allies-turn-on-you
item_name: Your Allies Turn on You!
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Your Allies Turn on You!
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.censor.level-8/your-allies-turn-on-you
source: mcdm.heroes.v1
target: One creature
tier1: 5 + P damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 9 + P damage; I < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 12 + P damage; I < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---

```ds-feature
cost: 11 Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: While the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, each of their allies who starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) within 5 squares of them must use a [free maneuver](scc.v1:mcdm.heroes.v1/rule.combat/free-maneuver) to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target. Additionally, while the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, each of their allies within 5 squares of them who can make a triggered [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a different creature must make the [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target instead.
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + P damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 9 + P damage; I < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 12 + P damage; I < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: You [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) your enemies' ire to the target.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 11 Wrath
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: While the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, each of their allies who starts their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) within 5 squares of them must use a [free maneuver](scc.v1:mcdm.heroes.v1/rule.combat/free-maneuver) to make a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target. Additionally, while the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, each of their allies within 5 squares of them who can make a triggered [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a different creature must make the [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the target instead.
    flavor: You [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) your enemies' ire to the target.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: Your Allies Turn on You!
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-8/your-allies-turn-on-you
    target: One creature
    tier1: 5 + P damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 9 + P damage; I < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 12 + P damage; I < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: Your Allies Turn on You!
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
