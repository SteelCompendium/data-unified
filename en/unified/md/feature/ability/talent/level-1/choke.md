---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
cost: 3 Clarity
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 3 + R damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 5 + R damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 8 + R damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    - effect: You can vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target up to 2 squares. If the target is made [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by this ability, this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
      name: Effect
flavor: You crush a foe in a telekinetic grip.
keywords:
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
    - Telekinesis
level: "1"
name: Choke
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/choke
target: One creature
tier1: 3 + R damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 5 + R damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 8 + R damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---


*You crush a foe in a telekinetic grip.*

| **Psionic, [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)**, **Strike, Telekinesis** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------------------|--------------------:|
| **📏 [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10**                             | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 3 + R damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 5 + R damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **17+:** 8 + R damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)

**Effect:** You can vertical [pull](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target up to 2 squares. If the target is made [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by this ability, this [forced movement](scc.v1:mcdm.heroes.v1/movement/forced-movement) ignores their [stability](scc.v1:mcdm.heroes.v1/rule.character/stability).
