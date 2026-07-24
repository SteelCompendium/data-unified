---
action_type: Main action
class: beastheart
cost: 5 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 3 + M damage; push 2; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 5 + M damage; push 3; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 8 + M damage; push 4; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - effect: If the target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) at least 1 square, an enemy adjacent to the target at the end of this forced movement is also targeted by this ability's power roll, but they don't trigger this effect.
      name: Effect
flavor: Your companion sends one enemy tumbling into another, taking them both out.
keywords:
    - Charge
    - Companion
    - Melee
    - Strike
    - Weapon
level: "2"
name: Foe Bowling
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/foe-bowling
subclass: punisher
target: One creature
tier1: 3 + M damage; push 2; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 5 + M damage; push 3; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 8 + M damage; push 4; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

*Your companion sends one enemy tumbling into another, taking them both out.*

| **Charge, Companion, Melee, Strike, Weapon** | **Main action** |
|----------------------------------------------|----------------:|
| **📏 Melee 1**                               | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 3 + M damage; push 2; M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
- **12-16:** 5 + M damage; push 3; M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
- **17+:** 8 + M damage; push 4; M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone)

**Effect:** If the target is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement) at least 1 square, an enemy adjacent to the target at the end of this forced movement is also targeted by this ability's power roll, but they don't trigger this effect.
