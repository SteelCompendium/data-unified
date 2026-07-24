---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: Self; see below
effects:
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). Each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this movement takes damage equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score. Then make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting). You gain 1 ferocity for each target who dies as a result of this ability (maximum 11 ferocity).
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 8 dies.
      tier2: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 11 dies.
      tier3: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 17 dies.
feature_type: ability
file_basename: relentless-death
file_dpath: feature/ability/fury/level-8
flavor: You won't escape your fate.
item_id: relentless-death
item_name: Relentless Death
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Relentless Death
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-8/relentless-death
source: mcdm.heroes.v1
target: Self
tier1: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 8 dies.
tier2: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 11 dies.
tier3: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 17 dies.
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: Self; see below
effects:
    - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). Each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this movement takes damage equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score. Then make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting). You gain 1 ferocity for each target who dies as a result of this ability (maximum 11 ferocity).
      name: Effect
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 8 dies.
      tier2: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 11 dies.
      tier3: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 17 dies.
feature_type: ability
flavor: You won't escape your fate.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 11 Ferocity
    distance: Self; see below
    effects:
        - effect: You [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed). Each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this movement takes damage equal to twice your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score. Then make one [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) that targets each enemy you move [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during this [shift](scc.v1:mcdm.heroes.v1/movement/shifting). You gain 1 ferocity for each target who dies as a result of this ability (maximum 11 ferocity).
          name: Effect
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 8 dies.
          tier2: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 11 dies.
          tier3: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 17 dies.
    flavor: You won't escape your fate.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: Relentless Death
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-8/relentless-death
    target: Self
    tier1: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 8 dies.
    tier2: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 11 dies.
    tier3: Any target whose [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) is equal to or less than 17 dies.
    type: ability
name: Relentless Death
target: Self
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
