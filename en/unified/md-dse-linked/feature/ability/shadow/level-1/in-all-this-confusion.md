---
action_type: Triggered
class: shadow
distance: Self
effect: You take half the damage, then can [teleport](../../../../movement/teleport.md) up to 4 squares after the triggering effect resolves.
feature_type: ability
file_basename: in-all-this-confusion
file_dpath: feature/ability/shadow/level-1
flavor: You vanish in a plume of black smoke to avoid danger.
item_id: in-all-this-confusion
item_name: In All This Confusion
keywords:
    - Magic
level: "1"
name: In All This Confusion
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion
source: mcdm.heroes.v1
spend: '1+ Insight: You [teleport](../../../../movement/teleport.md) 1 additional square for each insight spent.'
subtype: triggered
target: Self
trigger: You take damage.
type: ability
---

```ds-feature
distance: Self
effects:
    - effect: You take half the damage, then can [teleport](../../../../movement/teleport.md) up to 4 squares after the triggering effect resolves.
    - effect: '1+ Insight: You [teleport](../../../../movement/teleport.md) 1 additional square for each insight spent.'
      name: Spend
feature_type: ability
flavor: You vanish in a plume of black smoke to avoid danger.
keywords:
    - Magic
metadata:
    action_type: Triggered
    class: shadow
    distance: Self
    effect: You take half the damage, then can [teleport](../../../../movement/teleport.md) up to 4 squares after the triggering effect resolves.
    flavor: You vanish in a plume of black smoke to avoid danger.
    keywords:
        - Magic
    level: "1"
    name: In All This Confusion
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/in-all-this-confusion
    spend: '1+ Insight: You [teleport](../../../../movement/teleport.md) 1 additional square for each insight spent.'
    subtype: triggered
    target: Self
    trigger: You take damage.
    type: ability
name: In All This Confusion
target: Self
trigger: You take damage.
type: feature
usage: Triggered
```
