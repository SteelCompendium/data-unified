---
action_type: Main action
class: fury
cost: 11 Ferocity
cost_amount: "11"
cost_resource: Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: Each enemy within 5 squares of you is distracted until the end of the round. While a creature is distracted this way, they can't take [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) or free [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) made against them gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge), and their [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) scores are considered 1 lower for the purpose of resisting [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency).
feature_type: ability
file_basename: shower-of-blood
file_dpath: feature/ability/fury/level-9
flavor: You shock your foes with the brutality of your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), resetting the balance of combat.
item_id: shower-of-blood
item_name: Shower of Blood
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "9"
name: Shower of Blood
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.fury.level-9/shower-of-blood
source: mcdm.heroes.v1
target: One creature
tier1: 12 + M damage
tier2: 18 + M damage
tier3: 24 + M damage
type: ability
---

```ds-feature
cost: 11 Ferocity
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: Each enemy within 5 squares of you is distracted until the end of the round. While a creature is distracted this way, they can't take [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) or free [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) made against them gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge), and their [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) scores are considered 1 lower for the purpose of resisting [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 12 + M damage
      tier2: 18 + M damage
      tier3: 24 + M damage
feature_type: ability
flavor: You shock your foes with the brutality of your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), resetting the balance of combat.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    class: fury
    cost: 11 Ferocity
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: Each enemy within 5 squares of you is distracted until the end of the round. While a creature is distracted this way, they can't take [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action) or free [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action), [ability rolls](scc.v1:mcdm.heroes.v1/rule.dice/ability-roll) made against them gain an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge), and their [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) scores are considered 1 lower for the purpose of resisting [potencies](scc.v1:mcdm.heroes.v1/rule.character/potency).
    flavor: You shock your foes with the brutality of your [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike), resetting the balance of combat.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "9"
    name: Shower of Blood
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.fury.level-9/shower-of-blood
    target: One creature
    tier1: 12 + M damage
    tier2: 18 + M damage
    tier3: 24 + M damage
    type: ability
name: Shower of Blood
target: One creature
type: feature
usage: Main action
```
