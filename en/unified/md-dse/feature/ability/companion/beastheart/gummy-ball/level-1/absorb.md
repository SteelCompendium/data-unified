---
action_type: Maneuver
class: beastheart
companion: gummy-ball
distance: Melee 1
effect: The target takes acid damage equal to 3 + the ball's Might score, and if they have A < AVERAGE, the ball moves into the target's space. If the target completely fits within the ball's space, the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the ball.
feature_type: ability
file_basename: absorb
file_dpath: feature/ability/companion/beastheart/gummy-ball/level-1
flavor: With a sickening squelch, the ball oozes around their hapless prey.
item_id: absorb
item_name: Absorb
keywords:
    - Companion
    - Melee
    - Weapon
level: "1"
name: Absorb
scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.gummy-ball.level-1/absorb
source: mcdm.beastheart.v1
spend: '1 Ferocity: A target [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way takes acid damage equal to the ball''s Might score at the end of each of the ball''s turns.'
subtype: signature
target: One enemy
type: ability
---

```ds-feature
distance: Melee 1
effects:
    - effect: The target takes acid damage equal to 3 + the ball's Might score, and if they have A < AVERAGE, the ball moves into the target's space. If the target completely fits within the ball's space, the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the ball.
    - effect: '1 Ferocity: A target [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way takes acid damage equal to the ball''s Might score at the end of each of the ball''s turns.'
      name: Spend
feature_type: ability
flavor: With a sickening squelch, the ball oozes around their hapless prey.
keywords:
    - Companion
    - Melee
    - Weapon
metadata:
    action_type: Maneuver
    class: beastheart
    companion: gummy-ball
    distance: Melee 1
    effect: The target takes acid damage equal to 3 + the ball's Might score, and if they have A < AVERAGE, the ball moves into the target's space. If the target completely fits within the ball's space, the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by the ball.
    flavor: With a sickening squelch, the ball oozes around their hapless prey.
    keywords:
        - Companion
        - Melee
        - Weapon
    level: "1"
    name: Absorb
    scc: mcdm.beastheart.v1/feature.ability.companion.beastheart.gummy-ball.level-1/absorb
    spend: '1 Ferocity: A target [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) this way takes acid damage equal to the ball''s Might score at the end of each of the ball''s turns.'
    subtype: signature
    target: One enemy
    type: ability
name: Absorb
target: One enemy
type: feature
usage: Maneuver
```
