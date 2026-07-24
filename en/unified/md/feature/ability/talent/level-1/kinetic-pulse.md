---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
distance: 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 psychic damage
      tier2: 5 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 7 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    - effect: The size of the [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) increases by 2, and you are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
      name: Strained
flavor: The force of your mind hurls enemies backward.
keywords:
    - Area
    - Psionic
    - Telepathy
level: "1"
name: Kinetic Pulse
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/kinetic-pulse
subtype: signature
target: Each enemy in the area
tier1: 2 psychic damage
tier2: 5 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
tier3: 7 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
type: ability
---


*The force of your mind hurls enemies backward.*

| **Area, Psionic, Telepathy** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|------------------------------|------------------------------:|
| **📏 1 [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst)**               | **🎯 Each enemy in the area** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason):**

- **≤11:** 2 psychic damage
- **12-16:** 5 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
- **17+:** 7 psychic damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2

**Strained:** The size of the [burst](scc.v1:mcdm.heroes.v1/rule.combat/burst) increases by 2, and you are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
