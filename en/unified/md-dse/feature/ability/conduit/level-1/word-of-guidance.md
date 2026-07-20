---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: conduit
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).
feature_type: ability
file_basename: word-of-guidance
file_dpath: feature/ability/conduit/level-1
flavor: You invigorate an attacking ally with divine energy.
item_id: word-of-guidance
item_name: Word of Guidance
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Word of Guidance
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/word-of-guidance
source: mcdm.heroes.v1
spend: '1 Piety: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).'
subtype: triggered
target: One ally
trigger: The target makes an [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) for a damage-dealing ability.
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).
    - effect: '1 Piety: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).'
      name: Spend
feature_type: ability
flavor: You invigorate an attacking ally with divine energy.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: conduit
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).
    flavor: You invigorate an attacking ally with divine energy.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Word of Guidance
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/word-of-guidance
    spend: '1 Piety: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) has a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge).'
    subtype: triggered
    target: One ally
    trigger: The target makes an [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) for a damage-dealing ability.
    type: ability
name: Word of Guidance
target: One ally
trigger: The target makes an [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) for a damage-dealing ability.
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
