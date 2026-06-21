---
action_type: Main action
class: talent
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
feature_type: ability
file_basename: hoarfrost
file_dpath: feature/ability/talent/level-1
flavor: You blast a foe with a pulse of cold energy.
item_id: hoarfrost
item_name: Hoarfrost
keywords:
    - Cryokinesis
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
level: "1"
name: Hoarfrost
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + R cold damage; M < WEAK, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
tier2: 4 + R cold damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
tier3: 6 + R cold damage; M < STRONG, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 2 + R cold damage; M < WEAK, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
      tier2: 4 + R cold damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
      tier3: 6 + R cold damage; M < STRONG, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
feature_type: ability
flavor: You blast a foe with a pulse of cold energy.
keywords:
    - Cryokinesis
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
metadata:
    action_type: Main action
    class: talent
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    flavor: You blast a foe with a pulse of cold energy.
    keywords:
        - Cryokinesis
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Strike
    level: "1"
    name: Hoarfrost
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
    subtype: signature
    target: One creature
    tier1: 2 + R cold damage; M < WEAK, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
    tier2: 4 + R cold damage; M < AVERAGE, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
    tier3: 6 + R cold damage; M < STRONG, [slowed](../../../../condition/slowed.md) ([EoT](../../../../rule/combat/end-of-turn.md))
    type: ability
name: Hoarfrost
target: One creature
type: feature
usage: Main action
```
