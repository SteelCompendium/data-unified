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

With this stormwight kit, you channel your [primordial ferocity](scc.v1:mcdm.heroes.v1/feature.fury.level-10/primordial-ferocity) into the form of a bear, becoming large, durable, and imposing. [Boren](scc.v1:mcdm.heroes.v1/kit/boren) are tied to the craggy, rocky north, and this aspect is associated with the blizzard's bitter cold.

##### Signature Ability

###### Bear Claws

*Attacks with your sharp and deadly claws grab the weak.*

| **[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee), [Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), Weapon** |               **Main action** |
|---------------------------|------------------------------:|
| **📏 [Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1**            | **🎯 One creature or object** |

**[Power Roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) + [Might](scc.v1:mcdm.heroes.v1/rule.character/might):**

- **≤11:** 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
- **12-16:** 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
- **17+:** 11 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
      tier3: 11 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
feature_type: ability
flavor: Attacks with your sharp and deadly claws grab the weak.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    flavor: Attacks with your sharp and deadly claws grab the weak.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Bear Claws
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    subtype: signature
    target: One creature or object
    tier1: 2 + M damage; M < WEAK, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier2: 5 + M damage; M < AVERAGE, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    tier3: 11 + M damage; M < STRONG, [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed)
    type: ability
name: Bear Claws
target: One creature or object
type: feature
usage: Main action
```
