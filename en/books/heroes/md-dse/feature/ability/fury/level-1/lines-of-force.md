---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: fury
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can select a new target of the same [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) to be force moved instead. You become the source of the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), determine the new target's destination, and can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target instead of using the original [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) type. Additionally, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
feature_type: ability
file_basename: lines-of-force
file_dpath: feature/ability/fury/level-1
flavor: You redirect the energy of motion.
item_id: lines-of-force
item_name: Lines of Force
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
level: "1"
name: Lines of Force
scc: mcdm.heroes.v1/feature.ability.fury.level-1/lines-of-force
source: mcdm.heroes.v1
spend: '1 Ferocity: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score instead.'
subclass: berserker
subtype: triggered
target: Self or one creature
trigger: The target would be [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can select a new target of the same [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) to be force moved instead. You become the source of the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), determine the new target's destination, and can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target instead of using the original [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) type. Additionally, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
    - effect: '1 Ferocity: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score instead.'
      name: Spend
feature_type: ability
flavor: You redirect the energy of motion.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: fury
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can select a new target of the same [size](scc.v1:mcdm.heroes.v1/rule.character/size) or smaller within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) to be force moved instead. You become the source of the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement), determine the new target's destination, and can [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target instead of using the original [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) type. Additionally, the [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score.
    flavor: You redirect the energy of motion.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    level: "1"
    name: Lines of Force
    scc: mcdm.heroes.v1/feature.ability.fury.level-1/lines-of-force
    spend: '1 Ferocity: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score instead.'
    subclass: berserker
    subtype: triggered
    target: Self or one creature
    trigger: The target would be [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
    type: ability
name: Lines of Force
target: Self or one creature
trigger: The target would be [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
