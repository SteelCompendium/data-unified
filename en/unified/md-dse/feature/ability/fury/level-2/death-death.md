---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
feature_type: ability
file_basename: death-death
file_dpath: feature/ability/fury/level-2
flavor: Your unbridled rage strikes terror in their hearts.
item_id: death-death
item_name: Death... Death!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: Death... Death!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-2/death-death
source: mcdm.heroes.v1
target: One creature
tier1: 3 + M damage; P < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 5 + M damage; P < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 8 + M damage; P < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; P < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 5 + M damage; P < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 8 + M damage; P < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
feature_type: ability
flavor: Your unbridled rage strikes terror in their hearts.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: fury
    cost: 5 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: Your unbridled rage strikes terror in their hearts.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: Death... Death!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-2/death-death
    target: One creature
    tier1: 3 + M damage; P < WEAK, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: 5 + M damage; P < AVERAGE, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: 8 + M damage; P < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) and [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: Death... Death!
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
