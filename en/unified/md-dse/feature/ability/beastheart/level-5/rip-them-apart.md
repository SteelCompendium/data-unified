---
action_type: Main action
class: beastheart
cost: 9 Ferocity
cost_amount: "9"
cost_resource: Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 11 + M damage; M < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier2: 17 + M damage; M < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier3: 22 + M damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    - effect: If the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by your partner, the target takes extra damage equal to your Might score plus your partner's Might score. If the target is reduced to 0 Stamina by this ability, each enemy within 2 squares who has P < AVERAGE is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends).
      name: Effect
feature_type: ability
file_basename: rip-them-apart
file_dpath: feature/ability/beastheart/level-5
flavor: In a gruesome display, you and your companion rip off a pinned enemy's limb or other body part and toss it away.
item_id: rip-them-apart
item_name: Rip Them Apart!
keywords:
    - Melee
    - Strike
    - Weapon
level: "5"
name: Rip Them Apart!
power_roll_characteristic: Might
scc: mcdm.beastheart.v1/feature.ability.beastheart.level-5/rip-them-apart
source: mcdm.beastheart.v1
target: One creature
tier1: 11 + M damage; M < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier2: 17 + M damage; M < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
tier3: 22 + M damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
type: ability
---

```ds-feature
cost: 9 Ferocity
distance: Melee 1
effects:
    - roll: Power Roll + Might
      tier1: 11 + M damage; M < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier2: 17 + M damage; M < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
      tier3: 22 + M damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    - effect: If the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by your partner, the target takes extra damage equal to your Might score plus your partner's Might score. If the target is reduced to 0 Stamina by this ability, each enemy within 2 squares who has P < AVERAGE is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends).
      name: Effect
feature_type: ability
flavor: In a gruesome display, you and your companion rip off a pinned enemy's limb or other body part and toss it away.
keywords:
    - Melee
    - Strike
    - Weapon
metadata:
    action_type: Main action
    class: beastheart
    cost: 9 Ferocity
    distance: Melee 1
    effects:
        - roll: Power Roll + Might
          tier1: 11 + M damage; M < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier2: 17 + M damage; M < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
          tier3: 22 + M damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
        - effect: If the target is [grabbed](scc.v1:mcdm.heroes.v1/condition/grabbed) by your partner, the target takes extra damage equal to your Might score plus your partner's Might score. If the target is reduced to 0 Stamina by this ability, each enemy within 2 squares who has P < AVERAGE is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends).
          name: Effect
    flavor: In a gruesome display, you and your companion rip off a pinned enemy's limb or other body part and toss it away.
    keywords:
        - Melee
        - Strike
        - Weapon
    level: "5"
    name: Rip Them Apart!
    power_roll_characteristic: Might
    scc: mcdm.beastheart.v1/feature.ability.beastheart.level-5/rip-them-apart
    target: One creature
    tier1: 11 + M damage; M < WEAK [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier2: 17 + M damage; M < AVERAGE [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    tier3: 22 + M damage; M < STRONG [bleeding](scc.v1:mcdm.heroes.v1/condition/bleeding) (save ends)
    type: ability
name: Rip Them Apart!
target: One creature
type: feature
usage: Main action
```
