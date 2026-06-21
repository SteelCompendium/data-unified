---
action_type: Main action
class: summoner
distance: Melee 1
effect: You can spend charges to activate one of the following effects. You can activate an effect multiple times. All charges disappear after using this ability.
feature_source: summoner
feature_type: ability
file_basename: essence-transfer
file_dpath: feature/ability/summoner/level-1
flavor: You pierce your foe and repurpose some of that 'fiber of their being' they weren't using.
item_id: essence-transfer
item_name: Essence Transfer
keywords:
    - Magic
    - Melee
    - Strike
level: "1"
name: Essence Transfer
power_roll_characteristic: Reason
scc: mcdm.summoner.v1/feature.ability.summoner.level-1/essence-transfer
source: mcdm.summoner.v1
target: One creature
tier1: 5 + R corruption damage; 2 charges (see below)
tier2: 8 + R corruption damage; 3 charges
tier3: 11 + R corruption damage; 4 charges
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: You can spend charges to activate one of the following effects. You can activate an effect multiple times. All charges disappear after using this ability.
    - roll: Power Roll + Reason
      tier1: 5 + R corruption damage; 2 charges (see below)
      tier2: 8 + R corruption damage; 3 charges
      tier3: 11 + R corruption damage; 4 charges
feature_type: ability
flavor: You pierce your foe and repurpose some of that 'fiber of their being' they weren't using.
keywords:
    - Magic
    - Melee
    - Strike
metadata:
    action_type: Main action
    class: summoner
    distance: Melee 1
    effect: You can spend charges to activate one of the following effects. You can activate an effect multiple times. All charges disappear after using this ability.
    feature_source: summoner
    flavor: You pierce your foe and repurpose some of that 'fiber of their being' they weren't using.
    keywords:
        - Magic
        - Melee
        - Strike
    level: "1"
    name: Essence Transfer
    power_roll_characteristic: Reason
    scc: mcdm.summoner.v1/feature.ability.summoner.level-1/essence-transfer
    target: One creature
    tier1: 5 + R corruption damage; 2 charges (see below)
    tier2: 8 + R corruption damage; 3 charges
    tier3: 11 + R corruption damage; 4 charges
    type: ability
name: Essence Transfer
target: One creature
type: feature
usage: Main action
```
