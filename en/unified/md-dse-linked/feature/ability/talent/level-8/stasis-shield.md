---
action_type: Triggered
class: talent
cost: 3 Clarity
cost_amount: "3"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: The target is [teleport](../../../../movement/teleport.md)ed to an unoccupied space [adjacent](../../../../rule/combat/adjacent.md) to you, taking no damage and suffering no additional effects if this movement would get them out of harm's way.
feature_type: ability
file_basename: stasis-shield
file_dpath: feature/ability/talent/level-8
flavor: You freeze time just long enough to bring the victim to safety!
item_id: stasis-shield
item_name: Stasis Shield
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "8"
name: Stasis Shield
scc: mcdm.heroes.v1/feature.ability.talent.level-8/stasis-shield
source: mcdm.heroes.v1
subclass: chronopathy
subtype: triggered
target: Self, or one creature or object
trigger: The target takes damage.
type: ability
---

```ds-feature
cost: 3 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The target is [teleport](../../../../movement/teleport.md)ed to an unoccupied space [adjacent](../../../../rule/combat/adjacent.md) to you, taking no damage and suffering no additional effects if this movement would get them out of harm's way.
feature_type: ability
flavor: You freeze time just long enough to bring the victim to safety!
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Triggered
    class: talent
    cost: 3 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: The target is [teleport](../../../../movement/teleport.md)ed to an unoccupied space [adjacent](../../../../rule/combat/adjacent.md) to you, taking no damage and suffering no additional effects if this movement would get them out of harm's way.
    flavor: You freeze time just long enough to bring the victim to safety!
    keywords:
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "8"
    name: Stasis Shield
    scc: mcdm.heroes.v1/feature.ability.talent.level-8/stasis-shield
    subclass: chronopathy
    subtype: triggered
    target: Self, or one creature or object
    trigger: The target takes damage.
    type: ability
name: Stasis Shield
target: Self, or one creature or object
trigger: The target takes damage.
type: feature
usage: Triggered
```
