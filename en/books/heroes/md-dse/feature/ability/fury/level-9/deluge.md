---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 7 damage
      tier2: 10 damage
      tier3: 15 damage
    - effect: This ability deals your primordial [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) and ignores [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity).
      name: Effect
feature_type: ability
file_basename: deluge
file_dpath: feature/ability/fury/level-9
flavor: You summon your [primordial storm](scc.v1:mcdm.heroes.v1/feature.fury.stormwight-kits/primordial-storm).
item_id: deluge
item_name: Deluge
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Deluge
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-9/deluge
source: mcdm.heroes.v1
subclass: stormwight
target: Each enemy in the area
tier1: 7 damage
tier2: 10 damage
tier3: 15 damage
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 7 damage
      tier2: 10 damage
      tier3: 15 damage
    - effect: This ability deals your primordial [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) and ignores [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity).
      name: Effect
feature_type: ability
flavor: You summon your [primordial storm](scc.v1:mcdm.heroes.v1/feature.fury.stormwight-kits/primordial-storm).
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 11 Ferocity
    distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 7 damage
          tier2: 10 damage
          tier3: 15 damage
        - effect: This ability deals your primordial [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) and ignores [damage immunity](scc.v1:mcdm.heroes.v1/rule.damage/damage-immunity).
          name: Effect
    flavor: You summon your [primordial storm](scc.v1:mcdm.heroes.v1/feature.fury.stormwight-kits/primordial-storm).
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "9"
    name: Deluge
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/deluge
    subclass: stormwight
    target: Each enemy in the area
    tier1: 7 damage
    tier2: 10 damage
    tier3: 15 damage
    type: ability
name: Deluge
target: Each enemy in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
