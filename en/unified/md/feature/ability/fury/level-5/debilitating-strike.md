---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 10 + M damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 14 + M damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 20 + M damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    - effect: While [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, the target takes 1 damage for every square they move, including from [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement).
      name: Effect
flavor: You need just one blow to sabotage your target.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: Debilitating Strike
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/debilitating-strike
target: One creature
tier1: 10 + M damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 14 + M damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 20 + M damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---


*You need just one blow to sabotage your target.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 10 + M damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 14 + M damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **17+:** 20 + M damage; M < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)

**Effect:** While [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, the target takes 1 damage for every square they move, including from [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement).
