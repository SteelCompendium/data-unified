---
action_type: Main action
class: talent
cost: 5 Clarity
cost_amount: "5"
cost_resource: Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
feature_type: ability
file_basename: overwhelm
file_dpath: feature/ability/talent/level-2
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
item_id: overwhelm
item_name: Overwhelm
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
level: "2"
name: Overwhelm
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-2/overwhelm
source: mcdm.heroes.v1
subclass: telepathy
target: One creature
tier1: 6 + R psychic damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 10 + R psychic damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
tier3: 14 + R psychic damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
cost: 5 Clarity
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 6 + R psychic damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 10 + R psychic damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
      tier3: 14 + R psychic damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
keywords:
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Telepathy
metadata:
    action_type: Main action
    class: talent
    cost: 5 Clarity
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    flavor: You overload their senses, turning all their subconscious thoughts into conscious ones.
    keywords:
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Telepathy
    level: "2"
    name: Overwhelm
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-2/overwhelm
    subclass: telepathy
    target: One creature
    tier1: 6 + R psychic damage; I < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 10 + R psychic damage; I < AVERAGE, [weakened](../../../../condition/weakened.md) (save ends)
    tier3: 14 + R psychic damage; I < STRONG, [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Overwhelm
target: One creature
type: feature
usage: Main action
```
