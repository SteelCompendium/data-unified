---
action_type: '[Maneuver](../../../../rule/combat/turn.md)'
class: tactician
cost: 9 Focus
cost_amount: "9"
cost_resource: Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: Each target is marked by you. Immediately and until the end of the encounter, the Director tells you if any creatures marked by you have [damage immunity](../../../../rule/damage/damage-immunity.md) or weakness and the value of that immunity or weakness. Additionally, you and each ally within 3 squares of you gains 2 [surges](../../../../rule/resource/surge.md).
      name: Effect
    - effect: Until the end of the encounter, whenever you or any ally makes a [strike](../../../../rule/combat/strike.md) against a creature marked by you, you can spend 2 focus to make the [strike](../../../../rule/combat/strike.md) ignore [damage immunity](../../../../rule/damage/damage-immunity.md) and deal extra damage equal to three times your [Reason](../../../../rule/character/reason.md) score.
      name: Mark Benefit
feature_type: ability
file_basename: battle-plan
file_dpath: feature/ability/tactician/level-6
flavor: With new understanding of your foes, you create the perfect plan to win the battle.
item_id: battle-plan
item_name: Battle Plan
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "6"
name: Battle Plan
scc: mcdm.heroes.v1/feature.ability.tactician.level-6/battle-plan
source: mcdm.heroes.v1
subclass: mastermind
target: Three creatures
type: ability
---

```ds-feature
cost: 9 Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: Each target is marked by you. Immediately and until the end of the encounter, the Director tells you if any creatures marked by you have [damage immunity](../../../../rule/damage/damage-immunity.md) or weakness and the value of that immunity or weakness. Additionally, you and each ally within 3 squares of you gains 2 [surges](../../../../rule/resource/surge.md).
      name: Effect
    - effect: Until the end of the encounter, whenever you or any ally makes a [strike](../../../../rule/combat/strike.md) against a creature marked by you, you can spend 2 focus to make the [strike](../../../../rule/combat/strike.md) ignore [damage immunity](../../../../rule/damage/damage-immunity.md) and deal extra damage equal to three times your [Reason](../../../../rule/character/reason.md) score.
      name: Mark Benefit
feature_type: ability
flavor: With new understanding of your foes, you create the perfect plan to win the battle.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Maneuver](../../../../rule/combat/turn.md)'
    class: tactician
    cost: 9 Focus
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: Each target is marked by you. Immediately and until the end of the encounter, the Director tells you if any creatures marked by you have [damage immunity](../../../../rule/damage/damage-immunity.md) or weakness and the value of that immunity or weakness. Additionally, you and each ally within 3 squares of you gains 2 [surges](../../../../rule/resource/surge.md).
          name: Effect
        - effect: Until the end of the encounter, whenever you or any ally makes a [strike](../../../../rule/combat/strike.md) against a creature marked by you, you can spend 2 focus to make the [strike](../../../../rule/combat/strike.md) ignore [damage immunity](../../../../rule/damage/damage-immunity.md) and deal extra damage equal to three times your [Reason](../../../../rule/character/reason.md) score.
          name: Mark Benefit
    flavor: With new understanding of your foes, you create the perfect plan to win the battle.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "6"
    name: Battle Plan
    scc: mcdm.heroes.v1/feature.ability.tactician.level-6/battle-plan
    subclass: mastermind
    target: Three creatures
    type: ability
name: Battle Plan
target: Three creatures
type: feature
usage: '[Maneuver](../../../../rule/combat/turn.md)'
```
