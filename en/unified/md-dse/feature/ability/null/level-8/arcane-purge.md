---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 11 Discipline
cost_amount: "11"
cost_resource: Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 13 + A damage; M < WEAK, the target is suppressed (save ends)
      tier2: 19 + A damage; M < AVERAGE, the target is suppressed (save ends)
      tier3: 24 + A damage; M < STRONG, the target is suppressed (save ends)
    - effect: While suppressed, a target takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score at the start of their [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), whenever they use a [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) ability, or whenever they use an ability that costs Malice.
      name: Effect
feature_type: ability
file_basename: arcane-purge
file_dpath: feature/ability/null/level-8
flavor: You focus your [null field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) into a pressure point strike that prevents your foe from channeling sorcery.
item_id: arcane-purge
item_name: Arcane Purge
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Arcane Purge
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-8/arcane-purge
source: mcdm.heroes.v1
target: One creature
tier1: 13 + A damage; M < WEAK, the target is suppressed (save ends)
tier2: 19 + A damage; M < AVERAGE, the target is suppressed (save ends)
tier3: 24 + A damage; M < STRONG, the target is suppressed (save ends)
type: ability
---

```ds-feature
cost: 11 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 13 + A damage; M < WEAK, the target is suppressed (save ends)
      tier2: 19 + A damage; M < AVERAGE, the target is suppressed (save ends)
      tier3: 24 + A damage; M < STRONG, the target is suppressed (save ends)
    - effect: While suppressed, a target takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score at the start of their [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), whenever they use a [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) ability, or whenever they use an ability that costs Malice.
      name: Effect
feature_type: ability
flavor: You focus your [null field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) into a pressure point strike that prevents your foe from channeling sorcery.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: "null"
    cost: 11 Discipline
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 13 + A damage; M < WEAK, the target is suppressed (save ends)
          tier2: 19 + A damage; M < AVERAGE, the target is suppressed (save ends)
          tier3: 24 + A damage; M < STRONG, the target is suppressed (save ends)
        - effect: While suppressed, a target takes psychic damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score at the start of their [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn), whenever they use a [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) ability, or whenever they use an ability that costs Malice.
          name: Effect
    flavor: You focus your [null field](scc.v1:mcdm.heroes.v1/feature.null.level-1/null-field) into a pressure point strike that prevents your foe from channeling sorcery.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "8"
    name: Arcane Purge
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-8/arcane-purge
    target: One creature
    tier1: 13 + A damage; M < WEAK, the target is suppressed (save ends)
    tier2: 19 + A damage; M < AVERAGE, the target is suppressed (save ends)
    tier3: 24 + A damage; M < STRONG, the target is suppressed (save ends)
    type: ability
name: Arcane Purge
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
