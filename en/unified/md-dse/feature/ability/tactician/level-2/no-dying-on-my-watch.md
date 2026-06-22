---
action_type: Triggered
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) toward the triggering ally, ending this movement [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them or in the nearest square if you can't reach an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) square. The triggering ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) and gains 5 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) for each enemy you came [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during the move. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target.
feature_type: ability
file_basename: no-dying-on-my-watch
file_dpath: feature/ability/tactician/level-2
flavor: You prioritize saving an ally over your own safety.
item_id: no-dying-on-my-watch
item_name: No Dying on My Watch
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
level: "2"
name: No Dying on My Watch
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/no-dying-on-my-watch
source: mcdm.heroes.v1
subclass: vanguard
subtype: triggered
target: One enemy
tier1: R < WEAK, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
tier2: R < AVERAGE, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
tier3: R < STRONG, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
trigger: The target deals damage to an ally.
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
effects:
    - effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) toward the triggering ally, ending this movement [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them or in the nearest square if you can't reach an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) square. The triggering ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) and gains 5 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) for each enemy you came [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during the move. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target.
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might)
      tier1: R < WEAK, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
      tier2: R < AVERAGE, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
      tier3: R < STRONG, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
feature_type: ability
flavor: You prioritize saving an ally over your own safety.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Triggered
    class: tactician
    cost: 5 Focus
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 5'
    effect: You move up to your [speed](scc.v1:mcdm.heroes.v1/rule.character/speed) toward the triggering ally, ending this movement [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to them or in the nearest square if you can't reach an [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) square. The triggering ally can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries) and gains 5 [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) for each enemy you came [adjacent](scc.v1:mcdm.heroes.v1/rule.combat/adjacent) to during the move. You then make a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) against the target.
    flavor: You prioritize saving an ally over your own safety.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    level: "2"
    name: No Dying on My Watch
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/no-dying-on-my-watch
    subclass: vanguard
    subtype: triggered
    target: One enemy
    tier1: R < WEAK, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
    tier2: R < AVERAGE, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
    tier3: R < STRONG, the target is [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of the triggering ally (save ends)
    trigger: The target deals damage to an ally.
    type: ability
name: No Dying on My Watch
target: One enemy
trigger: The target deals damage to an ally.
type: feature
usage: Triggered
```
