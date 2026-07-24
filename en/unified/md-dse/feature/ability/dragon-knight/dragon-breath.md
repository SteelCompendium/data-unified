---
action_type: Main action
ancestry: dragon-knight
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 2 damage
      tier2: 4 damage
      tier3: 6 damage
    - effect: You choose the ability's [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) from acid, cold, corruption, fire, lightning, or poison.
      name: Effect
feature_type: ability
file_basename: dragon-breath
file_dpath: feature/ability/dragon-knight
flavor: A furious exhalation of energy washes over your foes.
item_id: dragon-breath
item_name: Dragon Breath
keywords:
    - Area
    - Magic
name: Dragon Breath
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.dragon-knight/dragon-breath
source: mcdm.heroes.v1
subtype: signature
target: Each enemy in the area
tier1: 2 damage
tier2: 4 damage
tier3: 6 damage
type: ability
---

```ds-feature
distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 2 damage
      tier2: 4 damage
      tier3: 6 damage
    - effect: You choose the ability's [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) from acid, cold, corruption, fire, lightning, or poison.
      name: Effect
feature_type: ability
flavor: A furious exhalation of energy washes over your foes.
keywords:
    - Area
    - Magic
metadata:
    action_type: Main action
    ancestry: dragon-knight
    distance: 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 1
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
          tier1: 2 damage
          tier2: 4 damage
          tier3: 6 damage
        - effect: You choose the ability's [damage type](scc.v1:mcdm.heroes.v1/rule.damage/damage-type) from acid, cold, corruption, fire, lightning, or poison.
          name: Effect
    flavor: A furious exhalation of energy washes over your foes.
    keywords:
        - Area
        - Magic
    name: Dragon Breath
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.dragon-knight/dragon-breath
    subtype: signature
    target: Each enemy in the area
    tier1: 2 damage
    tier2: 4 damage
    tier3: 6 damage
    type: ability
name: Dragon Breath
target: Each enemy in the area
type: feature
usage: Main action
```
