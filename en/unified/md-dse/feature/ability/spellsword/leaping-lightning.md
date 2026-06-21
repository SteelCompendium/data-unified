---
action_type: Main action
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effect: A creature or object of your choice within 2 squares of the target takes lightning damage equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
feature_type: ability
file_basename: leaping-lightning
file_dpath: feature/ability/spellsword
flavor: Lightning jumps from your weapon as you strike to harm a nearby foe.
item_id: leaping-lightning
item_name: Leaping Lightning
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
kit: spellsword
name: Leaping Lightning
power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
scc: mcdm.heroes.v1/feature.ability.spellsword/leaping-lightning
source: mcdm.heroes.v1
subtype: signature
target: One creature or object
tier1: 5 + M, R, I, or P lightning damage
tier2: 8 + M, R, I, or P lightning damage
tier3: 11 + M, R, I, or P lightning damage
type: ability
---

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - effect: A creature or object of your choice within 2 squares of the target takes lightning damage equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)
      tier1: 5 + M, R, I, or P lightning damage
      tier2: 8 + M, R, I, or P lightning damage
      tier3: 11 + M, R, I, or P lightning damage
feature_type: ability
flavor: Lightning jumps from your weapon as you strike to harm a nearby foe.
keywords:
    - Magic
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effect: A creature or object of your choice within 2 squares of the target takes lightning damage equal to the [characteristic](scc.v1:mcdm.heroes.v1/rule.character/characteristic) score used for this ability's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
    flavor: Lightning jumps from your weapon as you strike to harm a nearby foe.
    keywords:
        - Magic
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    kit: spellsword
    name: Leaping Lightning
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
    scc: mcdm.heroes.v1/feature.ability.spellsword/leaping-lightning
    subtype: signature
    target: One creature or object
    tier1: 5 + M, R, I, or P lightning damage
    tier2: 8 + M, R, I, or P lightning damage
    tier3: 11 + M, R, I, or P lightning damage
    type: ability
name: Leaping Lightning
target: One creature or object
type: feature
usage: Main action
```
