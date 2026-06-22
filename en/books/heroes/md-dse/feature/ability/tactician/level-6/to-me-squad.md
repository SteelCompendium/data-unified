---
action_type: Main action
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends). If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before one or both allies has made their [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
feature_type: ability
file_basename: to-me-squad
file_dpath: feature/ability/tactician/level-6
flavor: You lead your allies in a charge.
item_id: to-me-squad
item_name: To Me Squad!
keywords:
    - Charge
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: To Me Squad!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/to-me-squad
source: mcdm.heroes.v1
subclass: vanguard
target: One creature
tier1: 6 + M damage; one ally within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
tier2: 9 + M damage; one ally within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
tier3: 13 + M damage; two allies within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can each use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends). If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before one or both allies has made their [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage; one ally within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
      tier2: 9 + M damage; one ally within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
      tier3: 13 + M damage; two allies within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can each use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
feature_type: ability
flavor: You lead your allies in a charge.
keywords:
    - Charge
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: tactician
    cost: 9 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: If the target is hit with two or more strikes as part of this ability and they have R < STRONG, they are [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends). If the target is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before one or both allies has made their [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the ally or allies can pick a different target.
    flavor: You lead your allies in a charge.
    keywords:
        - Charge
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: To Me Squad!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/to-me-squad
    subclass: vanguard
    target: One creature
    tier1: 6 + M damage; one ally within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
    tier2: 9 + M damage; one ally within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
    tier3: 13 + M damage; two allies within 10 squares can use the [Charge](scc.v1:mcdm.heroes.v1/feature.common.main-actions/charge) main action as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), and can each use a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) that gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) instead of a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) for the charge
    type: ability
name: To Me Squad!
target: One creature
type: feature
usage: Main action
```
