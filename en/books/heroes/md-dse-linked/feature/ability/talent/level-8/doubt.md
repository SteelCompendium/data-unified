---
action_type: Main action
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: 'This ability gains an [edge](../../../../rule/dice/edge.md) against a target with a soul (see *Draw Steel: Monsters*). After you make the [power roll](../../../../rule/dice/power-roll.md), you or one ally within [distance](../../../../rule/combat/distance.md) have a double [edge](../../../../rule/dice/edge.md) on the next [power roll](../../../../rule/dice/power-roll.md) you make before the end of the encounter.'
feature_type: ability
file_basename: doubt
file_dpath: feature/ability/talent/level-8
flavor: You tug at the strings of the foe's anima and unravel them, allowing someone else to take advantage of their drive.
item_id: doubt
item_name: Doubt
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
level: "8"
name: Doubt
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-8/doubt
source: mcdm.heroes.v1
target: One creature or object
tier1: 10 + P damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
tier2: 14 + P damage; P < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 20 + P damage; P < STRONG, [weakened](../../../../condition/weakened.md) and [slowed](../../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: 'This ability gains an [edge](../../../../rule/dice/edge.md) against a target with a soul (see *Draw Steel: Monsters*). After you make the [power roll](../../../../rule/dice/power-roll.md), you or one ally within [distance](../../../../rule/combat/distance.md) have a double [edge](../../../../rule/dice/edge.md) on the next [power roll](../../../../rule/dice/power-roll.md) you make before the end of the encounter.'
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 10 + P damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
      tier2: 14 + P damage; P < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 20 + P damage; P < STRONG, [weakened](../../../../condition/weakened.md) and [slowed](../../../../condition/slowed.md) (save ends)
feature_type: ability
flavor: You tug at the strings of the foe's anima and unravel them, allowing someone else to take advantage of their drive.
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
metadata:
    action_type: Main action
    class: talent
    cost: 11 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: 'This ability gains an [edge](../../../../rule/dice/edge.md) against a target with a soul (see *Draw Steel: Monsters*). After you make the [power roll](../../../../rule/dice/power-roll.md), you or one ally within [distance](../../../../rule/combat/distance.md) have a double [edge](../../../../rule/dice/edge.md) on the next [power roll](../../../../rule/dice/power-roll.md) you make before the end of the encounter.'
    flavor: You tug at the strings of the foe's anima and unravel them, allowing someone else to take advantage of their drive.
    keywords:
        - Animapathy
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Strike
    level: "8"
    name: Doubt
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-8/doubt
    target: One creature or object
    tier1: 10 + P damage; P < WEAK, [weakened](../../../../condition/weakened.md) (save ends)
    tier2: 14 + P damage; P < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 20 + P damage; P < STRONG, [weakened](../../../../condition/weakened.md) and [slowed](../../../../condition/slowed.md) (save ends)
    type: ability
name: Doubt
target: One creature or object
type: feature
usage: Main action
```
