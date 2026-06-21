---
action_type: Triggered
class: conduit
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: The [power roll](../../../../rule/dice/power-roll.md) takes a [bane](../../../../rule/dice/bane.md) against the target.
feature_type: ability
file_basename: word-of-judgment
file_dpath: feature/ability/conduit/level-1
flavor: Your holy word saps an attacking enemy's strength.
item_id: word-of-judgment
item_name: Word of Judgment
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "1"
name: Word of Judgment
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/word-of-judgment
source: mcdm.heroes.v1
spend: '1 Piety: The [power roll](../../../../rule/dice/power-roll.md) has a double [bane](../../../../rule/dice/bane.md) against the target.'
subtype: triggered
target: One ally
trigger: The target would take damage from an ability that uses a [power roll](../../../../rule/dice/power-roll.md).
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: The [power roll](../../../../rule/dice/power-roll.md) takes a [bane](../../../../rule/dice/bane.md) against the target.
    - effect: '1 Piety: The [power roll](../../../../rule/dice/power-roll.md) has a double [bane](../../../../rule/dice/bane.md) against the target.'
      name: Spend
feature_type: ability
flavor: Your holy word saps an attacking enemy's strength.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Triggered
    class: conduit
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: The [power roll](../../../../rule/dice/power-roll.md) takes a [bane](../../../../rule/dice/bane.md) against the target.
    flavor: Your holy word saps an attacking enemy's strength.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "1"
    name: Word of Judgment
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/word-of-judgment
    spend: '1 Piety: The [power roll](../../../../rule/dice/power-roll.md) has a double [bane](../../../../rule/dice/bane.md) against the target.'
    subtype: triggered
    target: One ally
    trigger: The target would take damage from an ability that uses a [power roll](../../../../rule/dice/power-roll.md).
    type: ability
name: Word of Judgment
target: One ally
trigger: The target would take damage from an ability that uses a [power roll](../../../../rule/dice/power-roll.md).
type: feature
usage: Triggered
```
