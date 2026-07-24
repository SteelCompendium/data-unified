---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage
      tier2: 6 + M damage
      tier3: 9 + M damage
    - effect: You gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), and the target can make an [opportunity attack](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) against you as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action).
      name: Effect
flavor: Your reckless assault leaves you tactically vulnerable.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: To the Death!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/to-the-death
subtype: signature
target: One creature or object
tier1: 3 + M damage
tier2: 6 + M damage
tier3: 9 + M damage
type: ability
---


*Your reckless assault leaves you tactically vulnerable.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 3 + M damage
- **12-16:** 6 + M damage
- **17+:** 9 + M damage

**Effect:** You gain 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge), and the target can make an [opportunity attack](scc.v1:mcdm.heroes.v1/rule.combat/opportunity-attack) against you as a free [triggered action](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action).
