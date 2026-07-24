---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 5 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 + M holy damage
      tier2: 3 + M holy damage
      tier3: 5 + M holy damage
    - effect: When a target who is not a leader or solo creature is made [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) by this ability, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
      name: Effect
flavor: Judged and [sentenced](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-2/sentenced).
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Censored
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/censored
target: One creature
tier1: 2 + M holy damage
tier2: 3 + M holy damage
tier3: 5 + M holy damage
type: ability
---


*Judged and [sentenced](scc.v1:mcdm.heroes.v1/feature.ability.censor.level-2/sentenced).*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon**  |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**             |           **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 + M holy damage
- **12-16:** 3 + M holy damage
- **17+:** 5 + M holy damage

**Effect:** When a target who is not a leader or solo creature is made [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) by this ability, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
