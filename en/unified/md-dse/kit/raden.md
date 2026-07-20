---
file_basename: raden
file_dpath: kit
flavor: With this stormwight kit, you channel your primordial ferocity into the form of a rat, becoming mobile and elusive. Raden are associated with the wild nature of the rat, before cities became their habitat. This aspect is associated with the rat flood—a surge of corrupted water that draws forth hordes of rats.
item_id: raden
item_name: Raden
name: Raden
scc: mcdm.heroes.v1/kit/raden
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](scc.v1:mcdm.heroes.v1/feature.fury.level-10/primordial-ferocity) into the form of a rat, becoming mobile and elusive. [Raden](scc.v1:mcdm.heroes.v1/kit/raden) are associated with the wild nature of the rat, before cities became their habitat. This aspect is associated with the rat flood—a surge of corrupted water that draws forth hordes of rats.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to the same number of squares that you [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 + A damage
      tier2: 7 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
      tier3: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
feature_type: ability
flavor: Your enemies try in vain to fall back from your pouncing attack.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can [shift](scc.v1:mcdm.heroes.v1/movement/shifting) up to the same number of squares that you [pushed](scc.v1:mcdm.heroes.v1/movement/forced-movement) the target.
    flavor: Your enemies try in vain to fall back from your pouncing attack.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Driving Pounce
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature or object
    tier1: 4 + A damage
    tier2: 7 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 1
    tier3: 9 + A damage; [push](scc.v1:mcdm.heroes.v1/movement/forced-movement) 2
    type: ability
name: Driving Pounce
target: One creature or object
type: feature
usage: Main action
```
