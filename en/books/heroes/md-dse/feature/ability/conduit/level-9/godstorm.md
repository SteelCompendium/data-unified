---
action_type: Main action
class: conduit
cost: 11 Piety
cost_amount: "11"
cost_resource: Piety
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 5
effect: A raging storm fills the area until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). At the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can move the storm up to 5 squares (no action required). On subsequent [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) while the storm is active, you can use a maneuver to make its [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: godstorm
file_dpath: feature/ability/conduit/level-9
flavor: You summon a divine storm that remains under your control.
item_id: godstorm
item_name: Godstorm
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "9"
name: Godstorm
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-9/godstorm
source: mcdm.heroes.v1
target: Each enemy in the area
tier1: 2 lightning damage, 2 sonic damage
tier2: 3 lightning damage, 3 sonic damage
tier3: 5 lightning damage, 5 sonic damage
type: ability
---

```ds-feature
cost: 11 Piety
distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 5
effects:
    - effect: A raging storm fills the area until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). At the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can move the storm up to 5 squares (no action required). On subsequent [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) while the storm is active, you can use a maneuver to make its [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 2 lightning damage, 2 sonic damage
      tier2: 3 lightning damage, 3 sonic damage
      tier3: 5 lightning damage, 5 sonic damage
feature_type: ability
flavor: You summon a divine storm that remains under your control.
keywords:
    - Area
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Main action
    class: conduit
    cost: 11 Piety
    distance: 5 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 5
    effect: A raging storm fills the area until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). At the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can move the storm up to 5 squares (no action required). On subsequent [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) while the storm is active, you can use a maneuver to make its [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: You summon a divine storm that remains under your control.
    keywords:
        - Area
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "9"
    name: Godstorm
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-9/godstorm
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
