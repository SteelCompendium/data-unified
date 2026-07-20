---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
feature_type: ability
file_basename: blade-of-the-heavens
file_dpath: feature/ability/conduit/level-6
flavor: A greatsword streams down from the sky, threatening to pin your foe.
item_id: blade-of-the-heavens
item_name: Blade of the Heavens
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "6"
name: Blade of the Heavens
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/blade-of-the-heavens
source: mcdm.heroes.v1
subclass: war
target: One creature
tier1: 8 + I damage; A < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 12 + I damage; A < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 16 + I damage; A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---

```ds-feature
cost: 9 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 8 + I damage; A < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 12 + I damage; A < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 16 + I damage; A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
feature_type: ability
flavor: A greatsword streams down from the sky, threatening to pin your foe.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 9 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    flavor: A greatsword streams down from the sky, threatening to pin your foe.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "6"
    name: Blade of the Heavens
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/blade-of-the-heavens
    subclass: war
    target: One creature
    tier1: 8 + I damage; A < WEAK, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier2: 12 + I damage; A < AVERAGE, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier3: 16 + I damage; A < STRONG, [prone and](scc.v1:mcdm.heroes.v1/condition/prone) [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    type: ability
name: Blade of the Heavens
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
