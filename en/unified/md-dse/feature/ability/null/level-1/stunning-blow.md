---
action_type: Main action
class: "null"
cost: 3 Discipline
cost_amount: "3"
cost_resource: Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: stunning-blow
file_dpath: feature/ability/null/level-1
flavor: You focus your psionic technique into a concussive punch.
item_id: stunning-blow
item_name: Stunning Blow
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Stunning Blow
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/stunning-blow
source: mcdm.heroes.v1
target: One creature or object
tier1: 4 + A damage; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 5 + A damage; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 7 + A damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---

```ds-feature
cost: 3 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 5 + A damage; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 7 + A damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: You focus your psionic technique into a concussive punch.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    cost: 3 Discipline
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: You focus your psionic technique into a concussive punch.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Stunning Blow
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/stunning-blow
    target: One creature or object
    tier1: 4 + A damage; I < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 5 + A damage; I < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 7 + A damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: Stunning Blow
target: One creature or object
type: feature
usage: Main action
```
