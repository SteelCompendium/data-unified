---
action_type: Free triggered
class: fury
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You target a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you with the same strike, using the same [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) as the triggering strike.
feature_type: ability
file_basename: death-strike
file_dpath: feature/ability/fury/level-6
flavor: Once you taste your foe's blood, you become more efficient and [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) every killing blow into an opportunity.
item_id: death-strike
item_name: Death Strike
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "6"
name: Death Strike
scc: mcdm.heroes.v1/feature.ability.fury.level-6/death-strike
source: mcdm.heroes.v1
subclass: reaver
subtype: triggered
target: Self
trigger: You reduce a creature to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You target a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you with the same strike, using the same [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) as the triggering strike.
feature_type: ability
flavor: Once you taste your foe's blood, you become more efficient and [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) every killing blow into an opportunity.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Free triggered
    class: fury
    cost: 9 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You target a creature [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you with the same strike, using the same [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) as the triggering strike.
    flavor: Once you taste your foe's blood, you become more efficient and [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) every killing blow into an opportunity.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "6"
    name: Death Strike
    scc: mcdm.heroes.v1/feature.ability.fury.level-6/death-strike
    subclass: reaver
    subtype: triggered
    target: Self
    trigger: You reduce a creature to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
    type: ability
name: Death Strike
target: Self
trigger: You reduce a creature to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) with a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
type: feature
usage: Free triggered
```
