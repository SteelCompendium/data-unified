---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: elementalist
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target takes half the damage.
      name: Effect
    - cost: Spend 1 Essence
      effect: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is reduced by 1 for the target.
feature_type: ability
file_basename: skin-like-castle-walls
file_dpath: feature/ability/elementalist/level-1
flavor: You cover yourself or an ally in protective stone.
item_id: skin-like-castle-walls
item_name: Skin Like Castle Walls
keywords:
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Skin Like Castle Walls
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/skin-like-castle-walls
source: mcdm.heroes.v1
subclass: earth
subtype: triggered
target: Self or one ally
trigger: The target takes damage.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target takes half the damage.
      name: Effect
    - cost: Spend 1 Essence
      effect: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is reduced by 1 for the target.
feature_type: ability
flavor: You cover yourself or an ally in protective stone.
keywords:
    - Earth
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: elementalist
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: The target takes half the damage.
          name: Effect
        - cost: Spend 1 Essence
          effect: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effects associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is reduced by 1 for the target.
    flavor: You cover yourself or an ally in protective stone.
    keywords:
        - Earth
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Skin Like Castle Walls
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/skin-like-castle-walls
    subclass: earth
    subtype: triggered
    target: Self or one ally
    trigger: The target takes damage.
    type: ability
name: Skin Like Castle Walls
target: Self or one ally
trigger: The target takes damage.
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
