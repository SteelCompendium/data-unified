---
action_type: Main action
class: summoner
distance: 3 burst
effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
feature_source: summoner
feature_type: ability
file_basename: a-champions-cry
file_dpath: feature/ability/summoner/level-6
flavor: Your champion unleashes a bellow that shakes you to your core.
item_id: a-champions-cry
item_name: A Champion's Cry
keywords:
    - Area
    - Champion
    - Magic
level: "6"
name: A Champion's Cry
power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
scc: mcdm.summoner.v1/feature.ability.summoner.level-6/a-champions-cry
source: mcdm.summoner.v1
target: Each enemy in the area
tier1: 2 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
tier2: 5 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you and all allies ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
tier3: 7 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you and all allies ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
type: ability
---

```ds-feature
distance: 3 burst
effects:
    - effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
    - roll: Power Roll + [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)
      tier1: 2 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
      tier2: 5 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you and all allies ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
      tier3: 7 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you and all allies ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
feature_type: ability
flavor: Your champion unleashes a bellow that shakes you to your core.
keywords:
    - Area
    - Champion
    - Magic
metadata:
    action_type: Main action
    class: summoner
    distance: 3 burst
    effect: You can use this ability as if in the space of one of your minions within your Summoner's Range.
    feature_source: summoner
    flavor: Your champion unleashes a bellow that shakes you to your core.
    keywords:
        - Area
        - Champion
        - Magic
    level: "6"
    name: A Champion's Cry
    power_roll_characteristic: '[Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)'
    scc: mcdm.summoner.v1/feature.ability.summoner.level-6/a-champions-cry
    target: Each enemy in the area
    tier1: 2 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < WEAK [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
    tier2: 5 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < AVERAGE [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you and all allies ([EoT](scc.v1:mcdm.heroes.v1/rule.combat/end-of-turn))
    tier3: 7 psychic or sonic [damage](scc.v1:mcdm.heroes.v1/rule.damage/damage); I < STRONG [frightened](scc.v1:mcdm.heroes.v1/condition/frightened) of you and all allies ([save ends](scc.v1:mcdm.heroes.v1/rule.general/saving-throw))
    type: ability
name: A Champion's Cry
target: Each enemy in the area
type: feature
usage: Main action
```
