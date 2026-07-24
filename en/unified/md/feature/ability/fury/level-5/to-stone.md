---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 9 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 9 + M damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 13 + M damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 18 + M damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
    - effect: While the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, any other effect that would make the target [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) instead makes them [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by this ability. Additionally, a creature who fails the [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) while [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way is petrified until they are given a [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) cure or you choose to reverse the effect (no action required).
      name: Effect
flavor: You channel the Primordial Chaos into blows that petrify your foe... literally.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "5"
name: To Stone!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-5/to-stone
target: One creature
tier1: 9 + M damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier2: 13 + M damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
tier3: 18 + M damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)
type: ability
---


*You channel the Primordial Chaos into blows that petrify your foe... literally.*

| **Magic, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                   | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 9 + M damage; M < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **12-16:** 13 + M damage; M < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
- **17+:** 18 + M damage; M < STRONG, [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) (save ends)

**Effect:** While the target is [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) this way, any other effect that would make the target [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) instead makes them [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) by this ability. Additionally, a creature who fails the [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) while [restrained](scc.v1:mcdm.heroes.v1/condition/restrained) this way is petrified until they are given a [supernatural](scc.v1:mcdm.heroes.v1/rule.general/supernatural) cure or you choose to reverse the effect (no action required).
