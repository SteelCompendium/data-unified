---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: fury
cost: 11 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M damage
      tier2: 10 + M damage
      tier3: 14 + M damage
    - effect: If the target is a minion or is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) but isn't a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before this ability's damage is dealt. If the target is killed by this damage, you can deal any damage over what was required to kill them to another creature within 5 squares of the target.
      name: Effect
flavor: You strike so no damage is wasted.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "8"
name: Overkill
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-8/overkill
target: One creature
tier1: 6 + M damage
tier2: 10 + M damage
tier3: 14 + M damage
type: ability
---


*You strike so no damage is wasted.*

| **Magic, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |     **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------|--------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                   | **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 6 + M damage
- **12-16:** 10 + M damage
- **17+:** 14 + M damage

**Effect:** If the target is a minion or is [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) but isn't a leader or solo creature, they are reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) before this ability's damage is dealt. If the target is killed by this damage, you can deal any damage over what was required to kill them to another creature within 5 squares of the target.
