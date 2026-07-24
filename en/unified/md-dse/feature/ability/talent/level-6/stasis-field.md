---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 9 Clarity
cost_amount: "9"
cost_resource: Clarity
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: The area is frozen in time until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each object in the area is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) remain undestroyed.
      name: Effect
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the effect ends
      tier2: P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 until the effect ends
      tier3: P < STRONG, the target is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the effect ends
    - effect: Any creature or object [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) in the area takes 2 corruption damage for each square of the area they enter. Creatures and objects [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) in the area can be [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement). You are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the effect ends.
      name: Strained
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
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "6"
name: Stasis Field
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.talent.level-6/stasis-field
source: mcdm.heroes.v1
subclass: chronopathy
target: Each creature and object in the area
tier1: P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the effect ends
tier2: P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 until the effect ends
tier3: P < STRONG, the target is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the effect ends
type: ability
---

```ds-feature
cost: 9 Clarity
distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
effects:
    - effect: The area is frozen in time until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each object in the area is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) remain undestroyed.
      name: Effect
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the effect ends
      tier2: P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 until the effect ends
      tier3: P < STRONG, the target is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the effect ends
    - effect: Any creature or object [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) in the area takes 2 corruption damage for each square of the area they enter. Creatures and objects [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) in the area can be [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement). You are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the effect ends.
      name: Strained
feature_type: ability
flavor: Keep everything as it was. Ignore everything that will be.
keywords:
    - Area
    - Chronopathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    cost: 9 Clarity
    distance: 4 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10
    effects:
        - effect: The area is frozen in time until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each object in the area is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) and can't fall until the effect ends. Until the effect ends, creatures in the area who are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) or would die stay alive, and objects in the area that are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) remain undestroyed.
          name: Effect
        - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
          tier1: P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the effect ends
          tier2: P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 until the effect ends
          tier3: P < STRONG, the target is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the effect ends
        - effect: Any creature or object [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) in the area takes 2 corruption damage for each square of the area they enter. Creatures and objects [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) in the area can be [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement). You are [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the effect ends.
          name: Strained
    flavor: Keep everything as it was. Ignore everything that will be.
    keywords:
        - Area
        - Chronopathy
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "6"
    name: Stasis Field
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-6/stasis-field
    subclass: chronopathy
    target: Each creature and object in the area
    tier1: P < WEAK, the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) until the effect ends
    tier2: P < AVERAGE, the target's [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) is 0 until the effect ends
    tier3: P < STRONG, the target is [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) until the effect ends
    type: ability
name: Stasis Field
target: Each creature and object in the area
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
