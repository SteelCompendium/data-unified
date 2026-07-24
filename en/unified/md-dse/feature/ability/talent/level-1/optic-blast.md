---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: talent
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R damage; M < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 4 + R damage; M < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 6 + R damage; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - effect: When targeting an object with a solid reflective surface or a creature carrying or wearing such an object (such as a mirror, an unpainted metal shield, or shiny metal plate armor), you can target one additional creature or object within 3 squares of the first target.
      name: Effect
    - effect: You gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) that you can use immediately, and you take damage equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score that can't be reduced in any way.
      name: Strained
feature_type: ability
file_basename: optic-blast
file_dpath: feature/ability/talent/level-1
flavor: Your eyes emit rays of powerful enervating force.
item_id: optic-blast
item_name: Optic Blast
keywords:
    - Metamorphosis
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
level: "1"
name: Optic Blast
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.heroes.v1/feature.ability.talent.level-1/optic-blast
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 2 + R damage; M < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier2: 4 + R damage; M < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
tier3: 6 + R damage; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
type: ability
---

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 + R damage; M < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier2: 4 + R damage; M < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
      tier3: 6 + R damage; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    - effect: When targeting an object with a solid reflective surface or a creature carrying or wearing such an object (such as a mirror, an unpainted metal shield, or shiny metal plate armor), you can target one additional creature or object within 3 squares of the first target.
      name: Effect
    - effect: You gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) that you can use immediately, and you take damage equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score that can't be reduced in any way.
      name: Strained
feature_type: ability
flavor: Your eyes emit rays of powerful enervating force.
keywords:
    - Metamorphosis
    - Psionic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - Strike
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: talent
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
          tier1: 2 + R damage; M < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier2: 4 + R damage; M < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
          tier3: 6 + R damage; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
        - effect: When targeting an object with a solid reflective surface or a creature carrying or wearing such an object (such as a mirror, an unpainted metal shield, or shiny metal plate armor), you can target one additional creature or object within 3 squares of the first target.
          name: Effect
        - effect: You gain 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge) that you can use immediately, and you take damage equal to your [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) score that can't be reduced in any way.
          name: Strained
    flavor: Your eyes emit rays of powerful enervating force.
    keywords:
        - Metamorphosis
        - Psionic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - Strike
    level: "1"
    name: Optic Blast
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.heroes.v1/feature.ability.talent.level-1/optic-blast
    subtype: signature
    target: One creature or object
    tier1: 2 + R damage; M < WEAK[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier2: 4 + R damage; M < AVERAGE[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    tier3: 6 + R damage; M < STRONG[, prone](scc.v1:mcdm.heroes.v1/condition/prone)
    type: ability
name: Optic Blast
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
