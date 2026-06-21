---
action_type: Main action
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
feature_type: ability
file_basename: sic-em
file_dpath: feature/ability/beastheart/level-6
flavor: Your companion rushes forward to protect you from a dangerous foe.
item_id: sic-em
item_name: Sic 'Em!
keywords:
    - Charge
    - Companion
    - Melee
    - Strike
    - Weapon
level: "6"
name: Sic 'Em!
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/sic-em
source: mcdm.beastheart.v1
spend: '2 Ferocity: Your companion can use this ability as a triggered action against an enemy who damages you.'
subclass: guardian
target: One creature
tier1: 11 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 16 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 21 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 11 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 16 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 21 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
    - effect: '2 Ferocity: Your companion can use this ability as a triggered action against an enemy who damages you.'
      name: Spend
feature_type: ability
flavor: Your companion rushes forward to protect you from a dangerous foe.
keywords:
    - Charge
    - Companion
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 9 Ferocity
    distance: Melee 1
    flavor: Your companion rushes forward to protect you from a dangerous foe.
    keywords:
        - Charge
        - Companion
        - Melee
        - Strike
        - Weapon
    level: "6"
    name: Sic 'Em!
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-6/sic-em
    spend: '2 Ferocity: Your companion can use this ability as a triggered action against an enemy who damages you.'
    subclass: guardian
    target: One creature
    tier1: 11 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: 16 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: 21 + M damage; [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) (save ends); M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand (EoT)
    type: ability
name: Sic 'Em!
target: One creature
type: feature
usage: Main action
```
