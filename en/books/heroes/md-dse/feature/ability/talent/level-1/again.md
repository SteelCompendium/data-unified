---
action_type: Triggered
class: talent
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You can use this ability after seeing the result of the triggering roll. The target must reroll the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) and use the new roll.
feature_type: ability
file_basename: again
file_dpath: feature/ability/talent/level-1
flavor: You step back a split second to see if things play out a little differently.
item_id: again
item_name: Again
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Again
scc: mcdm.heroes.v1/feature.ability.talent.level-1/again
source: mcdm.heroes.v1
subclass: chronopathy
subtype: triggered
target: Self or one creature
trigger: The target makes an [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll).
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You can use this ability after seeing the result of the triggering roll. The target must reroll the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) and use the new roll.
feature_type: ability
flavor: You step back a split second to see if things play out a little differently.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Triggered
    class: talent
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You can use this ability after seeing the result of the triggering roll. The target must reroll the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) and use the new roll.
    flavor: You step back a split second to see if things play out a little differently.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Again
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/again
    subclass: chronopathy
    subtype: triggered
    target: Self or one creature
    trigger: The target makes an [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll).
    type: ability
name: Again
target: Self or one creature
trigger: The target makes an [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll).
type: feature
usage: Triggered
```
