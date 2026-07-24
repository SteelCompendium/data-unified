---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 + M damage
      tier2: 5 + M damage
      tier3: 7 + M damage; A < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square.
      name: Effect
flavor: Staying in constant motion helps you slip out of reach after a brutal assault.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Hit and Run
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/hit-and-run
subtype: signature
target: One creature or object
tier1: 2 + M damage
tier2: 5 + M damage
tier3: 7 + M damage; A < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
type: ability
---


*Staying in constant motion helps you slip out of reach after a brutal assault.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 + M damage
- **12-16:** 5 + M damage
- **17+:** 7 + M damage; A < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)

**Effect:** You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) 1 square.
