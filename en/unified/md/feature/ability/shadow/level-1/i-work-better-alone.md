---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + A damage
      tier2: 6 + A damage
      tier3: 9 + A damage
    - effect: If the target has none of your allies [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
flavor: '"It''s better, just you and me. Isn''t it?"'
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: I Work Better Alone
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/i-work-better-alone
subtype: signature
target: One creature
tier1: 3 + A damage
tier2: 6 + A damage
tier3: 9 + A damage
type: ability
---


*"It's better, just you and me. Isn't it?"*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-----------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5**        | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + A damage
- **12-16:** 6 + A damage
- **17+:** 9 + A damage

**Effect:** If the target has none of your allies [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
