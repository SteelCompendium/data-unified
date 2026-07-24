---
file_basename: vuken
file_dpath: kit
flavor: With this stormwight kit, you channel your primordial ferocity into the form of a wolf, becoming a fleet-footed hunter. Vuken are tied to forests and open steppes, and this aspect is associated with the thunderstorm.
item_id: vuken
item_name: Vuken
name: Vuken
scc: mcdm.heroes.v1/kit/vuken
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](../feature/fury/level-10/primordial-ferocity.md) into the form of a wolf, becoming a fleet-footed hunter. [Vuken](vuken.md) are tied to forests and open steppes, and this aspect is associated with the thunderstorm.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md)
      tier1: 4 + M damage; A < WEAK[, prone](../condition/prone.md)
      tier2: 7 + M damage; A < AVERAGE[, prone](../condition/prone.md)
      tier3: 9 + M damage; A < STRONG[, prone](../condition/prone.md)
feature_type: ability
flavor: A wild assault forces your foe onto their back.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    effects:
        - roll: Power Roll + [Might](../rule/character/might.md)
          tier1: 4 + M damage; A < WEAK[, prone](../condition/prone.md)
          tier2: 7 + M damage; A < AVERAGE[, prone](../condition/prone.md)
          tier3: 9 + M damage; A < STRONG[, prone](../condition/prone.md)
    flavor: A wild assault forces your foe onto their back.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Unbalancing Attack
    power_roll_characteristic: '[Might](../rule/character/might.md)'
    subtype: signature
    target: One creature or object
    tier1: 4 + M damage; A < WEAK[, prone](../condition/prone.md)
    tier2: 7 + M damage; A < AVERAGE[, prone](../condition/prone.md)
    tier3: 9 + M damage; A < STRONG[, prone](../condition/prone.md)
    type: ability
name: Unbalancing Attack
target: One creature or object
type: feature
usage: Main action
```
