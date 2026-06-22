---
action_type: Main action
class: conduit
cost: 9 Piety
cost_amount: "9"
cost_resource: Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: If this damage kills the target, you and each ally within [distance](../../../../rule/combat/distance.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
feature_type: ability
file_basename: your-story-ends-here
file_dpath: feature/ability/conduit/level-6
flavor: You bend the fate of a foe, willing them to die.
item_id: your-story-ends-here
item_name: Your Story Ends Here
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
level: "6"
name: Your Story Ends Here
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-6/your-story-ends-here
source: mcdm.heroes.v1
subclass: fate
target: One creature
tier1: 9 + I corruption damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 14 + I corruption damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 19 + I corruption damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
type: ability
---

```ds-feature
cost: 9 Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: If this damage kills the target, you and each ally within [distance](../../../../rule/combat/distance.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 9 + I corruption damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 14 + I corruption damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 19 + I corruption damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
feature_type: ability
flavor: You bend the fate of a foe, willing them to die.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
metadata:
    action_type: Main action
    class: conduit
    cost: 9 Piety
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: If this damage kills the target, you and each ally within [distance](../../../../rule/combat/distance.md) can spend a [Recovery](../../../../rule/health/recoveries.md).
    flavor: You bend the fate of a foe, willing them to die.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
    level: "6"
    name: Your Story Ends Here
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-6/your-story-ends-here
    subclass: fate
    target: One creature
    tier1: 9 + I corruption damage; R < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 14 + I corruption damage; R < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 19 + I corruption damage; R < STRONG, [weakened](../../../../condition/weakened.md) (save ends)
    type: ability
name: Your Story Ends Here
target: One creature
type: feature
usage: Main action
```
