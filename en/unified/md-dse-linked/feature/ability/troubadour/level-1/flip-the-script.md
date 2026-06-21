---
action_type: Main action
class: troubadour
cost: 5 Drama
cost_amount: "5"
cost_resource: Drama
distance: 3 [burst](../../../../rule/combat/burst.md)
effect: Each target can [teleport](../../../../movement/teleport.md) up to 5 squares. Any [teleport](../../../../movement/teleport.md)ed target who was [slowed](../../../../condition/slowed.md) is no longer [slowed](../../../../condition/slowed.md).
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
distance: 3 [burst](../../../../rule/combat/burst.md)
effects:
    - effect: Each target can [teleport](../../../../movement/teleport.md) up to 5 squares. Any [teleport](../../../../movement/teleport.md)ed target who was [slowed](../../../../condition/slowed.md) is no longer [slowed](../../../../condition/slowed.md).
feature_type: ability
flavor: You try a different take on events, justifying the new locations everyone ended up in.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    class: troubadour
    cost: 5 Drama
    distance: 3 [burst](../../../../rule/combat/burst.md)
    effect: Each target can [teleport](../../../../movement/teleport.md) up to 5 squares. Any [teleport](../../../../movement/teleport.md)ed target who was [slowed](../../../../condition/slowed.md) is no longer [slowed](../../../../condition/slowed.md).
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
usage: Main action
```
