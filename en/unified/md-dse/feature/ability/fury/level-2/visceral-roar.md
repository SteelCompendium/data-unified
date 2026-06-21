---
action_type: Main action
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: This ability deals your primordial [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) (see [Stormwight Kits](scc.v1:mcdm.heroes.v1/feature.fury.stormwight-kits/kit-features)).
feature_type: ability
file_basename: visceral-roar
file_dpath: feature/ability/fury/level-2
flavor: The sound of the storm within you staggers your opponents.
item_id: visceral-roar
item_name: Visceral Roar
keywords:
    - Area
    - Magic
level: "2"
name: Visceral Roar
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-2/visceral-roar
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: This ability deals your primordial [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) (see [Stormwight Kits](scc.v1:mcdm.heroes.v1/feature.fury.stormwight-kits/kit-features)).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
flavor: The sound of the storm within you staggers your opponents.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: fury
    cost: 5 Ferocity
    distance: 2 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: This ability deals your primordial [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) (see [Stormwight Kits](scc.v1:mcdm.heroes.v1/feature.fury.stormwight-kits/kit-features)).
    flavor: The sound of the storm within you staggers your opponents.
    keywords:
        - Area
        - Magic
    level: "2"
    name: Visceral Roar
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-2/visceral-roar
    target: Each enemy in the area
    tier1: 2 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1; M < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier2: 5 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2; M < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    tier3: 7 damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 3; M < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    type: ability
name: Visceral Roar
target: Each enemy in the area
type: feature
usage: Main action
```
