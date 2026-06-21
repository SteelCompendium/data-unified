---
action_type: Main action
class: "null"
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: You can deal damage equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score to one creature or object [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you.
feature_type: ability
file_basename: faster-than-the-eye
file_dpath: feature/ability/null/level-1
flavor: You strike so quickly that your hands become a blur.
item_id: faster-than-the-eye
item_name: Faster Than the Eye
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Faster Than the Eye
power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.null.level-1/faster-than-the-eye
source: mcdm.heroes.v1
subtype: signature
target: Two creatures or objects
tier1: 4 damage
tier2: 5 damage
tier3: 7 damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: You can deal damage equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score to one creature or object [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you.
    - roll: Power Roll + [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 damage
      tier2: 5 damage
      tier3: 7 damage
feature_type: ability
flavor: You strike so quickly that your hands become a blur.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: "null"
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: You can deal damage equal to your [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score to one creature or object [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you.
    flavor: You strike so quickly that your hands become a blur.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Faster Than the Eye
    power_roll_characteristic: '[Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.null.level-1/faster-than-the-eye
    subtype: signature
    target: Two creatures or objects
    tier1: 4 damage
    tier2: 5 damage
    tier3: 7 damage
    type: ability
name: Faster Than the Eye
target: Two creatures or objects
type: feature
usage: Main action
```
