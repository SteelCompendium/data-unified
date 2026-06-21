---
action_type: Triggered Action
class: beastheart
effect: You end the [forced movement](../../../../movement/forced-movement.md). You can then push the creature up to a number of squares equal to 1 + your Might score. The creature takes 1 damage for each square they are force moved this way.
feature_type: ability
file_basename: this-ones-yours
file_dpath: feature/ability/beastheart/level-2
item_id: this-ones-yours
item_name: This One's Yours
level: "2"
name: This One's Yours
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/this-ones-yours
source: mcdm.beastheart.v1
spend: '1 Ferocity: You and your companions can each use this free triggered action on the same turn.'
subclass: punisher
trigger: A creature [force moved](../../../../movement/forced-movement.md) by another creature enters a space adjacent to you.
type: ability
---

```ds-feature
effects:
    - effect: You end the [forced movement](../../../../movement/forced-movement.md). You can then push the creature up to a number of squares equal to 1 + your Might score. The creature takes 1 damage for each square they are force moved this way.
    - effect: '1 Ferocity: You and your companions can each use this free triggered action on the same turn.'
      name: Spend
feature_type: ability
metadata:
    action_type: Triggered Action
    class: beastheart
    effect: You end the [forced movement](../../../../movement/forced-movement.md). You can then push the creature up to a number of squares equal to 1 + your Might score. The creature takes 1 damage for each square they are force moved this way.
    level: "2"
    name: This One's Yours
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/this-ones-yours
    spend: '1 Ferocity: You and your companions can each use this free triggered action on the same turn.'
    subclass: punisher
    trigger: A creature [force moved](../../../../movement/forced-movement.md) by another creature enters a space adjacent to you.
    type: ability
name: This One's Yours
trigger: A creature [force moved](../../../../movement/forced-movement.md) by another creature enters a space adjacent to you.
type: feature
usage: Triggered Action
```
