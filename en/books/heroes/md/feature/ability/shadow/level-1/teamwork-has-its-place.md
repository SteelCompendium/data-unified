---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: shadow
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + A damage
      tier2: 6 + A damage
      tier3: 9 + A damage
    - effect: If any ally is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
      name: Effect
flavor: You attack an enemy as an ally exposes their weakness.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Teamwork Has Its Place
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/teamwork-has-its-place
subtype: signature
target: One creature or object
tier1: 3 + A damage
tier2: 6 + A damage
tier3: 9 + A damage
type: ability
---


*You attack an enemy as an ally exposes their weakness.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)** |
|-----------------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1 or [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5**        | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility):**

- **≤11:** 3 + A damage
- **12-16:** 6 + A damage
- **17+:** 9 + A damage

**Effect:** If any ally is [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to the target, you gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) before making the [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
