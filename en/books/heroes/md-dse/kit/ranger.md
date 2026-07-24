---
disengage_bonus: "+1"
equipment_text: You wear medium armor and wield a bow and a medium weapon.
file_basename: ranger
file_dpath: kit
flavor: The Ranger kit outfits you with medium armor and weapons for every challenge, letting you easily switch between melee and ranged combat. This kit provides a good balance of bonuses to defense and offense to create a hero who is a jack-of-all-trades.
item_id: ranger
item_name: Ranger
melee_damage_bonus: +1/+1/+1
name: Ranger
ranged_damage_bonus: +1/+1/+1
ranged_distance_bonus: "+5"
scc: mcdm.heroes.v1/kit/ranger
source: mcdm.heroes.v1
speed_bonus: "+1"
stamina_bonus: +6 per [echelon](scc.v1:mcdm.heroes.v1/rule.general/echelon)
type: kit
---

The [Ranger](scc.v1:mcdm.heroes.v1/kit/ranger) kit outfits you with medium armor and weapons for every challenge, letting you easily switch between [melee](scc.v1:mcdm.heroes.v1/rule.combat/melee) and [ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) combat. This kit provides a good balance of [bonus](scc.v1:mcdm.heroes.v1/rule.dice/bonuses-and-penalties)es to defense and offense to create a hero who is a jack-of-all-trades.

##### Equipment

You wear medium armor and wield a bow and a medium weapon.

```ds-feature
distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
effects:
    - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
      tier1: 3 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier2: 5 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
      tier3: 7 + M or A damage; A < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
feature_type: ability
flavor: A well-placed shot leaves your enemy struggling to move.
keywords:
    - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
    - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
    - Weapon
metadata:
    action_type: Main action
    distance: '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged) 10'
    effects:
        - roll: Power Roll + [Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)
          tier1: 3 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier2: 5 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
          tier3: 7 + M or A damage; A < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    flavor: A well-placed shot leaves your enemy struggling to move.
    keywords:
        - '[Ranged](scc.v1:mcdm.heroes.v1/rule.combat/ranged)'
        - '[Strike](scc.v1:mcdm.heroes.v1/rule.combat/strike)'
        - Weapon
    name: Hamstring Shot
    power_roll_characteristic: '[Might](scc.v1:mcdm.heroes.v1/rule.character/might) or [Agility](scc.v1:mcdm.heroes.v1/rule.character/agility)'
    subtype: signature
    target: One creature
    tier1: 3 + M or A damage; A < WEAK, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier2: 5 + M or A damage; A < AVERAGE, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    tier3: 7 + M or A damage; A < STRONG, [slowed](scc.v1:mcdm.heroes.v1/condition/slowed) (save ends)
    type: ability
name: Hamstring Shot
target: One creature
type: feature
usage: Main action
```
