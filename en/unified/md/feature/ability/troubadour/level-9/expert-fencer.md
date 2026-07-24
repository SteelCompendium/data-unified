---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: troubadour
cost: 11 Drama
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 15 + A damage
      tier2: 21 + A damage
      tier3: 28 + A damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    - effect: This ability can't obtain better than a tier 2 outcome unless the target is at maximum [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) that you can use immediately.
      name: Effect
flavor: If you can land the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the crowd goes wild.
keywords:
    - Charge
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Expert Fencer
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-9/expert-fencer
subclass: duelist
target: One creature or object
tier1: 15 + A damage
tier2: 21 + A damage
tier3: 28 + A damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---


*If you can land the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), the crowd goes wild.*

| **Charge, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-----------------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 3**                    | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 15 + A damage
- **12-16:** 21 + A damage
- **17+:** 28 + A damage; M < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)

**Effect:** This ability can't obtain better than a tier 2 outcome unless the target is at maximum [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance). If you obtain a tier 3 outcome with a natural 17 or higher, you gain 3 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge) that you can use immediately.
