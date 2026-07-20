---
disengage_bonus: "+1"
equipment_text: You wear no armor and wield a bow.
file_basename: sniper
file_dpath: kit
flavor: The Sniper kit gives you the tools and techniques to take down enemies from afar. This kit can help you become the archer who lurks behind trees or down tunnels, picking off enemies with a bow or crossbow as they approach.
item_id: sniper
item_name: Sniper
name: Sniper
ranged_damage_bonus: +0/+0/+4
ranged_distance_bonus: "+10"
scc: mcdm.heroes.v1/kit/sniper
source: mcdm.heroes.v1
speed_bonus: "+1"
type: kit
---

The [Sniper](scc.v1:mcdm.heroes.v1/kit/sniper) kit gives you the tools and techniques to take down enemies from afar. This kit can help you become the archer who lurks behind trees or down tunnels, picking off enemies with a bow or crossbow as they approach.

##### Equipment

You wear no armor and wield a bow.

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 15'
effects:
    - effect: If you don't take a move action this [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals extra damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score (your choice).
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage
      tier2: 6 + M or A damage
      tier3: 13 + M or A damage
feature_type: ability
flavor: Breathe... aim... wait... then strike!
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 15'
    effect: If you don't take a move action this [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), this [strike](scc.v1:mcdm.heroes.v1/rule.combat/strike) deals extra damage equal to your [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility) score (your choice).
    flavor: Breathe... aim... wait... then strike!
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Patient Shot
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage
    tier2: 6 + M or A damage
    tier3: 13 + M or A damage
    type: ability
name: Patient Shot
target: One creature
type: feature
usage: Main action
```
