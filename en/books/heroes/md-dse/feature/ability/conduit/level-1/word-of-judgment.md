---
action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
class: conduit
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) against the target.
feature_type: ability
file_basename: word-of-judgment
file_dpath: feature/ability/conduit/level-1
flavor: Your holy word saps an attacking enemy's strength.
item_id: word-of-judgment
item_name: Word of Judgment
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Word of Judgment
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/word-of-judgment
source: mcdm.heroes.v1
spend: '1 Piety: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) has a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) against the target.'
subtype: triggered
target: One ally
trigger: The target would take damage from an ability that uses a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) against the target.
    - effect: '1 Piety: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) has a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) against the target.'
      name: Spend
feature_type: ability
flavor: Your holy word saps an attacking enemy's strength.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
    class: conduit
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) against the target.
    flavor: Your holy word saps an attacking enemy's strength.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Word of Judgment
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/word-of-judgment
    spend: '1 Piety: The [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) has a double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) against the target.'
    subtype: triggered
    target: One ally
    trigger: The target would take damage from an ability that uses a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    type: ability
name: Word of Judgment
target: One ally
trigger: The target would take damage from an ability that uses a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
type: feature
usage: '[Triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)'
```
