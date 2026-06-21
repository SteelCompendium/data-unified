---
action_type: Main action
class: troubadour
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
feature_type: ability
file_basename: cutting-sarcasm
file_dpath: feature/ability/troubadour/level-1
flavor: There you are, radiating your usual charisma.
item_id: cutting-sarcasm
item_name: Cutting Sarcasm
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "1"
name: Cutting Sarcasm
power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/cutting-sarcasm
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + P psychic damage; P < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
tier2: 5 + P psychic damage; P < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
tier3: 7 + P psychic damage; P < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - roll: Power Roll + [Presence](../../../../rule/character/presence.md)
      tier1: 2 + P psychic damage; P < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier2: 5 + P psychic damage; P < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
      tier3: 7 + P psychic damage; P < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
feature_type: ability
flavor: There you are, radiating your usual charisma.
keywords:
    - Magic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    flavor: There you are, radiating your usual charisma.
    keywords:
        - Magic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "1"
    name: Cutting Sarcasm
    power_roll_characteristic: '[Presence](../../../../rule/character/presence.md)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/cutting-sarcasm
    subtype: signature
    target: One creature
    tier1: 2 + P psychic damage; P < WEAK, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier2: 5 + P psychic damage; P < AVERAGE, [bleeding](../../../../condition/bleeding.md) (save ends)
    tier3: 7 + P psychic damage; P < STRONG, [bleeding](../../../../condition/bleeding.md) (save ends)
    type: ability
name: Cutting Sarcasm
target: One creature
type: feature
usage: Main action
```
