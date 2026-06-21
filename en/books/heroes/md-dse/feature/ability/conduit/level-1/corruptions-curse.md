---
action_type: Main action
class: conduit
cost: 5 Piety
cost_amount: "5"
cost_resource: Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: corruptions-curse
file_dpath: feature/ability/conduit/level-1
flavor: Cursed by you, your enemy takes more damage from your allies.
item_id: corruptions-curse
item_name: Corruption's Curse
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Corruption's Curse
power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
scc: mcdm.heroes.v1/feature.ability.conduit.level-1/corruptions-curse
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + I corruption damage; M < WEAK, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
tier2: 6 + I corruption damage; M < AVERAGE, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
tier3: 9 + I corruption damage; M < STRONG, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
type: ability
---

```ds-feature
cost: 5 Piety
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)
      tier1: 3 + I corruption damage; M < WEAK, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
      tier2: 6 + I corruption damage; M < AVERAGE, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
      tier3: 9 + I corruption damage; M < STRONG, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
feature_type: ability
flavor: Cursed by you, your enemy takes more damage from your allies.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: Main action
    class: conduit
    cost: 5 Piety
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: Cursed by you, your enemy takes more damage from your allies.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Corruption's Curse
    power_roll_characteristic: '[Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition)'
    scc: mcdm.heroes.v1/feature.ability.conduit.level-1/corruptions-curse
    target: One creature or object
    tier1: 3 + I corruption damage; M < WEAK, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
    tier2: 6 + I corruption damage; M < AVERAGE, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
    tier3: 9 + I corruption damage; M < STRONG, [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 5 (save ends)
    type: ability
name: Corruption's Curse
target: One creature or object
type: feature
usage: Main action
```
