---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage
      tier3: 8 + M or A damage
    - effect: The target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
flavor: You execute a brutal strike that leaves your foe reeling. (Previously known as "[Shock and Awe](scc.v1:mcdm.heroes.v1/feature.tactician.level-7/shock-and-awe)")
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: raider
name: Raider's Awe
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.raider/raiders-awe
subtype: signature
target: One creature
tier1: 3 + M or A damage
tier2: 6 + M or A damage
tier3: 8 + M or A damage
type: ability
---

*You execute a brutal strike that leaves your foe reeling. (Previously known as "[Shock and Awe](scc.v1:mcdm.heroes.v1/feature.tactician.level-7/shock-and-awe)")*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **Main action** |
|-----------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**       | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + M or A damage
- **12-16:** 6 + M or A damage
- **17+:** 8 + M or A damage

**Effect:** The target takes a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) made before the end of their next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
