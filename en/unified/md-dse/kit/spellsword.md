---
equipment_text: You wear light armor and wield a shield and a medium weapon.
file_basename: spellsword
file_dpath: kit
flavor: The Spellsword kit combines melee strikes and a little bit of magic, letting you create a warrior who doesn't have to choose between the incantation and the blade.
item_id: spellsword
item_name: Spellsword
melee_damage_bonus: +2/+2/+2
name: Spellsword
scc: mcdm.heroes.v1/kit/spellsword
source: mcdm.heroes.v1
speed_bonus: "+1"
stability_bonus: "+1"
stamina_bonus: +6 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

The [Spellsword](scc.v1:mcdm.heroes.v1/kit/spellsword) kit combines [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) [strikes](scc.v1:mcdm.heroes.v1/rule.combat/strike) and a little bit of magic, letting you create a warrior who doesn't have to choose between the incantation and the blade.

##### Equipment

You wear light armor and wield a shield and a medium weapon.

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
    name: Leaping Lightning
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might), [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason), [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition), or [Presence](scc.v1:mcdm.heroes.v1/rule.character/presence)'
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
