---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target is marked by you until the end of the encounter, until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or until you use this ability again. You can willingly end your mark on a creature (no action required), and if another [tactician](scc.v1:mcdm.heroes.v1/class/tactician) marks a creature, your mark on that creature ends. When a creature marked by you is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), you can use a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to mark a new target within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
      name: Effect
feature_type: ability
file_basename: mark
file_dpath: feature/ability/tactician/level-1
flavor: You draw your allies' attention to a specific foe—with devastating effect.
item_id: mark
item_name: Mark
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Mark
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mark
source: mcdm.heroes.v1
target: One creature
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target is marked by you until the end of the encounter, until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or until you use this ability again. You can willingly end your mark on a creature (no action required), and if another [tactician](scc.v1:mcdm.heroes.v1/class/tactician) marks a creature, your mark on that creature ends. When a creature marked by you is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), you can use a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to mark a new target within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
      name: Effect
feature_type: ability
flavor: You draw your allies' attention to a specific foe—with devastating effect.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: The target is marked by you until the end of the encounter, until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or until you use this ability again. You can willingly end your mark on a creature (no action required), and if another [tactician](scc.v1:mcdm.heroes.v1/class/tactician) marks a creature, your mark on that creature ends. When a creature marked by you is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), you can use a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) to mark a new target within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
          name: Effect
    flavor: You draw your allies' attention to a specific foe—with devastating effect.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Mark
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/mark
    target: One creature
    type: ability
name: Mark
target: One creature
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
