---
action_type: Triggered Action
class: beastheart
distance: Melee 1
effect: You deal sonic damage equal to your Might score to the target and push them up to a number of squares equal to 1 + your Might score. If this [forced movement](../../../../movement/forced-movement.md) pushes the target away from the creature they damaged, the creature takes half the triggering damage.
feature_type: ability
file_basename: thunderclap
file_dpath: feature/ability/beastheart/level-1
flavor: The force of your counterattack cracks the air.
item_id: thunderclap
item_name: Thunderclap
keywords:
    - Melee
    - Weapon
level: "1"
name: Thunderclap
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/thunderclap
source: mcdm.beastheart.v1
spend: '1 Ferocity: The [forced movement](../../../../movement/forced-movement.md) distance is doubled.'
subclass: punisher
target: One enemy
trigger: The target deals damage to a creature.
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You deal sonic damage equal to your Might score to the target and push them up to a number of squares equal to 1 + your Might score. If this [forced movement](../../../../movement/forced-movement.md) pushes the target away from the creature they damaged, the creature takes half the triggering damage.
    - effect: '1 Ferocity: The [forced movement](../../../../movement/forced-movement.md) distance is doubled.'
      name: Spend
feature_type: ability
flavor: The force of your counterattack cracks the air.
keywords:
    - Melee
    - Weapon
metadata:
    action_type: Triggered Action
    class: beastheart
    distance: Melee 1
    effect: You deal sonic damage equal to your Might score to the target and push them up to a number of squares equal to 1 + your Might score. If this [forced movement](../../../../movement/forced-movement.md) pushes the target away from the creature they damaged, the creature takes half the triggering damage.
    flavor: The force of your counterattack cracks the air.
    keywords:
        - Melee
        - Weapon
    level: "1"
    name: Thunderclap
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/thunderclap
    spend: '1 Ferocity: The [forced movement](../../../../movement/forced-movement.md) distance is doubled.'
    subclass: punisher
    target: One enemy
    trigger: The target deals damage to a creature.
    type: ability
name: Thunderclap
target: One enemy
trigger: The target deals damage to a creature.
type: feature
usage: Triggered Action
```
