---
action_type: Main action
class: talent
cost: 11 Clarity
cost_amount: "11"
cost_resource: Clarity
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effect: You and each target ally can't obtain lower than a tier 2 outcome on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each target enemy is affected by the ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: synaptic-terror
file_dpath: feature/ability/talent/level-9
flavor: You project a terrifying image into the brains of your foes, and their fear psionically invigorates your allies.
item_id: synaptic-terror
item_name: Synaptic Terror
keywords:
    - Area
    - Psionic
    - Telepathy
level: "9"
name: Synaptic Terror
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-9/synaptic-terror
source: mcdm.heroes.v1
target: Each ally and enemy in the area
tier1: R < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: R < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: R < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 11 Clarity
distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - effect: You and each target ally can't obtain lower than a tier 2 outcome on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each target enemy is affected by the ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: R < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: R < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: R < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
feature_type: ability
flavor: You project a terrifying image into the brains of your foes, and their fear psionically invigorates your allies.
keywords:
    - Area
    - Psionic
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 11 Clarity
    distance: 3 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
    effect: You and each target ally can't obtain lower than a tier 2 outcome on [power rolls](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn). Each target enemy is affected by the ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: You project a terrifying image into the brains of your foes, and their fear psionically invigorates your allies.
    keywords:
        - Area
        - Psionic
        - Telepathy
    level: "9"
    name: Synaptic Terror
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-9/synaptic-terror
    target: Each ally and enemy in the area
    tier1: R < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: R < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: R < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: Synaptic Terror
target: Each ally and enemy in the area
type: feature
usage: Main action
```
