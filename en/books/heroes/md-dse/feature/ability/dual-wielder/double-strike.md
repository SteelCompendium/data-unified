---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 damage
      tier2: 6 damage
      tier3: 8 damage
    - effect: If you use this ability on your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can use it against one target, then use your maneuver and your move action for that [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) before using the ability against a second target. You still use the same [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) for both targets.
      name: Effect
feature_type: ability
file_basename: double-strike
file_dpath: feature/ability/dual-wielder
flavor: Why strike once when you could do it twice?
item_id: double-strike
item_name: Double Strike
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: dual-wielder
name: Double Strike
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
scc: mcdm.heroes.v1/feature.ability.dual-wielder/double-strike
source: mcdm.heroes.v1
subtype: signature
target: Two creatures or objects
tier1: 4 damage
tier2: 6 damage
tier3: 8 damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 4 damage
      tier2: 6 damage
      tier3: 8 damage
    - effect: If you use this ability on your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can use it against one target, then use your maneuver and your move action for that [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) before using the ability against a second target. You still use the same [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) for both targets.
      name: Effect
feature_type: ability
flavor: Why strike once when you could do it twice?
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 4 damage
          tier2: 6 damage
          tier3: 8 damage
        - effect: If you use this ability on your [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), you can use it against one target, then use your maneuver and your move action for that [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn) before using the ability against a second target. You still use the same [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) for both targets.
          name: Effect
    flavor: Why strike once when you could do it twice?
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: dual-wielder
    name: Double Strike
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    scc: mcdm.heroes.v1/feature.ability.dual-wielder/double-strike
    subtype: signature
    target: Two creatures or objects
    tier1: 4 damage
    tier2: 6 damage
    tier3: 8 damage
    type: ability
name: Double Strike
target: Two creatures or objects
type: feature
usage: Main action
```
