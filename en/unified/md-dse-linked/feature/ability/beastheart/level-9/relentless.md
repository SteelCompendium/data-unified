---
action_type: Main action
class: beastheart
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: Melee 1
effect: While the target is [taunted](../../../../condition/taunted.md) this way, all creatures except your companion have immunity 10 to damage dealt by the target.
feature_type: ability
file_basename: relentless
file_dpath: feature/ability/beastheart/level-9
flavor: Your companion launches at your foe, shielding allies with their body.
item_id: relentless
item_name: Relentless
keywords:
    - Charge
    - Companion
    - Melee
    - Strike
    - Weapon
level: "9"
name: Relentless
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/relentless
source: mcdm.beastheart.v1
subclass: guardian
target: One enemy
tier1: 11 + M damage; P < WEAK [taunted](../../../../condition/taunted.md) (save ends)
tier2: 17 + M damage; P < AVERAGE [taunted](../../../../condition/taunted.md) (save ends)
tier3: 22 + M damage; P < STRONG [taunted](../../../../condition/taunted.md) (save ends)
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: Melee 1
effects:
    - effect: While the target is [taunted](../../../../condition/taunted.md) this way, all creatures except your companion have immunity 10 to damage dealt by the target.
    - roll: Power Roll + Might
      tier1: 11 + M damage; P < WEAK [taunted](../../../../condition/taunted.md) (save ends)
      tier2: 17 + M damage; P < AVERAGE [taunted](../../../../condition/taunted.md) (save ends)
      tier3: 22 + M damage; P < STRONG [taunted](../../../../condition/taunted.md) (save ends)
feature_type: ability
flavor: Your companion launches at your foe, shielding allies with their body.
keywords:
    - Charge
    - Companion
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 11 Ferocity
    distance: Melee 1
    effect: While the target is [taunted](../../../../condition/taunted.md) this way, all creatures except your companion have immunity 10 to damage dealt by the target.
    flavor: Your companion launches at your foe, shielding allies with their body.
    keywords:
        - Charge
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "9"
    name: Relentless
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/relentless
    subclass: guardian
    target: One enemy
    tier1: 11 + M damage; P < WEAK [taunted](../../../../condition/taunted.md) (save ends)
    tier2: 17 + M damage; P < AVERAGE [taunted](../../../../condition/taunted.md) (save ends)
    tier3: 22 + M damage; P < STRONG [taunted](../../../../condition/taunted.md) (save ends)
    type: ability
name: Relentless
target: One enemy
type: feature
usage: Main action
```
