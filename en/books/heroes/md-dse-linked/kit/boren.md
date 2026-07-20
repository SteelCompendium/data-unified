---
file_basename: boren
file_dpath: kit
flavor: With this stormwight kit, you channel your primordial ferocity into the form of a bear, becoming large, durable, and imposing. Boren are tied to the craggy, rocky north, and this aspect is associated with the blizzard's bitter cold.
item_id: boren
item_name: Boren
name: Boren
scc: mcdm.heroes.v1/kit/boren
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](../feature/fury/level-10/primordial-ferocity.md) into the form of a bear, becoming large, durable, and imposing. [Boren](boren.md) are tied to the craggy, rocky north, and this aspect is associated with the blizzard's bitter cold.

```ds-feature
distance: '[Melee](../rule/combat/melee.md) 1'
effects:
    - roll: Power Roll + [Might](../rule/character/might.md)
      tier1: 2 + M damage; M < WEAK, [grabbed](../condition/grabbed.md)
      tier2: 5 + M damage; M < AVERAGE, [grabbed](../condition/grabbed.md)
      tier3: 11 + M damage; M < STRONG, [grabbed](../condition/grabbed.md)
feature_type: ability
flavor: Attacks with your sharp and deadly claws grab the weak.
keywords:
    - '[Melee](../rule/combat/melee.md)'
    - '[Strike](../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](../rule/combat/melee.md) 1'
    flavor: Attacks with your sharp and deadly claws grab the weak.
    keywords:
        - '[Melee](../rule/combat/melee.md)'
        - '[Strike](../rule/combat/strike.md)'
        - Weapon
    name: Bear Claws
    power_roll_characteristic: '[Might](../rule/character/might.md)'
    subtype: signature
    target: One creature or object
    tier1: 2 + M damage; M < WEAK, [grabbed](../condition/grabbed.md)
    tier2: 5 + M damage; M < AVERAGE, [grabbed](../condition/grabbed.md)
    tier3: 11 + M damage; M < STRONG, [grabbed](../condition/grabbed.md)
    type: ability
name: Bear Claws
target: One creature or object
type: feature
usage: Main action
```
