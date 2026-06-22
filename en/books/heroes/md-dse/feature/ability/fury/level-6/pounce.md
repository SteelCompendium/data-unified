---
action_type: Main action
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 4 squares, bringing the target with you. While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, the target takes damage equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score at the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: pounce
file_dpath: feature/ability/fury/level-6
flavor: You strike at the target like the ultimate predator you are.
item_id: pounce
item_name: Pounce
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Pounce
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-6/pounce
source: mcdm.heroes.v1
subclass: stormwight
target: One creature
tier1: 8 damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier2: 13 damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier3: 17 damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 4 squares, bringing the target with you. While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, the target takes damage equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score at the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 8 damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 13 damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 17 damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
flavor: You strike at the target like the ultimate predator you are.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to 4 squares, bringing the target with you. While [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, the target takes damage equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score at the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: You strike at the target like the ultimate predator you are.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: Pounce
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/pounce
    subclass: stormwight
    target: One creature
    tier1: 8 damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier2: 13 damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier3: 17 damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: Pounce
target: One creature
type: feature
usage: Main action
```
