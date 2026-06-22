---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: overwhelm
file_dpath: feature/ability/talent/level-2
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
item_id: overwhelm
item_name: Overwhelm
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
level: "2"
name: Overwhelm
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/overwhelm
source: mcdm.heroes.v1
subclass: telepathy
target: One creature
tier1: 6 + R psychic damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 10 + R psychic damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 14 + R psychic damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 6 + R psychic damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 10 + R psychic damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 14 + R psychic damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
feature_type: ability
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
    keywords:
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Telepathy
    level: "2"
    name: Overwhelm
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/overwhelm
    subclass: telepathy
    target: One creature
    tier1: 6 + R psychic damage; I < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 10 + R psychic damage; I < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    tier3: 14 + R psychic damage; I < STRONG, [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    type: ability
name: Overwhelm
target: One creature
type: feature
usage: Main action
```
