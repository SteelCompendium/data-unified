---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
cost: 5 Essence
cost_amount: "5"
cost_resource: Essence
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
feature_type: ability
file_basename: conflagration
file_dpath: feature/ability/elementalist/level-1
flavor: A storm of fire descends upon your enemies.
item_id: conflagration
item_name: Conflagration
keywords:
    - Area
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Conflagration
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/conflagration
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 4 fire damage
tier2: 6 fire damage
tier3: 10 fire damage
type: ability
---

```ds-feature
cost: 5 Essence
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 4 fire damage
      tier2: 6 fire damage
      tier3: 10 fire damage
feature_type: ability
flavor: A storm of fire descends upon your enemies.
keywords:
    - Area
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    cost: 5 Essence
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    flavor: A storm of fire descends upon your enemies.
    keywords:
        - Area
        - Fire
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Conflagration
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/conflagration
    target: Each enemy in the area
    tier1: 4 fire damage
    tier2: 6 fire damage
    tier3: 10 fire damage
    type: ability
name: Conflagration
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
