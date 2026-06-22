---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: Choose acid, cold, corruption, fire, lightning, poison, or sonic damage. The target loses any [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) to the chosen type and gains weakness 10 to the chosen type (save ends).
feature_type: ability
file_basename: primordial-bane
file_dpath: feature/ability/fury/level-9
flavor: You attune the target to be weaker to a specific element.
item_id: primordial-bane
item_name: Primordial Bane
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Primordial Bane
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-9/primordial-bane
source: mcdm.heroes.v1
subclass: reaver
target: One creature
tier1: 11 + M damage
tier2: 16 + M damage
tier3: 21 + M damage
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Choose acid, cold, corruption, fire, lightning, poison, or sonic damage. The target loses any [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) to the chosen type and gains weakness 10 to the chosen type (save ends).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 11 + M damage
      tier2: 16 + M damage
      tier3: 21 + M damage
feature_type: ability
flavor: You attune the target to be weaker to a specific element.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 11 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Choose acid, cold, corruption, fire, lightning, poison, or sonic damage. The target loses any [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity) to the chosen type and gains weakness 10 to the chosen type (save ends).
    flavor: You attune the target to be weaker to a specific element.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Primordial Bane
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/primordial-bane
    subclass: reaver
    target: One creature
    tier1: 11 + M damage
    tier2: 16 + M damage
    tier3: 21 + M damage
    type: ability
name: Primordial Bane
target: One creature
type: feature
usage: Main action
```
