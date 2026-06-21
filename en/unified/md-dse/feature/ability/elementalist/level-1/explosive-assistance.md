---
action_type: Triggered
class: elementalist
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
feature_type: ability
file_basename: explosive-assistance
file_dpath: feature/ability/elementalist/level-1
flavor: You add a little magic to an ally's aggression at just the right time.
item_id: explosive-assistance
item_name: Explosive Assistance
keywords:
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Explosive Assistance
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/explosive-assistance
source: mcdm.heroes.v1
spend: '1 Essence: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to twice your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score instead.'
subtype: triggered
target: Self or one ally
trigger: The target [force move](scc.v1:mcdm.heroes.v1/movement/forced-movement)s a creature or object.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
    - effect: '1 Essence: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to twice your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score instead.'
      name: Spend
feature_type: ability
flavor: You add a little magic to an ally's aggression at just the right time.
keywords:
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Triggered
    class: elementalist
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
    flavor: You add a little magic to an ally's aggression at just the right time.
    keywords:
        - Fire
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Explosive Assistance
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/explosive-assistance
    spend: '1 Essence: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) gains a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) equal to twice your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score instead.'
    subtype: triggered
    target: Self or one ally
    trigger: The target [force move](scc.v1:mcdm.heroes.v1/movement/forced-movement)s a creature or object.
    type: ability
name: Explosive Assistance
target: Self or one ally
trigger: The target [force move](scc.v1:mcdm.heroes.v1/movement/forced-movement)s a creature or object.
type: feature
usage: Triggered
```
