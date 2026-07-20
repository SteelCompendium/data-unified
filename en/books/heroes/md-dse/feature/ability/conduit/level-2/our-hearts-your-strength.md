---
action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: Until the end of the encounter or until the target is [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), at the start of each of the target's [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), they gain a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [rolled damage](scc.v1:mcdm.heroes.v1/rule.damage/rolled-damage) equal to the number of allies within 10 squares of them. This [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) lasts until the start of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
file_basename: our-hearts-your-strength
file_dpath: feature/ability/conduit/level-2
flavor: An ally gains strength from their friends.
item_id: our-hearts-your-strength
item_name: Our Hearts Your Strength
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "2"
name: Our Hearts Your Strength
scc: mcdm.heroes.v1/feature.ability.conduit.level-2/our-hearts-your-strength
source: mcdm.heroes.v1
subclass: love
target: Self and one ally
type: ability
---

```ds-feature
cost: 5 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: Until the end of the encounter or until the target is [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), at the start of each of the target's [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), they gain a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [rolled damage](scc.v1:mcdm.heroes.v1/rule.damage/rolled-damage) equal to the number of allies within 10 squares of them. This [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) lasts until the start of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
feature_type: ability
flavor: An ally gains strength from their friends.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: conduit
    cost: 5 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: Until the end of the encounter or until the target is [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), at the start of each of the target's [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), they gain a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and a [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) to [rolled damage](scc.v1:mcdm.heroes.v1/rule.damage/rolled-damage) equal to the number of allies within 10 squares of them. This [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties) lasts until the start of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
    flavor: An ally gains strength from their friends.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "2"
    name: Our Hearts Your Strength
    scc: mcdm.heroes.v1/feature.ability.conduit.level-2/our-hearts-your-strength
    subclass: love
    target: Self and one ally
    type: ability
name: Our Hearts Your Strength
target: Self and one ally
type: feature
usage: '[Maneuver](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
