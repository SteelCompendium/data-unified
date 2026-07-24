---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 5 Insight
cost_amount: "5"
cost_resource: Insight
distance: Self; see below
effects:
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets up to three enemies who came [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you during the move.
      name: Effect
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 9 damage
feature_type: ability
file_basename: one-hundred-throats
file_dpath: feature/ability/shadow/level-1
flavor: As you move across the battlefield, every foe within reach feels your wrath.
item_id: one-hundred-throats
item_name: One Hundred Throats
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
level: "1"
name: One Hundred Throats
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
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
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets up to three enemies who came [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you during the move.
      name: Effect
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 damage
      tier2: 6 damage
      tier3: 9 damage
feature_type: ability
flavor: As you move across the battlefield, every foe within reach feels your wrath.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: shadow
    cost: 5 Insight
    distance: Self; see below
    effects:
        - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) and make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets up to three enemies who came [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you during the move.
          name: Effect
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 3 damage
          tier2: 6 damage
          tier3: 9 damage
    flavor: As you move across the battlefield, every foe within reach feels your wrath.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Weapon
    level: "1"
    name: One Hundred Throats
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/one-hundred-throats
    target: Self
    tier1: 3 damage
    tier2: 6 damage
    tier3: 9 damage
    type: ability
name: One Hundred Throats
target: Self
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
