---
action_type: '[Main action](../../../../rule/combat/turn.md)'
class: shadow
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effect: One ally within 5 squares of the target gains 1 [surge](../../../../rule/resource/surge.md).
feature_type: ability
file_basename: gasping-in-pain
file_dpath: feature/ability/shadow/level-1
flavor: Your precise strikes let your allies take advantage of a target's agony.
item_id: gasping-in-pain
item_name: Gasping in Pain
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Gasping in Pain
power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
scc: mcdm.heroes.v1/feature.ability.shadow.level-1/gasping-in-pain
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 3 + A damage
tier2: 5 + A damage
tier3: 8 + A damage; I < STRONG[, prone](../../../../condition/prone.md)
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - effect: One ally within 5 squares of the target gains 1 [surge](../../../../rule/resource/surge.md).
    - roll: Power Roll + [Agility](../../../../rule/character/agility.md)
      tier1: 3 + A damage
      tier2: 5 + A damage
      tier3: 8 + A damage; I < STRONG[, prone](../../../../condition/prone.md)
feature_type: ability
flavor: Your precise strikes let your allies take advantage of a target's agony.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Main action](../../../../rule/combat/turn.md)'
    class: shadow
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    effect: One ally within 5 squares of the target gains 1 [surge](../../../../rule/resource/surge.md).
    flavor: Your precise strikes let your allies take advantage of a target's agony.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Gasping in Pain
    power_roll_characteristic: '[Agility](../../../../rule/character/agility.md)'
    scc: mcdm.heroes.v1/feature.ability.shadow.level-1/gasping-in-pain
    subtype: signature
    target: One creature
    tier1: 3 + A damage
    tier2: 5 + A damage
    tier3: 8 + A damage; I < STRONG[, prone](../../../../condition/prone.md)
    type: ability
name: Gasping in Pain
target: One creature
type: feature
usage: '[Main action](../../../../rule/combat/turn.md)'
```
