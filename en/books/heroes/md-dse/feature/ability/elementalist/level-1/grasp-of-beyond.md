---
action_type: Main action
class: elementalist
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
feature_type: ability
file_basename: grasp-of-beyond
file_dpath: feature/ability/elementalist/level-1
flavor: You absorb the life energy of another creature and use it to [teleport](scc.v1:mcdm.heroes.v1/movement/teleport).
item_id: grasp-of-beyond
item_name: Grasp of Beyond
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Void
level: "1"
name: Grasp of Beyond
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/grasp-of-beyond
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + R corruption damage
tier2: 6 + R corruption damage
tier3: 9 + R corruption damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 + R corruption damage
      tier2: 6 + R corruption damage
      tier3: 9 + R corruption damage
feature_type: ability
flavor: You absorb the life energy of another creature and use it to [teleport](scc.v1:mcdm.heroes.v1/movement/teleport).
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Void
metadata:
    action_type: Main action
    class: elementalist
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can [teleport](scc.v1:mcdm.heroes.v1/movement/teleport) up to a number of squares equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score.
    flavor: You absorb the life energy of another creature and use it to [teleport](scc.v1:mcdm.heroes.v1/movement/teleport).
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Void
    level: "1"
    name: Grasp of Beyond
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/grasp-of-beyond
    subtype: signature
    target: One creature
    tier1: 3 + R corruption damage
    tier2: 6 + R corruption damage
    tier3: 9 + R corruption damage
    type: ability
name: Grasp of Beyond
target: One creature
type: feature
usage: Main action
```
