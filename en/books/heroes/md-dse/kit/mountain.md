---
equipment_text: You wear heavy armor and wield a heavy weapon.
file_basename: mountain
file_dpath: kit
flavor: The Mountain kit does exactly what it says on the tin. You don heavy armor and raise a heavy weapon to stand strong against your foes, quickly demolishing them when it's your turn to strike.
item_id: mountain
item_name: Mountain
melee_damage_bonus: +0/+0/+4
name: Mountain
scc: mcdm.heroes.v1/kit/mountain
source: mcdm.heroes.v1
stability_bonus: "+2"
stamina_bonus: +9 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

The [Mountain](scc.v1:mcdm.heroes.v1/kit/mountain) kit does exactly what it says on the tin. You don heavy armor and raise a heavy weapon to stand strong against your foes, quickly demolishing them when it's your turn to strike.

##### Equipment

You wear heavy armor and wield a heavy weapon.

```ds-feature
distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage
      tier2: 5 + M or A damage
      tier3: 13 + M or A damage
    - effect: If the target dealt damage to you since the end of your last [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals additional damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score (your choice).
      name: Effect
feature_type: ability
flavor: An enemy who tagged you will pay for that.
keywords:
    - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) 1'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 3 + M or A damage
          tier2: 5 + M or A damage
          tier3: 13 + M or A damage
        - effect: If the target dealt damage to you since the end of your last [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals additional damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score (your choice).
          name: Effect
    flavor: An enemy who tagged you will pay for that.
    keywords:
        - '[Melee](scc.v1:mcdm.heroes.v1/rule.combat/melee)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Pain for Pain
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 5 + M or A damage
    tier3: 13 + M or A damage
    type: ability
name: Pain for Pain
target: One creature
type: feature
usage: Main action
```
