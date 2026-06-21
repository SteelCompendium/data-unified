---
action_type: Main action
class: talent
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effect: When targeting an object with a solid reflective surface or a creature carrying or wearing such an object (such as a mirror, an unpainted metal shield, or shiny metal plate armor), you can target one additional creature or object within 3 squares of the first target.
feature_type: ability
file_basename: optic-blast
file_dpath: feature/ability/talent/level-1
flavor: Your eyes emit rays of powerful enervating force.
item_id: optic-blast
item_name: Optic Blast
keywords:
    - Metamorphosis
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
level: "1"
name: Optic Blast
power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/optic-blast
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + R damage; M < WEAK[, prone](../../../../condition/prone.md)
tier2: 4 + R damage; M < AVERAGE[, prone](../../../../condition/prone.md)
tier3: 6 + R damage; M < STRONG[, prone](../../../../condition/prone.md)
type: ability
---

```ds-feature
distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
effects:
    - effect: When targeting an object with a solid reflective surface or a creature carrying or wearing such an object (such as a mirror, an unpainted metal shield, or shiny metal plate armor), you can target one additional creature or object within 3 squares of the first target.
    - roll: Power Roll + [Reason](../../../../rule/character/reason.md)
      tier1: 2 + R damage; M < WEAK[, prone](../../../../condition/prone.md)
      tier2: 4 + R damage; M < AVERAGE[, prone](../../../../condition/prone.md)
      tier3: 6 + R damage; M < STRONG[, prone](../../../../condition/prone.md)
feature_type: ability
flavor: Your eyes emit rays of powerful enervating force.
keywords:
    - Metamorphosis
    - Psionic
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - Strike
metadata:
    action_type: Main action
    class: talent
    distance: '[Ranged](../../../../rule/combat/ranged.md) 10'
    effect: When targeting an object with a solid reflective surface or a creature carrying or wearing such an object (such as a mirror, an unpainted metal shield, or shiny metal plate armor), you can target one additional creature or object within 3 squares of the first target.
    flavor: Your eyes emit rays of powerful enervating force.
    keywords:
        - Metamorphosis
        - Psionic
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - Strike
    level: "1"
    name: Optic Blast
    power_roll_characteristic: '[Reason](../../../../rule/character/reason.md)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/optic-blast
    subtype: signature
    target: One creature or object
    tier1: 2 + R damage; M < WEAK[, prone](../../../../condition/prone.md)
    tier2: 4 + R damage; M < AVERAGE[, prone](../../../../condition/prone.md)
    tier3: 6 + R damage; M < STRONG[, prone](../../../../condition/prone.md)
    type: ability
name: Optic Blast
target: One creature or object
type: feature
usage: Main action
```
