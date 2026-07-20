---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: 4 [cube](../../../../rule/combat/cube.md) within 10
effect: The area is frozen in time until the start of your next [turn](../../../../rule/combat/turn.md). Each object in the area is [restrained](../../../../condition/restrained.md) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](../../../../rule/health/stamina.md) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](../../../../rule/health/stamina.md) remain undestroyed.
feature_type: ability
file_basename: stasis-field
file_dpath: feature/ability/talent/level-6
flavor: Keep everything as it was. Ignore everything that will be.
item_id: stasis-field
item_name: Stasis Field
keywords:
    - Area
    - Chronopathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "6"
name: Stasis Field
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-6/stasis-field
source: mcdm.heroes.v1
subclass: chronopathy
target: Each creature and object in the area
tier1: P < WEAK, the target is [slowed](../../../../condition/slowed.md) until the effect ends
tier2: P < AVERAGE, the target's [speed](../../../../rule/character/speed.md) is 0 until the effect ends
tier3: P < STRONG, the target is [restrained](../../../../condition/restrained.md) until the effect ends
type: ability
---

```ds-feature
cost: 9 Clarity
distance: 4 [cube](../../../../rule/combat/cube.md) within 10
effects:
    - effect: The area is frozen in time until the start of your next [turn](../../../../rule/combat/turn.md). Each object in the area is [restrained](../../../../condition/restrained.md) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](../../../../rule/health/stamina.md) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](../../../../rule/health/stamina.md) remain undestroyed.
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: P < WEAK, the target is [slowed](../../../../condition/slowed.md) until the effect ends
      tier2: P < AVERAGE, the target's [speed](../../../../rule/character/speed.md) is 0 until the effect ends
      tier3: P < STRONG, the target is [restrained](../../../../condition/restrained.md) until the effect ends
feature_type: ability
flavor: Keep everything as it was. Ignore everything that will be.
keywords:
    - Area
    - Chronopathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    cost: 9 Clarity
    distance: 4 [cube](../../../../rule/combat/cube.md) within 10
    effect: The area is frozen in time until the start of your next [turn](../../../../rule/combat/turn.md). Each object in the area is [restrained](../../../../condition/restrained.md) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](../../../../rule/health/stamina.md) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](../../../../rule/health/stamina.md) remain undestroyed.
    flavor: Keep everything as it was. Ignore everything that will be.
    keywords:
        - Area
        - Chronopathy
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "6"
    name: Stasis Field
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/stasis-field
    subclass: chronopathy
    target: Each creature and object in the area
    tier1: P < WEAK, the target is [slowed](../../../../condition/slowed.md) until the effect ends
    tier2: P < AVERAGE, the target's [speed](../../../../rule/character/speed.md) is 0 until the effect ends
    tier3: P < STRONG, the target is [restrained](../../../../condition/restrained.md) until the effect ends
    type: ability
name: Stasis Field
target: Each creature and object in the area
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
