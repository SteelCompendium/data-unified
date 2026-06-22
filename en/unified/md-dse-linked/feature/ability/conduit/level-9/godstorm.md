---
action_type: Main action
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: 5 [cube](../../../../rule/combat/cube.md) within 5
effect: A raging storm fills the area until the end of the encounter or until you are [dying](../../../../rule/health/dying.md). At the start of each of your [turns](../../../../rule/combat/turn.md), you can move the storm up to 5 squares (no action required). On subsequent [turns](../../../../rule/combat/turn.md) while the storm is active, you can use a maneuver to make its [power roll](../../../../rule/dice/power-roll.md).
feature_type: ability
file_basename: godstorm
file_dpath: feature/ability/conduit/level-9
flavor: You summon a divine storm that remains under your control.
item_id: godstorm
item_name: Godstorm
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
level: "9"
name: Godstorm
power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/godstorm
source: mcdm.heroes.v1
subclass: storm
target: Each enemy in the area
tier1: 2 lightning damage, 2 sonic damage
tier2: 3 lightning damage, 3 sonic damage
tier3: 5 lightning damage, 5 sonic damage
type: ability
---

```ds-feature
cost: 11 Piety
distance: 5 [cube](../../../../rule/combat/cube.md) within 5
effects:
    - effect: A raging storm fills the area until the end of the encounter or until you are [dying](../../../../rule/health/dying.md). At the start of each of your [turns](../../../../rule/combat/turn.md), you can move the storm up to 5 squares (no action required). On subsequent [turns](../../../../rule/combat/turn.md) while the storm is active, you can use a maneuver to make its [power roll](../../../../rule/dice/power-roll.md).
    - roll: Power Roll + [Intuition](../../../../rule/character/intuition.md)
      tier1: 2 lightning damage, 2 sonic damage
      tier2: 3 lightning damage, 3 sonic damage
      tier3: 5 lightning damage, 5 sonic damage
feature_type: ability
flavor: You summon a divine storm that remains under your control.
keywords:
    - Area
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
metadata:
    action_type: Main action
    class: conduit
    cost: 11 Piety
    distance: 5 [cube](../../../../rule/combat/cube.md) within 5
    effect: A raging storm fills the area until the end of the encounter or until you are [dying](../../../../rule/health/dying.md). At the start of each of your [turns](../../../../rule/combat/turn.md), you can move the storm up to 5 squares (no action required). On subsequent [turns](../../../../rule/combat/turn.md) while the storm is active, you can use a maneuver to make its [power roll](../../../../rule/dice/power-roll.md).
    flavor: You summon a divine storm that remains under your control.
    keywords:
        - Area
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
    level: "9"
    name: Godstorm
    power_roll_characteristic: '[Intuition](../../../../rule/character/intuition.md)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/godstorm
    subclass: storm
    target: Each enemy in the area
    tier1: 2 lightning damage, 2 sonic damage
    tier2: 3 lightning damage, 3 sonic damage
    tier3: 5 lightning damage, 5 sonic damage
    type: ability
name: Godstorm
target: Each enemy in the area
type: feature
usage: Main action
```
