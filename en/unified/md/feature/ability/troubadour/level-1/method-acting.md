---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 5 Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 6 + A damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier2: 10 + A damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
      tier3: 14 + A damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
    - effect: You can become [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends) to deal an extra 5 corruption damage to the target.
      name: Effect
flavor: They're so hurt by your performance, you start to believe it yourself.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Method Acting
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/method-acting
target: One creature
tier1: 6 + A damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier2: 10 + A damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
tier3: 14 + A damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
type: ability
---


*They're so hurt by your performance, you start to believe it yourself.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 6 + A damage; P < WEAK, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **12-16:** 10 + A damage; P < AVERAGE, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)
- **17+:** 14 + A damage; P < STRONG, [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) (save ends)

**Effect:** You can become [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends) to deal an extra 5 corruption damage to the target.
