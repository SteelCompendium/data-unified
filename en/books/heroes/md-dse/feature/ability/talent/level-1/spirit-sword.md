---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 3 + P damage
      tier2: 6 + P damage
      tier3: 9 + P damage
    - effect: You gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
    - effect: The target takes an extra 3 damage. You also take 3 damage that can't be reduced in any way.
      name: Strained
feature_type: ability
file_basename: spirit-sword
file_dpath: feature/ability/talent/level-1
flavor: You form a blade of mind energy and stab your target, invigorating yourself.
item_id: spirit-sword
item_name: Spirit Sword
keywords:
    - Animapathy
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "1"
name: Spirit Sword
power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/spirit-sword
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 3 + P damage
tier2: 6 + P damage
tier3: 9 + P damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
effects:
    - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 3 + P damage
      tier2: 6 + P damage
      tier3: 9 + P damage
    - effect: You gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
      name: Effect
    - effect: The target takes an extra 3 damage. You also take 3 damage that can't be reduced in any way.
      name: Strained
feature_type: ability
flavor: You form a blade of mind energy and stab your target, invigorating yourself.
keywords:
    - Animapathy
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - Psionic
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 2'
    effects:
        - roll: Power Roll + [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
          tier1: 3 + P damage
          tier2: 6 + P damage
          tier3: 9 + P damage
        - effect: You gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).
          name: Effect
        - effect: The target takes an extra 3 damage. You also take 3 damage that can't be reduced in any way.
          name: Strained
    flavor: You form a blade of mind energy and stab your target, invigorating yourself.
    keywords:
        - Animapathy
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - Psionic
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "1"
    name: Spirit Sword
    power_roll_characteristic: '[Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/spirit-sword
    subtype: signature
    target: One creature or object
    tier1: 3 + P damage
    tier2: 6 + P damage
    tier3: 9 + P damage
    type: ability
name: Spirit Sword
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
