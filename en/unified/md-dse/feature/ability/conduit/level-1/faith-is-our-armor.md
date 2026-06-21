---
action_type: Maneuver
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effect: You can target yourself instead of one ally with this ability.
feature_type: ability
file_basename: faith-is-our-armor
file_dpath: feature/ability/conduit/level-1
flavor: The heroes' armor glows with golden light, granting divine protection.
item_id: faith-is-our-armor
item_name: Faith Is Our Armor
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
level: "1"
name: Faith Is Our Armor
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/faith-is-our-armor
source: mcdm.heroes.v1
target: Four allies
tier1: The target gains 5 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
tier2: The target gains 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
tier3: The target gains 15 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
type: ability
---

```ds-feature
cost: 5 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - effect: You can target yourself instead of one ally with this ability.
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: The target gains 5 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
      tier2: The target gains 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
      tier3: The target gains 15 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
feature_type: ability
flavor: The heroes' armor glows with golden light, granting divine protection.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
metadata:
    action_type: Maneuver
    class: conduit
    cost: 5 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effect: You can target yourself instead of one ally with this ability.
    flavor: The heroes' armor glows with golden light, granting divine protection.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    level: "1"
    name: Faith Is Our Armor
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/faith-is-our-armor
    target: Four allies
    tier1: The target gains 5 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
    tier2: The target gains 10 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
    tier3: The target gains 15 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina).
    type: ability
name: Faith Is Our Armor
target: Four allies
type: feature
usage: Maneuver
```
