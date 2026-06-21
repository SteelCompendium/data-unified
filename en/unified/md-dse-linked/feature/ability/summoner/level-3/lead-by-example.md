---
action_type: Main action
class: summoner
distance: Melee 1 or Summoner's Range
feature_source: summoner
feature_type: ability
file_basename: lead-by-example
file_dpath: feature/ability/summoner/level-3
flavor: Your minions watch as your implement crackles with power, ready to slam unbelievable force into your foe.
item_id: lead-by-example
item_name: Lead By Example
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
level: "3"
name: Lead By Example
power_roll_characteristic: Reason
scc: mcdm.summoner.v1/feature.ability.summoner.level-3/lead-by-example
source: mcdm.summoner.v1
target: One enemy or object
tier1: 8 + R [damage](../../../../rule/damage/damage.md); R < WEAK [dazed](../../../../condition/dazed.md) (save ends)
tier2: 12 + R [damage](../../../../rule/damage/damage.md); R < AVERAGE [dazed](../../../../condition/dazed.md) (save ends)
tier3: 16 + R [damage](../../../../rule/damage/damage.md); R < STRONG [dazed](../../../../condition/dazed.md) (save ends)
type: ability
---

```ds-feature
distance: Melee 1 or Summoner's Range
effects:
    - roll: Power Roll + Reason
      tier1: 8 + R [damage](../../../../rule/damage/damage.md); R < WEAK [dazed](../../../../condition/dazed.md) (save ends)
      tier2: 12 + R [damage](../../../../rule/damage/damage.md); R < AVERAGE [dazed](../../../../condition/dazed.md) (save ends)
      tier3: 16 + R [damage](../../../../rule/damage/damage.md); R < STRONG [dazed](../../../../condition/dazed.md) (save ends)
feature_type: ability
flavor: Your minions watch as your implement crackles with power, ready to slam unbelievable force into your foe.
keywords:
    - Magic
    - Melee
    - Ranged
    - Strike
metadata:
    action_type: Main action
    class: summoner
    distance: Melee 1 or Summoner's Range
    feature_source: summoner
    flavor: Your minions watch as your implement crackles with power, ready to slam unbelievable force into your foe.
    keywords:
        - Magic
        - Melee
        - Ranged
        - Strike
    level: "3"
    name: Lead By Example
    power_roll_characteristic: Reason
    scc: mcdm.summoner.v1/feature.ability.summoner.level-3/lead-by-example
    target: One enemy or object
    tier1: 8 + R [damage](../../../../rule/damage/damage.md); R < WEAK [dazed](../../../../condition/dazed.md) (save ends)
    tier2: 12 + R [damage](../../../../rule/damage/damage.md); R < AVERAGE [dazed](../../../../condition/dazed.md) (save ends)
    tier3: 16 + R [damage](../../../../rule/damage/damage.md); R < STRONG [dazed](../../../../condition/dazed.md) (save ends)
    type: ability
name: Lead By Example
target: One enemy or object
type: feature
usage: Main action
```
