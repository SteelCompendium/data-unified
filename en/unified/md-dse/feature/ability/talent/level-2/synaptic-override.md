---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You control the target's movement. The target can't be moved in a way that would harm them (such as over a cliff), leave them [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or result in them suffering a [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) or other negative effect. However, you can move them to provoke [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack).
feature_type: ability
file_basename: synaptic-override
file_dpath: feature/ability/talent/level-2
flavor: You control an enemy's nervous system. How pleasant for them.
item_id: synaptic-override
item_name: Synaptic Override
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telepathy
level: "2"
name: Synaptic Override
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/synaptic-override
source: mcdm.heroes.v1
target: One enemy
tier1: The target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against one enemy of your choice.
tier2: The target shifts up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against any enemies of your choice.
tier3: The target moves up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against any enemies of your choice.
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You control the target's movement. The target can't be moved in a way that would harm them (such as over a cliff), leave them [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or result in them suffering a [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) or other negative effect. However, you can move them to provoke [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack).
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: The target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against one enemy of your choice.
      tier2: The target shifts up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against any enemies of your choice.
      tier3: The target moves up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against any enemies of your choice.
feature_type: ability
flavor: You control an enemy's nervous system. How pleasant for them.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You control the target's movement. The target can't be moved in a way that would harm them (such as over a cliff), leave them [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), or result in them suffering a [condition](scc.v1:mcdm.heroes.v1/rule.combat/condition) or other negative effect. However, you can move them to provoke [opportunity attacks](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack).
    flavor: You control an enemy's nervous system. How pleasant for them.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Telepathy
    level: "2"
    name: Synaptic Override
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/synaptic-override
    target: One enemy
    tier1: The target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against one enemy of your choice.
    tier2: The target shifts up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against any enemies of your choice.
    tier3: The target moves up to their [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and uses their [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against any enemies of your choice.
    type: ability
name: Synaptic Override
target: One enemy
type: feature
usage: Main action
```
