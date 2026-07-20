---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: "null"
cost: 5 Discipline
cost_amount: "5"
cost_resource: Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: A target who goes out of phase is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), has their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) reduced by 2, and can't obtain a tier 3 outcome on [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll).
feature_type: ability
file_basename: phase-strike
file_dpath: feature/ability/null/level-1
flavor: For a moment, your foe slips out of phase with this manifold.
item_id: phase-strike
item_name: Phase Strike
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Phase Strike
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/phase-strike
source: mcdm.heroes.v1
target: One creature
tier1: 3 + A psychic damage; I < WEAK, the target goes out of phase (save ends)
tier2: 4 + A psychic damage; I < AVERAGE, the target goes out of phase (save ends)
tier3: 6 + A psychic damage; I < STRONG, the target goes out of phase (save ends)
type: ability
---

```ds-feature
cost: 5 Discipline
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: A target who goes out of phase is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), has their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) reduced by 2, and can't obtain a tier 3 outcome on [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll).
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + A psychic damage; I < WEAK, the target goes out of phase (save ends)
      tier2: 4 + A psychic damage; I < AVERAGE, the target goes out of phase (save ends)
      tier3: 6 + A psychic damage; I < STRONG, the target goes out of phase (save ends)
feature_type: ability
flavor: For a moment, your foe slips out of phase with this manifold.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: "null"
    cost: 5 Discipline
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: A target who goes out of phase is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed), has their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability) reduced by 2, and can't obtain a tier 3 outcome on [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll).
    flavor: For a moment, your foe slips out of phase with this manifold.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Phase Strike
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/phase-strike
    target: One creature
    tier1: 3 + A psychic damage; I < WEAK, the target goes out of phase (save ends)
    tier2: 4 + A psychic damage; I < AVERAGE, the target goes out of phase (save ends)
    tier3: 6 + A psychic damage; I < STRONG, the target goes out of phase (save ends)
    type: ability
name: Phase Strike
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
