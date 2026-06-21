---
action_type: Maneuver
class: beastheart
companion: condor
distance: Melee 1
effect: The target takes damage equal to 3 + the condor's Might score. Additionally, enemies are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) while adjacent to the condor until the end of your next turn.
feature_type: ability
file_basename: flurry-of-wings
file_dpath: feature/ability/companion/beastheart/condor/level-1
flavor: I can't draw a bead on them with that infernal bird flapping in my face!
item_id: flurry-of-wings
item_name: Flurry of Wings
keywords:
    - Companion
    - Melee
    - Weapon
level: "1"
name: Flurry of Wings
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.condor.level-1/flurry-of-wings
source: mcdm.beastheart.v1
spend: '1 Ferocity: An enemy who would be [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) by this ability is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) instead.'
subtype: signature
target: One creature or object
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes damage equal to 3 + the condor's Might score. Additionally, enemies are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) while adjacent to the condor until the end of your next turn.
    - effect: '1 Ferocity: An enemy who would be [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) by this ability is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) instead.'
      name: Spend
feature_type: ability
flavor: I can't draw a bead on them with that infernal bird flapping in my face!
keywords:
    - Companion
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: condor
    distance: Melee 1
    effect: The target takes damage equal to 3 + the condor's Might score. Additionally, enemies are [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) while adjacent to the condor until the end of your next turn.
    flavor: I can't draw a bead on them with that infernal bird flapping in my face!
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Flurry of Wings
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.condor.level-1/flurry-of-wings
    spend: '1 Ferocity: An enemy who would be [weakened](scc.v1:mcdm.heroes.v1/condition/weakened) by this ability is [taunted](scc.v1:mcdm.heroes.v1/condition/taunted) instead.'
    subtype: signature
    target: One creature or object
    type: ability
name: Flurry of Wings
target: One creature or object
type: feature
usage: Maneuver
```
