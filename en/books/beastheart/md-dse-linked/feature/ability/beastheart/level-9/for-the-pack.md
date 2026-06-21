---
action_type: Free Triggered Action
class: beastheart
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: Self
effect: Your companion makes a power roll, which targets each enemy in a 5 burst.
feature_type: ability
file_basename: for-the-pack
file_dpath: feature/ability/beastheart/level-9
flavor: They'd tell stories in hushed tones of your companion's last stand—if any of them lived to tell the tale.
item_id: for-the-pack
item_name: For the Pack!
keywords:
    - Area
    - Companion
    - Magic
level: "9"
name: For the Pack!
power_roll_characteristic: Intuition
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/for-the-pack
source: mcdm.beastheart.v1
subclass: spark
target: Self
tier1: 20 cold, fire, lightning, or sonic damage
tier2: 25 cold, fire, lightning, or sonic damage
tier3: 30 cold, fire, lightning, or sonic damage
trigger: After taking damage, your companion is dead or dying.
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: Self
effects:
    - effect: Your companion makes a power roll, which targets each enemy in a 5 burst.
    - roll: Power Roll + Intuition
      tier1: 20 cold, fire, lightning, or sonic damage
      tier2: 25 cold, fire, lightning, or sonic damage
      tier3: 30 cold, fire, lightning, or sonic damage
feature_type: ability
flavor: They'd tell stories in hushed tones of your companion's last stand—if any of them lived to tell the tale.
keywords:
    - Area
    - Companion
    - Magic
metadata:
    action_type: Free Triggered Action
    class: beastheart
    cost: 11 Ferocity
    distance: Self
    effect: Your companion makes a power roll, which targets each enemy in a 5 burst.
    flavor: They'd tell stories in hushed tones of your companion's last stand—if any of them lived to tell the tale.
    keywords:
        - Area
        - Companion
        - Magic
    level: "9"
    name: For the Pack!
    power_roll_characteristic: Intuition
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-9/for-the-pack
    subclass: spark
    target: Self
    tier1: 20 cold, fire, lightning, or sonic damage
    tier2: 25 cold, fire, lightning, or sonic damage
    tier3: 30 cold, fire, lightning, or sonic damage
    trigger: After taking damage, your companion is dead or dying.
    type: ability
name: For the Pack!
target: Self
trigger: After taking damage, your companion is dead or dying.
type: feature
usage: Free Triggered Action
```
