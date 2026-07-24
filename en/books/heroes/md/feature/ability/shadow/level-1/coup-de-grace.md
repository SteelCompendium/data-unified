---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
cost: 5 Insight
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 2d6 + 7 + A damage
      tier2: 2d6 + 11 + A damage
      tier3: 2d6 + 16 + A damage
flavor: Your blade might be the last thing they see.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Coup de Grace
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/coup-de-grace
target: One creature
tier1: 2d6 + 7 + A damage
tier2: 2d6 + 11 + A damage
tier3: 2d6 + 16 + A damage
type: ability
---


*Your blade might be the last thing they see.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-----------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5**        | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 2d6 + 7 + A damage
- **12-16:** 2d6 + 11 + A damage
- **17+:** 2d6 + 16 + A damage
