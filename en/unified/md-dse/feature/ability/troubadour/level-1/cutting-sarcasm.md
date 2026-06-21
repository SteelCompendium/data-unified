---
action_type: Main action
class: troubadour
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
feature_type: ability
file_basename: cutting-sarcasm
file_dpath: feature/ability/troubadour/level-1
flavor: There you are, radiating your usual charisma.
item_id: cutting-sarcasm
item_name: Cutting Sarcasm
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Cutting Sarcasm
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/cutting-sarcasm
source: mcdm.heroes.v1
subtype: signature
target: One creature
tier1: 2 + P psychic damage; P < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier2: 5 + P psychic damage; P < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier3: 7 + P psychic damage; P < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 2 + P psychic damage; P < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier2: 5 + P psychic damage; P < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier3: 7 + P psychic damage; P < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
feature_type: ability
flavor: There you are, radiating your usual charisma.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: troubadour
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    flavor: There you are, radiating your usual charisma.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Cutting Sarcasm
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.troubadour.level-1/cutting-sarcasm
    subtype: signature
    target: One creature
    tier1: 2 + P psychic damage; P < WEAK, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier2: 5 + P psychic damage; P < AVERAGE, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier3: 7 + P psychic damage; P < STRONG, [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    type: ability
name: Cutting Sarcasm
target: One creature
type: feature
usage: Main action
```
