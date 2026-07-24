---
action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
class: tactician
cost: 5 Focus
cost_amount: "5"
cost_resource: Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: You move up to your [speed](../../../../rule/character/speed.md) toward the triggering ally, ending this movement [adjacent](../../../../rule/combat/adjacent.md) to them or in the nearest square if you can't reach an [adjacent](../../../../rule/combat/adjacent.md) square. The triggering ally can spend a [Recovery](../../../../rule/health/recoveries.md) and gains 5 [temporary Stamina](../../../../rule/health/temporary-stamina.md) for each enemy you came [adjacent](../../../../rule/combat/adjacent.md) to during the move. You then make a [power roll](../../../../rule/dice/power-roll.md) against the target.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: R < WEAK, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
      tier2: R < AVERAGE, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
      tier3: R < STRONG, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
feature_type: ability
file_basename: no-dying-on-my-watch
file_dpath: feature/ability/tactician/level-2
flavor: You prioritize saving an ally over your own safety.
item_id: no-dying-on-my-watch
item_name: No Dying on My Watch
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
level: "2"
name: No Dying on My Watch
power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
scc: mcdm.heroes.v1/feature.ability.tactician.level-2/no-dying-on-my-watch
source: mcdm.heroes.v1
subclass: vanguard
subtype: triggered
target: One enemy
tier1: R < WEAK, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
tier2: R < AVERAGE, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
tier3: R < STRONG, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
trigger: The target deals damage to an ally.
type: ability
---

```ds-feature
cost: 5 Focus
distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
effects:
    - effect: You move up to your [speed](../../../../rule/character/speed.md) toward the triggering ally, ending this movement [adjacent](../../../../rule/combat/adjacent.md) to them or in the nearest square if you can't reach an [adjacent](../../../../rule/combat/adjacent.md) square. The triggering ally can spend a [Recovery](../../../../rule/health/recoveries.md) and gains 5 [temporary Stamina](../../../../rule/health/temporary-stamina.md) for each enemy you came [adjacent](../../../../rule/combat/adjacent.md) to during the move. You then make a [power roll](../../../../rule/dice/power-roll.md) against the target.
      name: Effect
    - roll: Power Roll + [Might](../../../../rule/character/might.md)
      tier1: R < WEAK, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
      tier2: R < AVERAGE, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
      tier3: R < STRONG, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
feature_type: ability
flavor: You prioritize saving an ally over your own safety.
keywords:
    - '[Ranged](../../../../rule/combat/ranged.md)'
    - '[Strike](../../../../rule/combat/strike.md)'
    - Weapon
metadata:
    action_type: '[Triggered](../../../../rule/combat/triggered-action.md)'
    class: tactician
    cost: 5 Focus
    distance: '[Ranged](../../../../rule/combat/ranged.md) 5'
    effects:
        - effect: You move up to your [speed](../../../../rule/character/speed.md) toward the triggering ally, ending this movement [adjacent](../../../../rule/combat/adjacent.md) to them or in the nearest square if you can't reach an [adjacent](../../../../rule/combat/adjacent.md) square. The triggering ally can spend a [Recovery](../../../../rule/health/recoveries.md) and gains 5 [temporary Stamina](../../../../rule/health/temporary-stamina.md) for each enemy you came [adjacent](../../../../rule/combat/adjacent.md) to during the move. You then make a [power roll](../../../../rule/dice/power-roll.md) against the target.
          name: Effect
        - roll: Power Roll + [Might](../../../../rule/character/might.md)
          tier1: R < WEAK, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
          tier2: R < AVERAGE, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
          tier3: R < STRONG, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
    flavor: You prioritize saving an ally over your own safety.
    keywords:
        - '[Ranged](../../../../rule/combat/ranged.md)'
        - '[Strike](../../../../rule/combat/strike.md)'
        - Weapon
    level: "2"
    name: No Dying on My Watch
    power_roll_characteristic: '[Might](../../../../rule/character/might.md)'
    scc: mcdm.heroes.v1/feature.ability.tactician.level-2/no-dying-on-my-watch
    subclass: vanguard
    subtype: triggered
    target: One enemy
    tier1: R < WEAK, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
    tier2: R < AVERAGE, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
    tier3: R < STRONG, the target is [frightened](../../../../condition/frightened.md) of the triggering ally (save ends)
    trigger: The target deals damage to an ally.
    type: ability
name: No Dying on My Watch
target: One enemy
trigger: The target deals damage to an ally.
type: feature
usage: '[Triggered](../../../../rule/combat/triggered-action.md)'
```
