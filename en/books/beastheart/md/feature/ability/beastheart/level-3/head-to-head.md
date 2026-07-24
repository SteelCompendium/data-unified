---
action_type: Main action
class: beastheart
cost: 7 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 13 + M damage; P < WEAK [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier2: 19 + M damage; P < AVERAGE [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
      tier3: 25 + M damage; P < STRONG [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
    - effect: You are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends). Until the end of your next turn, your companion gains an edge on power rolls.
      name: Effect
flavor: Your bloody-forehead smash drives your companion into a frenzy.
keywords:
    - Beastheart
    - Melee
    - Strike
level: "3"
name: Head to Head
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-3/head-to-head
target: One creature
tier1: 13 + M damage; P < WEAK [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier2: 19 + M damage; P < AVERAGE [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
tier3: 25 + M damage; P < STRONG [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
type: ability
---

*Your bloody-forehead smash drives your companion into a frenzy.*

| **Beastheart, Melee, Strike** | **Main action** |
|-------------------------------|----------------:|
| **📏 Melee 1**                | **🎯 One creature** |

**Power Roll + Might:**

- **≤11:** 13 + M damage; P < WEAK [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **12-16:** 19 + M damage; P < AVERAGE [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)
- **17+:** 25 + M damage; P < STRONG [dazed](scc.v1:mcdm.heroes.v1/condition/dazed) (save ends)

**Effect:** You are [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends). Until the end of your next turn, your companion gains an edge on power rolls.
