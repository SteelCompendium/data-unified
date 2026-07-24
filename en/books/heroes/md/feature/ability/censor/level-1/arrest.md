---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 5 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 6 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 9 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 13 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    - effect: If the target makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a creature while [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, you can spend 3 wrath to deal holy damage to them equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score, then change the target of the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) to another target within the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
      name: Effect
flavor: '"I got you, you son of a bitch."'
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Arrest
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/arrest
target: One creature
tier1: 6 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier2: 9 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
tier3: 13 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
type: ability
---


*"I got you, you son of a bitch."*

| **Magic, [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|----------------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**                   |           **🎯 One creature** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 6 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
- **12-16:** 9 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
- **17+:** 13 + M holy damage; [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)

**Effect:** If the target makes a [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) against a creature while [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way, you can spend 3 wrath to deal holy damage to them equal to your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score, then change the target of the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) to another target within the [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'s [distance](scc.v1:mcdm.heroes.v1/rule.combat/distance).
