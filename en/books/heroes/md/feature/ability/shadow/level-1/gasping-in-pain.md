---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + A damage
      tier2: 5 + A damage
      tier3: 8 + A damage; I < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - effect: One ally within 5 squares of the target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
flavor: Your precise strikes let your allies take advantage of a target's agony.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Gasping in Pain
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/gasping-in-pain
subtype: signature
target: One creature
tier1: 3 + A damage
tier2: 5 + A damage
tier3: 8 + A damage; I < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---


*Your precise strikes let your allies take advantage of a target's agony.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + A damage
- **12-16:** 5 + A damage
- **17+:** 8 + A damage; I < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)

**Effect:** One ally within 5 squares of the target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
