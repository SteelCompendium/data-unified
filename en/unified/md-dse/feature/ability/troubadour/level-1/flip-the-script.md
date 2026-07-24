---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. Any [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed target who was [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) is no longer [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).
      name: Effect
feature_type: ability
file_basename: flip-the-script
file_dpath: feature/ability/troubadour/level-1
flavor: You try a different take on events, justifying the new locations everyone ended up in.
item_id: flip-the-script
item_name: Flip the Script
keywords:
    - Area
    - Magic
level: "1"
name: Flip the Script
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/flip-the-script
source: mcdm.heroes.v1
target: Self and each ally in the area
type: ability
---

```ds-feature
cost: 5 Drama
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. Any [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed target who was [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) is no longer [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).
      name: Effect
feature_type: ability
flavor: You try a different take on events, justifying the new locations everyone ended up in.
keywords:
    - Area
    - Magic
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: troubadour
    cost: 5 Drama
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effects:
        - effect: Each target can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to 5 squares. Any [teleport](scc.v1:mcdm.heroes.v1/movement/teleport)ed target who was [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) is no longer [slowed](scc.v1:mcdm.heroes.v1/condition/slowed).
          name: Effect
    flavor: You try a different take on events, justifying the new locations everyone ended up in.
    keywords:
        - Area
        - Magic
    level: "1"
    name: Flip the Script
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/flip-the-script
    target: Self and each ally in the area
    type: ability
name: Flip the Script
target: Self and each ally in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
