---
action_type: Triggered
class: troubadour
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: The target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the creature who made the triggering strike.
feature_type: ability
file_basename: riposte
file_dpath: feature/ability/troubadour/level-1
flavor: '"I''d have brought treats had I known I''d be fighting a dog."'
item_id: riposte
item_name: Riposte
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
level: "1"
name: Riposte
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/riposte
source: mcdm.heroes.v1
subtype: triggered
target: Self or one ally
trigger: The target takes damage from a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: The target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the creature who made the triggering strike.
feature_type: ability
flavor: '"I''d have brought treats had I known I''d be fighting a dog."'
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
metadata:
    action_type: Triggered
    class: troubadour
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: The target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against the creature who made the triggering strike.
    flavor: '"I''d have brought treats had I known I''d be fighting a dog."'
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    level: "1"
    name: Riposte
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/riposte
    subtype: triggered
    target: Self or one ally
    trigger: The target takes damage from a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
    type: ability
name: Riposte
target: Self or one ally
trigger: The target takes damage from a [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike).
type: feature
usage: Triggered
```
