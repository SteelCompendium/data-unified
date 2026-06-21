---
action_type: Main action
class: beastheart
cost: 5 Ferocity
cost_amount: "5"
cost_resource: Ferocity
distance: Melee 2
feature_type: ability
file_basename: burning-lash
file_dpath: feature/ability/beastheart/level-2
flavor: A blazing tongue of energy entangles a foe.
item_id: burning-lash
item_name: Burning Lash
keywords:
    - Companion
    - Magic
    - Melee
    - Strike
    - Weapon
level: "2"
name: Burning Lash
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/burning-lash
source: mcdm.beastheart.v1
spend: '1 Ferocity: If you are within distance of the target, you can use a free maneuver to wield a second whip, dealing extra fire or lightning damage equal to your Intuition score.'
subclass: spark
target: One creature
tier1: 6 + I fire or lightning damage; M < WEAK [prone](../../../../condition/prone.md)
tier2: 9 + I fire or lightning damage; M < AVERAGE [prone](../../../../condition/prone.md)
tier3: 14 + I fire or lightning damage; M < STRONG [prone](../../../../condition/prone.md) and can't stand (EoT)
type: ability
---

```ds-feature
cost: 5 Ferocity
distance: Melee 2
effects:
    - roll: Power Roll + Intuition
      tier1: 6 + I fire or lightning damage; M < WEAK [prone](../../../../condition/prone.md)
      tier2: 9 + I fire or lightning damage; M < AVERAGE [prone](../../../../condition/prone.md)
      tier3: 14 + I fire or lightning damage; M < STRONG [prone](../../../../condition/prone.md) and can't stand (EoT)
    - effect: '1 Ferocity: If you are within distance of the target, you can use a free maneuver to wield a second whip, dealing extra fire or lightning damage equal to your Intuition score.'
      name: Spend
feature_type: ability
flavor: A blazing tongue of energy entangles a foe.
keywords:
    - Companion
    - Magic
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 5 Ferocity
    distance: Melee 2
    flavor: A blazing tongue of energy entangles a foe.
    keywords:
        - Companion
        - Magic
        - Melee
        - Strike
        - Weapon
    level: "2"
    name: Burning Lash
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-2/burning-lash
    spend: '1 Ferocity: If you are within distance of the target, you can use a free maneuver to wield a second whip, dealing extra fire or lightning damage equal to your Intuition score.'
    subclass: spark
    target: One creature
    tier1: 6 + I fire or lightning damage; M < WEAK [prone](../../../../condition/prone.md)
    tier2: 9 + I fire or lightning damage; M < AVERAGE [prone](../../../../condition/prone.md)
    tier3: 14 + I fire or lightning damage; M < STRONG [prone](../../../../condition/prone.md) and can't stand (EoT)
    type: ability
name: Burning Lash
target: One creature
type: feature
usage: Main action
```
