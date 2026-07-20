---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 3 Wrath
cost_amount: "3"
cost_resource: Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), enemies take a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) made against you or any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you.
feature_type: ability
file_basename: behold-a-shield-of-faith
file_dpath: feature/ability/censor/level-1
flavor: A mighty blow [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) your foe's vitality into a holy light that envelops you and an ally, discouraging enemies who might attack you.
item_id: behold-a-shield-of-faith
item_name: Behold a Shield of Faith!
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "1"
name: Behold a Shield of Faith!
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-1/behold-a-shield-of-faith
source: mcdm.heroes.v1
target: One creature or object
tier1: 3 + M holy damage
tier2: 6 + M holy damage
tier3: 9 + M holy damage
type: ability
---

```ds-feature
cost: 3 Wrath
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), enemies take a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) made against you or any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 3 + M holy damage
      tier2: 6 + M holy damage
      tier3: 9 + M holy damage
feature_type: ability
flavor: A mighty blow [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) your foe's vitality into a holy light that envelops you and an ally, discouraging enemies who might attack you.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 3 Wrath
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Until the start of your next [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), enemies take a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) made against you or any ally [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to you.
    flavor: A mighty blow [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) your foe's vitality into a holy light that envelops you and an ally, discouraging enemies who might attack you.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "1"
    name: Behold a Shield of Faith!
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-1/behold-a-shield-of-faith
    target: One creature or object
    tier1: 3 + M holy damage
    tier2: 6 + M holy damage
    tier3: 9 + M holy damage
    type: ability
name: Behold a Shield of Faith!
target: One creature or object
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
