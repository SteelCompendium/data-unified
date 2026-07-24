---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 3 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier2: 5 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier3: 8 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    - effect: While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target takes damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score at the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Effect
flavor: Hard for them to fight when they're busy holding in their giblets.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Your Entrails Are Your Extrails!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-1/your-entrails-are-your-extrails
target: One creature or object
tier1: 3 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier2: 5 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier3: 8 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---


*Hard for them to fight when they're busy holding in their giblets.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 3 + M damage; M < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
- **12-16:** 5 + M damage; M < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
- **17+:** 8 + M damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)

**Effect:** While [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) this way, the target takes damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) score at the end of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn).
