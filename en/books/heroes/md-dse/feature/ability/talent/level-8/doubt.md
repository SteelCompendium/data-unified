---
action_type: Main action
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: 'This ability gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against a target with a soul (see *Draw Steel: Monsters*). After you make the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), you or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) have a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) you make before the end of the encounter.'
feature_type: ability
file_basename: doubt
file_dpath: feature/ability/talent/level-8
flavor: You tug at the strings of the foe's anima and unravel them, allowing someone else to take advantage of their drive.
item_id: doubt
item_name: Doubt
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
level: "8"
name: Doubt
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.talent.level-8/doubt
source: mcdm.heroes.v1
target: One creature or object
tier1: 10 + P damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 14 + P damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 20 + P damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---

```ds-feature
cost: 11 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: 'This ability gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against a target with a soul (see *Draw Steel: Monsters*). After you make the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), you or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) have a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) you make before the end of the encounter.'
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 10 + P damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 14 + P damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 20 + P damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: You tug at the strings of the foe's anima and unravel them, allowing someone else to take advantage of their drive.
keywords:
    - Animapathy
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
metadata:
    action_type: Main action
    class: talent
    cost: 11 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: 'This ability gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) against a target with a soul (see *Draw Steel: Monsters*). After you make the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), you or one ally within [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance) have a double [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) you make before the end of the encounter.'
    flavor: You tug at the strings of the foe's anima and unravel them, allowing someone else to take advantage of their drive.
    keywords:
        - Animapathy
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Strike
    level: "8"
    name: Doubt
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-8/doubt
    target: One creature or object
    tier1: 10 + P damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier2: 14 + P damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 20 + P damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: Doubt
target: One creature or object
type: feature
usage: Main action
```
