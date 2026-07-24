---
action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
class: censor
cost: 5 Wrath
cost_amount: "5"
cost_resource: Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 8 + M holy damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 15 + M holy damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    - effect: If the target is already [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
      name: Effect
feature_type: ability
file_basename: it-is-justice-you-fear
file_dpath: feature/ability/censor/level-2
flavor: I am but a vessel. Your own deeds weigh upon you.
item_id: it-is-justice-you-fear
item_name: It Is Justice You Fear
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
level: "2"
name: It Is Justice You Fear
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.censor.level-2/it-is-justice-you-fear
source: mcdm.heroes.v1
subclass: exorcist
target: One creature
tier1: 8 + M holy damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
tier3: 15 + M holy damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
type: ability
---

```ds-feature
cost: 5 Wrath
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: 8 + M holy damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
      tier3: 15 + M holy damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    - effect: If the target is already [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
      name: Effect
feature_type: ability
flavor: I am but a vessel. Your own deeds weigh upon you.
keywords:
    - Magic
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
metadata:
    action_type: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
    class: censor
    cost: 5 Wrath
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
          tier1: 8 + M holy damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
          tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
          tier3: 15 + M holy damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
        - effect: If the target is already [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you or another creature and this ability would frighten them again, they instead take psychic damage equal to twice your [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence) score.
          name: Effect
    flavor: I am but a vessel. Your own deeds weigh upon you.
    keywords:
        - Magic
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    level: "2"
    name: It Is Justice You Fear
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.censor.level-2/it-is-justice-you-fear
    subclass: exorcist
    target: One creature
    tier1: 8 + M holy damage; P < WEAK, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier2: 12 + M holy damage; P < AVERAGE, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    tier3: 15 + M holy damage; P < STRONG, [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) (save ends)
    type: ability
name: It Is Justice You Fear
target: One creature
type: feature
usage: '[Main action](scc.v1:mcdm.heroes.v1/rule.combat/turn)'
```
