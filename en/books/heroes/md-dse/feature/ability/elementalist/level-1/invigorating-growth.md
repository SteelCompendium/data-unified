---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 3 Essence
cost_amount: "3"
cost_resource: Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 4 + R poison damage
      tier2: 7 + R poison damage
      tier3: 11 + R poison damage
    - effect: Mushrooms cover the target's body. While the mushrooms are on the target, you and any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) whenever the target takes damage. The mushrooms can be removed by the target or an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature as a main action.
      name: Effect
feature_type: ability
file_basename: invigorating-growth
file_dpath: feature/ability/elementalist/level-1
flavor: Mushrooms erupt from a foe, sapping their vitality to spread strengthening spores.
item_id: invigorating-growth
item_name: Invigorating Growth
keywords:
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Invigorating Growth
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/invigorating-growth
source: mcdm.heroes.v1
target: One creature
tier1: 4 + R poison damage
tier2: 7 + R poison damage
tier3: 11 + R poison damage
type: ability
---

```ds-feature
cost: 3 Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 4 + R poison damage
      tier2: 7 + R poison damage
      tier3: 11 + R poison damage
    - effect: Mushrooms cover the target's body. While the mushrooms are on the target, you and any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) whenever the target takes damage. The mushrooms can be removed by the target or an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature as a main action.
      name: Effect
feature_type: ability
flavor: Mushrooms erupt from a foe, sapping their vitality to spread strengthening spores.
keywords:
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 3 Essence
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 4 + R poison damage
          tier2: 7 + R poison damage
          tier3: 11 + R poison damage
        - effect: Mushrooms cover the target's body. While the mushrooms are on the target, you and any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) whenever the target takes damage. The mushrooms can be removed by the target or an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) creature as a main action.
          name: Effect
    flavor: Mushrooms erupt from a foe, sapping their vitality to spread strengthening spores.
    keywords:
        - Green
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Invigorating Growth
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/invigorating-growth
    target: One creature
    tier1: 4 + R poison damage
    tier2: 7 + R poison damage
    tier3: 11 + R poison damage
    type: ability
name: Invigorating Growth
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
