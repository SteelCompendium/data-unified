---
action_type: Main action
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: Self; see below
effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md) and make one [power roll](../../../../rule/dice/power-roll.md) that targets up to three enemies who came [adjacent](../../../../rule/combat/adjacent.md) to you during the move.
feature_type: ability
file_basename: one-hundred-throats
file_dpath: feature/ability/shadow/level-1
flavor: As you move across the battlefield, every foe within reach feels your wrath.
item_id: one-hundred-throats
item_name: One Hundred Throats
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
level: "1"
name: One Hundred Throats
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/one-hundred-throats
source: mcdm.heroes.v1
target: Self
tier1: 3 damage
tier2: 6 damage
tier3: 9 damage
type: ability
---

```ds-feature
cost: 5 Insight
distance: Self; see below
effects:
    - effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md) and make one [power roll](../../../../rule/dice/power-roll.md) that targets up to three enemies who came [adjacent](../../../../rule/combat/adjacent.md) to you during the move.
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 9 damage
feature_type: ability
flavor: As you move across the battlefield, every foe within reach feels your wrath.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Weapon
metadata:
    action_type: Main action
    class: shadow
    cost: 5 Insight
    distance: Self; see below
    effect: You [shift](../../../../movement/shifting.md) up to your [speed](../../../../rule/character/speed.md) and make one [power roll](../../../../rule/dice/power-roll.md) that targets up to three enemies who came [adjacent](../../../../rule/combat/adjacent.md) to you during the move.
    flavor: As you move across the battlefield, every foe within reach feels your wrath.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - Weapon
    level: "1"
    name: One Hundred Throats
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/one-hundred-throats
    target: Self
    tier1: 3 damage
    tier2: 6 damage
    tier3: 9 damage
    type: ability
name: One Hundred Throats
target: Self
type: feature
usage: Main action
```
