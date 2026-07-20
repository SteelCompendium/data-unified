---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: A worthless [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1M object drops onto the target to deal the damage, then rolls into an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space of your choice. The object is made of wood, stone, or metal (your choice).
feature_type: ability
file_basename: materialize
file_dpath: feature/ability/talent/level-1
flavor: You picture an object in your mind and give it form—directly above your opponent's head.
item_id: materialize
item_name: Materialize
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Resopathy
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Materialize
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/materialize
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + R damage
tier2: 5 + R damage
tier3: 8 + R damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: A worthless [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1M object drops onto the target to deal the damage, then rolls into an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space of your choice. The object is made of wood, stone, or metal (your choice).
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 + R damage
      tier2: 5 + R damage
      tier3: 8 + R damage
feature_type: ability
flavor: You picture an object in your mind and give it form—directly above your opponent's head.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Resopathy
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: A worthless [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1M object drops onto the target to deal the damage, then rolls into an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) unoccupied space of your choice. The object is made of wood, stone, or metal (your choice).
    flavor: You picture an object in your mind and give it form—directly above your opponent's head.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Resopathy
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Materialize
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/materialize
    subtype: signature
    target: One creature or object
    tier1: 3 + R damage
    tier2: 5 + R damage
    tier3: 8 + R damage
    type: ability
name: Materialize
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
