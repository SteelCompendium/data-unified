---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effect: A column of fire remains in the area until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each enemy who enters the area for the first time in a [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) or starts their turn there takes 2 fire damage.
feature_type: ability
file_basename: incinerate
file_dpath: feature/ability/talent/level-1
flavor: The air erupts into a column of smokeless flame.
item_id: incinerate
item_name: Incinerate
keywords:
    - Area
    - Fire
    - Psionic
    - Pyrokinesis
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Incinerate
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/incinerate
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 fire damage
tier2: 4 fire damage
tier3: 6 fire damage
type: ability
---

```ds-feature
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: A column of fire remains in the area until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each enemy who enters the area for the first time in a [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) or starts their turn there takes 2 fire damage.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 fire damage
      tier2: 4 fire damage
      tier3: 6 fire damage
feature_type: ability
flavor: The air erupts into a column of smokeless flame.
keywords:
    - Area
    - Fire
    - Psionic
    - Pyrokinesis
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effect: A column of fire remains in the area until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each enemy who enters the area for the first time in a [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) or starts their turn there takes 2 fire damage.
    flavor: The air erupts into a column of smokeless flame.
    keywords:
        - Area
        - Fire
        - Psionic
        - Pyrokinesis
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Incinerate
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/incinerate
    subtype: signature
    target: Each enemy in the area
    tier1: 2 fire damage
    tier2: 4 fire damage
    tier3: 6 fire damage
    type: ability
name: Incinerate
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
