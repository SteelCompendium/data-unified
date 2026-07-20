---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: You control the target's movement. The target can't be moved in a way that would harm them (such as over a cliff), leave them [dying](../../../../rule/health/dying.md), or result in them suffering a [condition](../../../../rule/combat/condition.md) or other negative effect. However, you can move them to provoke [opportunity attacks](../../../../rule/combat/opportunity-attack.md).
feature_type: ability
file_basename: synaptic-override
file_dpath: feature/ability/talent/level-2
flavor: You control an enemy's nervous system. How pleasant for them.
item_id: synaptic-override
item_name: Synaptic Override
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Telepathy
level: "2"
name: Synaptic Override
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/synaptic-override
source: mcdm.heroes.v1
subclass: telepathy
target: One enemy
tier1: The target makes a [free strike](../../../common/main-actions/free-strike.md) against one enemy of your choice.
tier2: The target shifts up to their [speed](../../../../rule/character/speed.md) and uses their [signature ability](../../../../rule/combat/signature-ability.md) against any enemies of your choice.
tier3: The target moves up to their [speed](../../../../rule/character/speed.md) and uses their [signature ability](../../../../rule/combat/signature-ability.md) against any enemies of your choice.
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You control the target's movement. The target can't be moved in a way that would harm them (such as over a cliff), leave them [dying](../../../../rule/health/dying.md), or result in them suffering a [condition](../../../../rule/combat/condition.md) or other negative effect. However, you can move them to provoke [opportunity attacks](../../../../rule/combat/opportunity-attack.md).
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: The target makes a [free strike](../../../common/main-actions/free-strike.md) against one enemy of your choice.
      tier2: The target shifts up to their [speed](../../../../rule/character/speed.md) and uses their [signature ability](../../../../rule/combat/signature-ability.md) against any enemies of your choice.
      tier3: The target moves up to their [speed](../../../../rule/character/speed.md) and uses their [signature ability](../../../../rule/combat/signature-ability.md) against any enemies of your choice.
feature_type: ability
flavor: You control an enemy's nervous system. How pleasant for them.
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Telepathy
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: You control the target's movement. The target can't be moved in a way that would harm them (such as over a cliff), leave them [dying](../../../../rule/health/dying.md), or result in them suffering a [condition](../../../../rule/combat/condition.md) or other negative effect. However, you can move them to provoke [opportunity attacks](../../../../rule/combat/opportunity-attack.md).
    flavor: You control an enemy's nervous system. How pleasant for them.
    keywords:
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Telepathy
    level: "2"
    name: Synaptic Override
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/synaptic-override
    subclass: telepathy
    target: One enemy
    tier1: The target makes a [free strike](../../../common/main-actions/free-strike.md) against one enemy of your choice.
    tier2: The target shifts up to their [speed](../../../../rule/character/speed.md) and uses their [signature ability](../../../../rule/combat/signature-ability.md) against any enemies of your choice.
    tier3: The target moves up to their [speed](../../../../rule/character/speed.md) and uses their [signature ability](../../../../rule/combat/signature-ability.md) against any enemies of your choice.
    type: ability
name: Synaptic Override
target: One enemy
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
