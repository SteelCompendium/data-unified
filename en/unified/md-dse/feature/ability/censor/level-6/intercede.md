---
action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
class: censor
cost: 9 Wrath
cost_amount: "9"
cost_resource: Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target is unaffected by the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) and you become the target instead, even if you aren't a valid target for it. You take half the damage from the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), and the target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
feature_type: ability
file_basename: intercede
file_dpath: feature/ability/censor/level-6
flavor: You take your ally's place.
item_id: intercede
item_name: Intercede
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "6"
name: Intercede
scc: mcdm.heroes.v1/feature.ability.censor.level-6/intercede
source: mcdm.heroes.v1
subclass: paragon
subtype: triggered
target: One ally
trigger: A creature makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against the target.
type: ability
---

```ds-feature
cost: 9 Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The target is unaffected by the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) and you become the target instead, even if you aren't a valid target for it. You take half the damage from the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), and the target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
feature_type: ability
flavor: You take your ally's place.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    class: censor
    cost: 9 Wrath
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - effect: The target is unaffected by the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) and you become the target instead, even if you aren't a valid target for it. You take half the damage from the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), and the target gains 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
          name: Effect
    flavor: You take your ally's place.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "6"
    name: Intercede
    scc: mcdm.heroes.v1/feature.ability.censor.level-6/intercede
    subclass: paragon
    subtype: triggered
    target: One ally
    trigger: A creature makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against the target.
    type: ability
name: Intercede
target: One ally
trigger: A creature makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against the target.
type: feature
usage: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
```
