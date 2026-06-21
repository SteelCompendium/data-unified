---
action_type: Main action
class: talent
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: hoarfrost
file_dpath: feature/ability/talent/level-1
flavor: You blast a foe with a pulse of cold energy.
item_id: hoarfrost
item_name: Hoarfrost
keywords:
    - Cryokinesis
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
level: "1"
name: Hoarfrost
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + R cold damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier2: 4 + R cold damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier3: 6 + R cold damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R cold damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier2: 4 + R cold damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier3: 6 + R cold damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
feature_type: ability
flavor: You blast a foe with a pulse of cold energy.
keywords:
    - Cryokinesis
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
metadata:
    action_type: Main action
    class: talent
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You blast a foe with a pulse of cold energy.
    keywords:
        - Cryokinesis
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Strike
    level: "1"
    name: Hoarfrost
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/hoarfrost
    subtype: signature
    target: One creature
    tier1: 2 + R cold damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier2: 4 + R cold damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier3: 6 + R cold damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    type: ability
name: Hoarfrost
target: One creature
type: feature
usage: Main action
```
