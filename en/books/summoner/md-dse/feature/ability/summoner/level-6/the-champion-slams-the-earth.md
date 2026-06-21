---
action_type: Main action
class: summoner
distance: 4 cube within 1
effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
feature_source: summoner
feature_type: ability
file_basename: the-champion-slams-the-earth
file_dpath: feature/ability/summoner/level-6
flavor: Your champion lays their fury upon those unfortunate enough to be in their wake.
item_id: the-champion-slams-the-earth
item_name: The Champion Slams the Earth
keywords:
    - Area
    - Champion
    - Magic
    - Weapon
level: "6"
name: The Champion Slams the Earth
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.summoner.v1/feature.ability.summoner.level-6/the-champion-slams-the-earth
source: mcdm.summoner.v1
target: Each enemy and object in the area
tier1: 5 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
tier2: 8 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
tier3: 11 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
type: ability
---

```ds-feature
distance: 4 cube within 1
effects:
    - effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 5 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
      tier2: 8 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
      tier3: 11 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
feature_type: ability
flavor: Your champion lays their fury upon those unfortunate enough to be in their wake.
keywords:
    - Area
    - Champion
    - Magic
    - Weapon
metadata:
    action_type: Main action
    class: summoner
    distance: 4 cube within 1
    effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
    feature_source: summoner
    flavor: Your champion lays their fury upon those unfortunate enough to be in their wake.
    keywords:
        - Area
        - Champion
        - Magic
        - Weapon
    level: "6"
    name: The Champion Slams the Earth
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.summoner.v1/feature.ability.summoner.level-6/the-champion-slams-the-earth
    target: Each enemy and object in the area
    tier1: 5 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < WEAK [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
    tier2: 8 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < AVERAGE [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
    tier3: 11 [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); M < STRONG [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
    type: ability
name: The Champion Slams the Earth
target: Each enemy and object in the area
type: feature
usage: Main action
```
