---
action_type: Maneuver
class: beastheart
companion: panther
distance: Melee 1
effect: The target takes damage equal to 3 + the panther's Might score, and if they have M < AVERAGE, they are knocked [prone](../../../../../../condition/prone.md).
feature_type: ability
file_basename: pounce
file_dpath: feature/ability/companion/beastheart/panther/level-1
flavor: The panther bunches up, then uncoils into a deadly leap.
item_id: pounce
item_name: Pounce
keywords:
    - Companion
    - Melee
    - Weapon
level: "1"
name: Pounce
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.panther.level-1/pounce
source: mcdm.beastheart.v1
spend: '1 Ferocity: The panther can jump up to a number of squares equal to their speed before using this ability. If they jump at least 1 square in this way, a target who has M < STRONG is knocked [prone](../../../../../../condition/prone.md).'
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the panther's Might score, and if they have M < AVERAGE, they are knocked [prone](../../../../../../condition/prone.md).
    - effect: '1 Ferocity: The panther can jump up to a number of squares equal to their speed before using this ability. If they jump at least 1 square in this way, a target who has M < STRONG is knocked [prone](../../../../../../condition/prone.md).'
      name: Spend
feature_type: ability
flavor: The panther bunches up, then uncoils into a deadly leap.
keywords:
    - Companion
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: panther
    distance: Melee 1
    effect: The target takes damage equal to 3 + the panther's Might score, and if they have M < AVERAGE, they are knocked [prone](../../../../../../condition/prone.md).
    flavor: The panther bunches up, then uncoils into a deadly leap.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Pounce
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.panther.level-1/pounce
    spend: '1 Ferocity: The panther can jump up to a number of squares equal to their speed before using this ability. If they jump at least 1 square in this way, a target who has M < STRONG is knocked [prone](../../../../../../condition/prone.md).'
    subtype: signature
    target: One enemy
    type: ability
name: Pounce
target: One enemy
type: feature
usage: Maneuver
```
