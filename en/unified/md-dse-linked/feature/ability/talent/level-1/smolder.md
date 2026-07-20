---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
cost: 3 Clarity
cost_amount: "3"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: 'Choose the [damage type](../../../../rule/damage/damage-type.md) and the weakness for this ability from one of the following: acid, corruption, or fire. The target takes damage before this ability imposes any weakness.'
feature_type: ability
file_basename: smolder
file_dpath: feature/ability/talent/level-1
flavor: Smoke flows from your enemy like tears as their skin begins to blacken and flake.
item_id: smolder
item_name: Smolder
keywords:
    - Psionic
    - Pyrokinesis
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "1"
name: Smolder
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/smolder
source: mcdm.heroes.v1
target: One creature
tier1: 3 + R damage; R < WEAK, the target has weakness 5 (save ends)
tier2: 6 + R damage; R < AVERAGE, the target has weakness 5 (save ends)
tier3: 9 + R damage; R < STRONG, the target has weakness equal to 5 + your [Reason](../../../../rule/character/reason.md) score (save ends)
type: ability
---

```ds-feature
cost: 3 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: 'Choose the [damage type](../../../../rule/damage/damage-type.md) and the weakness for this ability from one of the following: acid, corruption, or fire. The target takes damage before this ability imposes any weakness.'
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 3 + R damage; R < WEAK, the target has weakness 5 (save ends)
      tier2: 6 + R damage; R < AVERAGE, the target has weakness 5 (save ends)
      tier3: 9 + R damage; R < STRONG, the target has weakness equal to 5 + your [Reason](../../../../rule/character/reason.md) score (save ends)
feature_type: ability
flavor: Smoke flows from your enemy like tears as their skin begins to blacken and flake.
keywords:
    - Psionic
    - Pyrokinesis
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    cost: 3 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: 'Choose the [damage type](../../../../rule/damage/damage-type.md) and the weakness for this ability from one of the following: acid, corruption, or fire. The target takes damage before this ability imposes any weakness.'
    flavor: Smoke flows from your enemy like tears as their skin begins to blacken and flake.
    keywords:
        - Psionic
        - Pyrokinesis
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "1"
    name: Smolder
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/smolder
    target: One creature
    tier1: 3 + R damage; R < WEAK, the target has weakness 5 (save ends)
    tier2: 6 + R damage; R < AVERAGE, the target has weakness 5 (save ends)
    tier3: 9 + R damage; R < STRONG, the target has weakness equal to 5 + your [Reason](../../../../rule/character/reason.md) score (save ends)
    type: ability
name: Smolder
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
