---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against a creature of your choice. This [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) can target the creature even if it usually wouldn't. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target of this ability.
feature_type: ability
file_basename: subvert-the-green-within
file_dpath: feature/ability/elementalist/level-2
flavor: Fungal spores sprout inside your enemy's brain, allowing you to control their actions.
item_id: subvert-the-green-within
item_name: Subvert the Green Within
keywords:
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Void
level: "2"
name: Subvert the Green Within
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-2/subvert-the-green-within
source: mcdm.heroes.v1
target: One creature
tier1: 5 + R poison damage
tier2: 9 + R poison damage
tier3: 12 + R poison damage
type: ability
---

```ds-feature
cost: 5 Essence
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against a creature of your choice. This [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) can target the creature even if it usually wouldn't. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target of this ability.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 5 + R poison damage
      tier2: 9 + R poison damage
      tier3: 12 + R poison damage
feature_type: ability
flavor: Fungal spores sprout inside your enemy's brain, allowing you to control their actions.
keywords:
    - Green
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Void
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 5 Essence
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The target uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against a creature of your choice. This [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) can target the creature even if it usually wouldn't. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target of this ability.
    flavor: Fungal spores sprout inside your enemy's brain, allowing you to control their actions.
    keywords:
        - Green
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Void
    level: "2"
    name: Subvert the Green Within
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-2/subvert-the-green-within
    target: One creature
    tier1: 5 + R poison damage
    tier2: 9 + R poison damage
    tier3: 12 + R poison damage
    type: ability
name: Subvert the Green Within
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
