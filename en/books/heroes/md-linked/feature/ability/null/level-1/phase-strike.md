---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: "null"
cost: 5 Discipline
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 3 + A psychic damage; I < WEAK, the target goes out of phase (save ends)
      tier2: 4 + A psychic damage; I < AVERAGE, the target goes out of phase (save ends)
      tier3: 6 + A psychic damage; I < STRONG, the target goes out of phase (save ends)
    - effect: A target who goes out of phase is [slowed](../../../../condition/slowed.md), has their [stability](../../../../rule/character/stability.md) reduced by 2, and can't obtain a tier 3 outcome on [ability rolls](../../../../rule/dice/ability-roll.md).
      name: Effect
flavor: For a moment, your foe slips out of phase with this manifold.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - Psionic
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Phase Strike
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/phase-strike
target: One creature
tier1: 3 + A psychic damage; I < WEAK, the target goes out of phase (save ends)
tier2: 4 + A psychic damage; I < AVERAGE, the target goes out of phase (save ends)
tier3: 6 + A psychic damage; I < STRONG, the target goes out of phase (save ends)
type: ability
---


*For a moment, your foe slips out of phase with this manifold.*

| **[Melee](../../../../rule/combat/melee.md), Psionic, [Strike](../../../../rule/combat/strike.md), Weapon** |                           **[Main action](../../../../rule/combat/turn.md)** |
|------------------------------------|------------------------------------------:|
| **📏 [Melee](../../../../rule/combat/melee.md) 1**                     |                       **🎯 One creature** |

**[Power Roll](../../../../rule/dice/power-roll.md) + [Agility](../../../../rule/character/agility.md):**

- **≤11:** 3 + A psychic damage; I < WEAK, the target goes out of phase (save ends)
- **12-16:** 4 + A psychic damage; I < AVERAGE, the target goes out of phase (save ends)
- **17+:** 6 + A psychic damage; I < STRONG, the target goes out of phase (save ends)

**Effect:** A target who goes out of phase is [slowed](../../../../condition/slowed.md), has their [stability](../../../../rule/character/stability.md) reduced by 2, and can't obtain a tier 3 outcome on [ability rolls](../../../../rule/dice/ability-roll.md).
