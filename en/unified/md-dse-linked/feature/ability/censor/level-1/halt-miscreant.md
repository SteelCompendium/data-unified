---
action_type: Main action
class: censor
distance: '[Melee](../../../../rule/combat/melee.md) 1'
feature_type: ability
file_basename: halt-miscreant
file_dpath: feature/ability/censor/level-1
flavor: You infuse your weapon with holy magic that makes it difficult for your foe to get away.
item_id: halt-miscreant
item_name: Halt Miscreant!
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Halt Miscreant!
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/halt-miscreant
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + M holy damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
tier2: 5 + M holy damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
tier3: 7 + M holy damage; P < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
type: ability
---

```ds-feature
distance: '[Melee](../../../../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: 2 + M holy damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
      tier2: 5 + M holy damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
      tier3: 7 + M holy damage; P < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
feature_type: ability
flavor: You infuse your weapon with holy magic that makes it difficult for your foe to get away.
keywords:
    - '[Melee](../../../../rule/combat/melee.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: censor
    distance: '[Melee](../../../../rule/combat/melee.md) 1'
    flavor: You infuse your weapon with holy magic that makes it difficult for your foe to get away.
    keywords:
        - '[Melee](../../../../rule/combat/melee.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Halt Miscreant!
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/halt-miscreant
    subtype: signature
    target: One creature or object
    tier1: 2 + M holy damage; P < WEAK, [slowed](../../../../condition/slowed.md) (save ends)
    tier2: 5 + M holy damage; P < AVERAGE, [slowed](../../../../condition/slowed.md) (save ends)
    tier3: 7 + M holy damage; P < STRONG, [slowed](../../../../condition/slowed.md) (save ends)
    type: ability
name: Halt Miscreant!
target: One creature or object
type: feature
usage: Main action
```
