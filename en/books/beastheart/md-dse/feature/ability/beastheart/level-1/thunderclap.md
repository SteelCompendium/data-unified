---
action_type: Triggered Action
class: beastheart
distance: Melee 1
effects:
    - effect: You deal sonic damage equal to your Might score to the target and push them up to a number of squares equal to 1 + your Might score. If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) pushes the target away from the creature they damaged, the creature takes half the triggering damage.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) distance is doubled.
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
subclass: punisher
target: One enemy
trigger: The target deals damage to a creature.
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You deal sonic damage equal to your Might score to the target and push them up to a number of squares equal to 1 + your Might score. If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) pushes the target away from the creature they damaged, the creature takes half the triggering damage.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) distance is doubled.
feature_type: ability
flavor: The force of your counterattack cracks the air.
keywords:
    - Melee
    - Weapon
metadata:
    action_type: Triggered Action
    class: beastheart
    distance: Melee 1
    effects:
        - effect: You deal sonic damage equal to your Might score to the target and push them up to a number of squares equal to 1 + your Might score. If this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) pushes the target away from the creature they damaged, the creature takes half the triggering damage.
          name: Effect
        - cost: Spend 1 Ferocity
          effect: The [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) distance is doubled.
    flavor: The force of your counterattack cracks the air.
    keywords:
        - Melee
        - Weapon
    level: "1"
    name: Thunderclap
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/thunderclap
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
