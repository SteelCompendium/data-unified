---
action_type: Triggered
class: tactician
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), which they can use on the triggering damage.
feature_type: ability
file_basename: advanced-tactics
file_dpath: feature/ability/tactician/level-1
flavor: Your leadership aids an ally.
item_id: advanced-tactics
item_name: Advanced Tactics
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Advanced Tactics
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/advanced-tactics
source: mcdm.heroes.v1
spend: '1 Focus: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effect associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is increased by 1.'
subclass: insurgent
subtype: triggered
target: One ally
trigger: The target deals damage to another creature.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), which they can use on the triggering damage.
    - effect: '1 Focus: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effect associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is increased by 1.'
      name: Spend
feature_type: ability
flavor: Your leadership aids an ally.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Triggered
    class: tactician
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), which they can use on the triggering damage.
    flavor: Your leadership aids an ally.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Advanced Tactics
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/advanced-tactics
    spend: '1 Focus: If the damage has any [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) effect associated with it, the [potency](scc.v1:mcdm.heroes.v1/rule.character/potency) is increased by 1.'
    subclass: insurgent
    subtype: triggered
    target: One ally
    trigger: The target deals damage to another creature.
    type: ability
name: Advanced Tactics
target: One ally
trigger: The target deals damage to another creature.
type: feature
usage: Triggered
```
