---
action_type: Main action
class: elementalist
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: bifurcated-incineration
file_dpath: feature/ability/elementalist/level-1
flavor: Two jets of flame lance out at your command.
item_id: bifurcated-incineration
item_name: Bifurcated Incineration
keywords:
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Bifurcated Incineration
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/bifurcated-incineration
source: mcdm.heroes.v1
subtype: signature
target: Two creatures or objects
tier1: 2 fire damage
tier2: 4 fire damage
tier3: 6 fire damage
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 fire damage
      tier2: 4 fire damage
      tier3: 6 fire damage
feature_type: ability
flavor: Two jets of flame lance out at your command.
keywords:
    - Fire
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: elementalist
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: Two jets of flame lance out at your command.
    keywords:
        - Fire
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Bifurcated Incineration
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/bifurcated-incineration
    subtype: signature
    target: Two creatures or objects
    tier1: 2 fire damage
    tier2: 4 fire damage
    tier3: 6 fire damage
    type: ability
name: Bifurcated Incineration
target: Two creatures or objects
type: feature
usage: Main action
```
