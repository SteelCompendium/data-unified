---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R damage
      tier2: 4 + R damage
      tier3: 6 + R damage
    - effect: 'When you make this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), choose the [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) from one of the following options: acid, cold, corruption, fire, lightning, poison, or sonic.'
      name: Effect
feature_type: ability
file_basename: hurl-element
file_dpath: feature/ability/elementalist/level-1
flavor: You cast a ball of elemental energy at a foe.
item_id: hurl-element
item_name: Hurl Element
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Hurl Element
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/hurl-element
source: mcdm.heroes.v1
target: One creature or object
tier1: 2 + R damage
tier2: 4 + R damage
tier3: 6 + R damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R damage
      tier2: 4 + R damage
      tier3: 6 + R damage
    - effect: 'When you make this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), choose the [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) from one of the following options: acid, cold, corruption, fire, lightning, poison, or sonic.'
      name: Effect
feature_type: ability
flavor: You cast a ball of elemental energy at a foe.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 2 + R damage
          tier2: 4 + R damage
          tier3: 6 + R damage
        - effect: 'When you make this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), choose the [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) from one of the following options: acid, cold, corruption, fire, lightning, poison, or sonic.'
          name: Effect
    flavor: You cast a ball of elemental energy at a foe.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Hurl Element
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/hurl-element
    target: One creature or object
    tier1: 2 + R damage
    tier2: 4 + R damage
    tier3: 6 + R damage
    type: ability
name: Hurl Element
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
