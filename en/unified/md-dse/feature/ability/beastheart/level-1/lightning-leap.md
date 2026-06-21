---
action_type: Maneuver
class: beastheart
distance: Melee 1
effect: The target takes damage equal to 3 + your Might score. Before you use this ability, you can [jump](scc.v1:mcdm.heroes.v1/movement/jump) up to a number of squares equal to your Intuition score in a straight line. During this jump, enemies' spaces don't count as [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for you. The target takes extra lightning damage equal to the number of squares you jumped this way.
feature_type: ability
file_basename: lightning-leap
file_dpath: feature/ability/beastheart/level-1
flavor: You summon a lightning bolt and ride it into battle.
item_id: lightning-leap
item_name: Lightning Leap
keywords:
    - Beastheart
    - Melee
    - Weapon
level: "1"
name: Lightning Leap
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/lightning-leap
source: mcdm.beastheart.v1
spend: '1 Ferocity: Your jump doesn''t provoke opportunity attacks.'
subclass: prowler
target: One creature
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + your Might score. Before you use this ability, you can [jump](scc.v1:mcdm.heroes.v1/movement/jump) up to a number of squares equal to your Intuition score in a straight line. During this jump, enemies' spaces don't count as [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for you. The target takes extra lightning damage equal to the number of squares you jumped this way.
    - effect: '1 Ferocity: Your jump doesn''t provoke opportunity attacks.'
      name: Spend
feature_type: ability
flavor: You summon a lightning bolt and ride it into battle.
keywords:
    - Beastheart
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    distance: Melee 1
    effect: The target takes damage equal to 3 + your Might score. Before you use this ability, you can [jump](scc.v1:mcdm.heroes.v1/movement/jump) up to a number of squares equal to your Intuition score in a straight line. During this jump, enemies' spaces don't count as [difficult terrain](scc.v1:mcdm.heroes.v1/movement/difficult-terrain) for you. The target takes extra lightning damage equal to the number of squares you jumped this way.
    flavor: You summon a lightning bolt and ride it into battle.
    keywords:
        - Beastheart
        - Melee
        - Weapon
    level: "1"
    name: Lightning Leap
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-1/lightning-leap
    spend: '1 Ferocity: Your jump doesn''t provoke opportunity attacks.'
    subclass: prowler
    target: One creature
    type: ability
name: Lightning Leap
target: One creature
type: feature
usage: Maneuver
```
