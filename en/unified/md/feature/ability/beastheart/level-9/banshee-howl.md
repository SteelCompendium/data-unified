---
action_type: Main action
class: beastheart
cost: 11 Ferocity
distance: 3 burst
effects:
    - roll: Power Roll + Intuition
      tier1: 5 sonic damage; I < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 10 sonic damage; I < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 15 sonic damage; I < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    - effect: While [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way, a creature takes 10 psychic damage at the start of each of your turns.
      name: Effect
    - cost: Spend 1 Ferocity
      effect: This ability also affects a 3 burst originating from you. An enemy in both areas is only affected once.
flavor: Your companion's howl, screech, roar, or psychic emanation presages death to those who hear it.
keywords:
    - Area
    - Companion
    - Magic
level: "9"
name: Banshee Howl
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/banshee-howl
subclass: guardian
target: Each enemy in the area
tier1: 5 sonic damage; I < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 10 sonic damage; I < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 15 sonic damage; I < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

*Your companion's howl, screech, roar, or psychic emanation presages death to those who hear it.*

| **Area, Companion, Magic** |              **Main action** |
|----------------------------|-----------------------------:|
| **📏 3 burst**             | **🎯 Each enemy in the area** |

**Power Roll + Intuition:**

- **≤11:** 5 sonic damage; I < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
- **12-16:** 10 sonic damage; I < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
- **17+:** 15 sonic damage; I < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)

**Effect:** While [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) this way, a creature takes 10 psychic damage at the start of each of your turns.

**Spend 1 Ferocity:** This ability also affects a 3 burst originating from you. An enemy in both areas is only affected once.
