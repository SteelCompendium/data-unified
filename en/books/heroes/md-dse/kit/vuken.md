---
file_basename: vuken
file_dpath: kit
flavor: With this stormwight kit, you channel your primordial ferocity into the form of a wolf, becoming a fleet-footed hunter. Vuken are tied to forests and open steppes, and this aspect is associated with the thunderstorm.
item_id: vuken
item_name: Vuken
kit_type: Martial
name: Vuken
scc: mcdm.heroes.v1/kit/vuken
source: mcdm.heroes.v1
type: kit
---

With this stormwight kit, you channel your [primordial ferocity](scc.v1:mcdm.heroes.v1/feature.fury.level-10/primordial-ferocity) into the form of a wolf, becoming a fleet-footed hunter. [Vuken](scc.v1:mcdm.heroes.v1/kit/vuken) are tied to forests and open steppes, and this aspect is associated with the thunderstorm.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 4 + M damage; A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 7 + M damage; A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 9 + M damage; A < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
feature_type: ability
flavor: A wild assault forces your foe onto their back.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 4 + M damage; A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier2: 7 + M damage; A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 9 + M damage; A < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    flavor: A wild assault forces your foe onto their back.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Unbalancing Attack
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    subtype: signature
    target: One creature or object
    tier1: 4 + M damage; A < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: 7 + M damage; A < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: 9 + M damage; A < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Unbalancing Attack
target: One creature or object
type: feature
usage: Main action
```
