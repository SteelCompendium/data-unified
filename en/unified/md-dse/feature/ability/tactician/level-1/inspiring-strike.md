---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: tactician
cost: 3 Focus
cost_amount: "3"
cost_resource: Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
      tier2: 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
      tier3: 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the next [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) you make during the encounter
feature_type: ability
file_basename: inspiring-strike
file_dpath: feature/ability/tactician/level-1
flavor: Your attack gives an ally hope.
item_id: inspiring-strike
item_name: Inspiring Strike
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Inspiring Strike
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-1/inspiring-strike
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
tier2: 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
tier3: 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the next [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) you make during the encounter
type: ability
---

```ds-feature
cost: 3 Focus
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
      tier2: 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
      tier3: 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the next [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) you make during the encounter
feature_type: ability
flavor: Your attack gives an ally hope.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: tactician
    cost: 3 Focus
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
          tier2: 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
          tier3: 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the next [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) you make during the encounter
    flavor: Your attack gives an ally hope.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Inspiring Strike
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-1/inspiring-strike
    target: One creature or object
    tier1: 3 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
    tier2: 5 + M damage; you or one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries)
    tier3: 8 + M damage; you and one ally within 10 squares of you can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), and each of you gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on the next [ability roll](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) you make during the encounter
    type: ability
name: Inspiring Strike
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
