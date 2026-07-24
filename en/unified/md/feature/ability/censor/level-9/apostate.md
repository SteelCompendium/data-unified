---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 11 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 13 + M holy damage
      tier2: 19 + M holy damage
      tier3: 26 + M holy damage
    - effect: Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), the target has [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 10.
      name: Effect
flavor: You channel holy energy to seal an enemy's fate.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Apostate
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-9/apostate
subclass: paragon
target: One creature
tier1: 13 + M holy damage
tier2: 19 + M holy damage
tier3: 26 + M holy damage
type: ability
---


*You channel holy energy to seal an enemy's fate.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 13 + M holy damage
- **12-16:** 19 + M holy damage
- **17+:** 26 + M holy damage

**Effect:** Until the end of the encounter or until you are [dying](scc.v1:mcdm.heroes.v1/rule.health/dying), the target has [damage weakness](scc.v1:mcdm.heroes.v1/rule.damage/damage-weakness) 10.
