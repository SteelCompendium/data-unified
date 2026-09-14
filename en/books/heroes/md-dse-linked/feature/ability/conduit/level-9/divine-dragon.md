---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You conjure a [size](../../../../rule/character/size.md) 4 dragon that appears in an unoccupied space within [distance](../../../../rule/combat/distance.md). The dragon has [speed](../../../../rule/character/speed.md) 6 and can [fly](../../../../movement/fly.md), [stability](../../../../rule/character/stability.md) 4, 100 [Stamina](../../../../rule/health/stamina.md), immunity all to fire damage, and uses your [characteristics](../../../../rule/character/characteristic.md). The dragon disappears at the end of the encounter, if their [Stamina](../../../../rule/health/stamina.md) drops to 0, or if you are [dying](../../../../rule/health/dying.md).
      name: Effect
    - effect: On subsequent [turns](../../../../rule/combat/turn.md), you can use a main action to command the dragon to breathe magic fire in a 3 [cube](../../../../rule/combat/cube.md) within 1 square of them. Make the following [power roll](../../../../rule/dice/power-roll.md) targeting each enemy in the area.
      roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 5 fire damage
      tier2: 9 fire damage
      tier3: 12 fire damage
    - effect: Additionally, you can use a maneuver to move the dragon up to their [speed](../../../../rule/character/speed.md), or to make a [melee](../../../../rule/combat/melee.md) weapon [strike](../../../../rule/combat/strike.md) with their claw against an [adjacent](../../../../rule/combat/adjacent.md) creature or object. The dragon can also make this [strike](../../../../rule/combat/strike.md) as a [free strike](../../../common/main-actions/free-strike.md).
      roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 3 + I damage
      tier2: 5 + I damage
      tier3: 8 + I damage
feature_type: ability
file_basename: divine-dragon
file_dpath: feature/ability/conduit/level-9
flavor: From nothing but divine will, you create a powerful ally.
item_id: divine-dragon
item_name: Divine Dragon
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "9"
name: Divine Dragon
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/divine-dragon
source: mcdm.heroes.v1
subclass: creation
target: Special
tier1: 5 fire damage
tier2: 9 fire damage
tier3: 12 fire damage
type: ability
---

```ds-feature
cost: 11 Piety
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: You conjure a [size](../../../../rule/character/size.md) 4 dragon that appears in an unoccupied space within [distance](../../../../rule/combat/distance.md). The dragon has [speed](../../../../rule/character/speed.md) 6 and can [fly](../../../../movement/fly.md), [stability](../../../../rule/character/stability.md) 4, 100 [Stamina](../../../../rule/health/stamina.md), immunity all to fire damage, and uses your [characteristics](../../../../rule/character/characteristic.md). The dragon disappears at the end of the encounter, if their [Stamina](../../../../rule/health/stamina.md) drops to 0, or if you are [dying](../../../../rule/health/dying.md).
      name: Effect
    - effect: On subsequent [turns](../../../../rule/combat/turn.md), you can use a main action to command the dragon to breathe magic fire in a 3 [cube](../../../../rule/combat/cube.md) within 1 square of them. Make the following [power roll](../../../../rule/dice/power-roll.md) targeting each enemy in the area.
      roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 5 fire damage
      tier2: 9 fire damage
      tier3: 12 fire damage
    - effect: Additionally, you can use a maneuver to move the dragon up to their [speed](../../../../rule/character/speed.md), or to make a [melee](../../../../rule/combat/melee.md) weapon [strike](../../../../rule/combat/strike.md) with their claw against an [adjacent](../../../../rule/combat/adjacent.md) creature or object. The dragon can also make this [strike](../../../../rule/combat/strike.md) as a [free strike](../../../common/main-actions/free-strike.md).
      roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 3 + I damage
      tier2: 5 + I damage
      tier3: 8 + I damage
feature_type: ability
flavor: From nothing but divine will, you create a powerful ally.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: conduit
    cost: 11 Piety
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effects:
        - effect: You conjure a [size](../../../../rule/character/size.md) 4 dragon that appears in an unoccupied space within [distance](../../../../rule/combat/distance.md). The dragon has [speed](../../../../rule/character/speed.md) 6 and can [fly](../../../../movement/fly.md), [stability](../../../../rule/character/stability.md) 4, 100 [Stamina](../../../../rule/health/stamina.md), immunity all to fire damage, and uses your [characteristics](../../../../rule/character/characteristic.md). The dragon disappears at the end of the encounter, if their [Stamina](../../../../rule/health/stamina.md) drops to 0, or if you are [dying](../../../../rule/health/dying.md).
          name: Effect
        - effect: On subsequent [turns](../../../../rule/combat/turn.md), you can use a main action to command the dragon to breathe magic fire in a 3 [cube](../../../../rule/combat/cube.md) within 1 square of them. Make the following [power roll](../../../../rule/dice/power-roll.md) targeting each enemy in the area.
          roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
          tier1: 5 fire damage
          tier2: 9 fire damage
          tier3: 12 fire damage
        - effect: Additionally, you can use a maneuver to move the dragon up to their [speed](../../../../rule/character/speed.md), or to make a [melee](../../../../rule/combat/melee.md) weapon [strike](../../../../rule/combat/strike.md) with their claw against an [adjacent](../../../../rule/combat/adjacent.md) creature or object. The dragon can also make this [strike](../../../../rule/combat/strike.md) as a [free strike](../../../common/main-actions/free-strike.md).
          roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
          tier1: 3 + I damage
          tier2: 5 + I damage
          tier3: 8 + I damage
    flavor: From nothing but divine will, you create a powerful ally.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "9"
    name: Divine Dragon
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/divine-dragon
    subclass: creation
    target: Special
    tier1: 5 fire damage
    tier2: 9 fire damage
    tier3: 12 fire damage
    type: ability
name: Divine Dragon
target: Special
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
