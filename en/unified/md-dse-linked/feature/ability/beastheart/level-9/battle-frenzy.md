---
action_type: Main action
class: beastheart
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: 5 burst
effects:
    - effect: This ability targets only creatures you choose within distance.
      name: Special
    - roll: Power Roll + Might
      tier1: P < WEAK the target is battle-frenzied
      tier2: P < AVERAGE the target is battle-frenzied
      tier3: The target is battle-frenzied
    - effect: If a target resists the potency, they can choose to become battle-frenzied.
      name: Effect
feature_type: ability
file_basename: battle-frenzy
file_dpath: feature/ability/beastheart/level-9
flavor: Your companion shatters the floodgates that keep their rampage dammed up, and it cascades into the unprepared minds of nearby creatures.
item_id: battle-frenzy
item_name: Battle Frenzy
keywords:
    - Area
    - Companion
    - Magic
level: "9"
name: Battle Frenzy
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/battle-frenzy
source: mcdm.beastheart.v1
subclass: punisher
target: Special
tier1: P < WEAK the target is battle-frenzied
tier2: P < AVERAGE the target is battle-frenzied
tier3: The target is battle-frenzied
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: 5 burst
effects:
    - effect: This ability targets only creatures you choose within distance.
      name: Special
    - roll: Power Roll + Might
      tier1: P < WEAK the target is battle-frenzied
      tier2: P < AVERAGE the target is battle-frenzied
      tier3: The target is battle-frenzied
    - effect: If a target resists the potency, they can choose to become battle-frenzied.
      name: Effect
feature_type: ability
flavor: Your companion shatters the floodgates that keep their rampage dammed up, and it cascades into the unprepared minds of nearby creatures.
keywords:
    - Area
    - Companion
    - Magic
metadata:
    action_type: Main action
    class: beastheart
    cost: 11 Ferocity
    distance: 5 burst
    effects:
        - effect: This ability targets only creatures you choose within distance.
          name: Special
        - roll: Power Roll + Might
          tier1: P < WEAK the target is battle-frenzied
          tier2: P < AVERAGE the target is battle-frenzied
          tier3: The target is battle-frenzied
        - effect: If a target resists the potency, they can choose to become battle-frenzied.
          name: Effect
    flavor: Your companion shatters the floodgates that keep their rampage dammed up, and it cascades into the unprepared minds of nearby creatures.
    keywords:
        - Area
        - Companion
        - Magic
    level: "9"
    name: Battle Frenzy
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/battle-frenzy
    subclass: punisher
    target: Special
    tier1: P < WEAK the target is battle-frenzied
    tier2: P < AVERAGE the target is battle-frenzied
    tier3: The target is battle-frenzied
    type: ability
name: Battle Frenzy
target: Special
type: feature
usage: Main action
```
