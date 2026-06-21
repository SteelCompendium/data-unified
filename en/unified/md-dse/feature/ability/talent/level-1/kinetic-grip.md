---
action_type: Main action
class: talent
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: kinetic-grip
file_dpath: feature/ability/talent/level-1
flavor: You lift and hurl your foe away from you.
item_id: kinetic-grip
item_name: Kinetic Grip
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telekinesis
level: "1"
name: Kinetic Grip
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/kinetic-grip
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2 + R'
tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4 + R'
tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 + R; [prone](scc.v1:mcdm.heroes.v1/condition/prone)'
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2 + R'
      tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4 + R'
      tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 + R; [prone](scc.v1:mcdm.heroes.v1/condition/prone)'
feature_type: ability
flavor: You lift and hurl your foe away from you.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telekinesis
metadata:
    action_type: Main action
    class: talent
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You lift and hurl your foe away from you.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Telekinesis
    level: "1"
    name: Kinetic Grip
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/kinetic-grip
    subtype: signature
    target: One creature or object
    tier1: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2 + R'
    tier2: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 4 + R'
    tier3: '[Slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) 6 + R; [prone](scc.v1:mcdm.heroes.v1/condition/prone)'
    type: ability
name: Kinetic Grip
target: One creature or object
type: feature
usage: Main action
```
