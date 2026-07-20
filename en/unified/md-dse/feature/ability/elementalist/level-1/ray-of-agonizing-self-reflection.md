---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: elementalist
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: ray-of-agonizing-self-reflection
file_dpath: feature/ability/elementalist/level-1
flavor: You inflict pain and doubt in equal measure.
item_id: ray-of-agonizing-self-reflection
item_name: Ray of Agonizing Self-Reflection
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Void
level: "1"
name: Ray of Agonizing Self-Reflection
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/ray-of-agonizing-self-reflection
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + R corruption damage; R < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 4 + R corruption damage; R < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 6 + R corruption damage; R < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R corruption damage; R < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 4 + R corruption damage; R < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 6 + R corruption damage; R < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: You inflict pain and doubt in equal measure.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Void
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: elementalist
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: You inflict pain and doubt in equal measure.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Void
    level: "1"
    name: Ray of Agonizing Self-Reflection
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.elementalist.level-1/ray-of-agonizing-self-reflection
    subtype: signature
    target: One creature or object
    tier1: 2 + R corruption damage; R < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 4 + R corruption damage; R < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 6 + R corruption damage; R < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: Ray of Agonizing Self-Reflection
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
