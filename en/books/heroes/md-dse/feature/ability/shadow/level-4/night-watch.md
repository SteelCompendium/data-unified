---
action_type: Triggered
class: shadow
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effect: The target takes half the damage. You remain hidden.
feature_type: ability
file_basename: night-watch
file_dpath: feature/ability/shadow/level-4
flavor: A steely dagger from out of the blue knocks another weapon off course.
item_id: night-watch
item_name: Night Watch
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Weapon
level: "4"
name: Night Watch
scc: mcdm.heroes.v1/feature.ability.shadow.level-4/night-watch
source: mcdm.heroes.v1
subtype: triggered
target: One ally
trigger: The target takes damage from another creature's ability while you are hidden.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: The target takes half the damage. You remain hidden.
feature_type: ability
flavor: A steely dagger from out of the blue knocks another weapon off course.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Weapon
metadata:
    action_type: Triggered
    class: shadow
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effect: The target takes half the damage. You remain hidden.
    flavor: A steely dagger from out of the blue knocks another weapon off course.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Weapon
    level: "4"
    name: Night Watch
    scc: mcdm.heroes.v1/feature.ability.shadow.level-4/night-watch
    subtype: triggered
    target: One ally
    trigger: The target takes damage from another creature's ability while you are hidden.
    type: ability
name: Night Watch
target: One ally
trigger: The target takes damage from another creature's ability while you are hidden.
type: feature
usage: Triggered
```
