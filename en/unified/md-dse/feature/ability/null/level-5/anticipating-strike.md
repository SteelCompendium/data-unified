---
action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
class: "null"
cost: 9 Discipline
cost_amount: "9"
cost_resource: Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 7 + A damage; I < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 10 + A damage; I < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 13 + A damage; I < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    - effect: This [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) resolves before the triggering movement or main action.
      name: Effect
feature_type: ability
file_basename: anticipating-strike
file_dpath: feature/ability/null/level-5
flavor: You suddenly strike an enemy, then grab them in a psionically enhanced grip.
item_id: anticipating-strike
item_name: Anticipating Strike
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: Anticipating Strike
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-5/anticipating-strike
source: mcdm.heroes.v1
subtype: triggered
target: One creature
tier1: 7 + A damage; I < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier2: 10 + A damage; I < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
tier3: 13 + A damage; I < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
trigger: The target moves or uses a main action.
type: ability
---

```ds-feature
cost: 9 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 7 + A damage; I < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier2: 10 + A damage; I < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
      tier3: 13 + A damage; I < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    - effect: This [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) resolves before the triggering movement or main action.
      name: Effect
feature_type: ability
flavor: You suddenly strike an enemy, then grab them in a psionically enhanced grip.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
    class: "null"
    cost: 9 Discipline
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 7 + A damage; I < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier2: 10 + A damage; I < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
          tier3: 13 + A damage; I < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
        - effect: This [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) resolves before the triggering movement or main action.
          name: Effect
    flavor: You suddenly strike an enemy, then grab them in a psionically enhanced grip.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "5"
    name: Anticipating Strike
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-5/anticipating-strike
    subtype: triggered
    target: One creature
    tier1: 7 + A damage; I < WEAK, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier2: 10 + A damage; I < AVERAGE, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    tier3: 13 + A damage; I < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    trigger: The target moves or uses a main action.
    type: ability
name: Anticipating Strike
target: One creature
trigger: The target moves or uses a main action.
type: feature
usage: Free [triggered](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action)
```
