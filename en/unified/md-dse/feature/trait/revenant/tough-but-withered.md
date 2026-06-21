---
action_type: feature
ancestry: revenant
feature_type: trait
file_basename: tough-but-withered
file_dpath: feature/trait/revenant
item_id: tough-but-withered
item_name: 'Signature Trait: Tough But Withered'
name: 'Signature Trait: Tough But Withered'
scc: mcdm.heroes.v1/feature.trait.revenant/tough-but-withered
source: mcdm.heroes.v1
type: trait
---

```ds-feature
effects:
    - effect: |-
        Your undead body grants you immunity to cold, corruption, lightning, and poison damage equal to your level, but you have fire weakness 5. You can't suffocate, and you don't need to eat or drink to stay alive.

        Additionally, when your [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) reaches the negative of your [winded](scc.v1:mcdm.heroes.v1/rule.health/winded) value, you become inert instead of [dying](scc.v1:mcdm.heroes.v1/rule.health/dying). You fall [prone](scc.v1:mcdm.heroes.v1/condition/prone) and can't stand. You continue to observe your surroundings, but you can't speak, take main actions, maneuvers, move actions, or [triggered actions](scc.v1:mcdm.heroes.v1/rule.combat/triggered-action). While inert this way, if you take any fire damage, your body is destroyed and you die. Otherwise, after 12 hours, you regain [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) equal to your [recovery value](scc.v1:mcdm.heroes.v1/rule.health/recoveries).

        ##### Purchased Revenant Traits

        You have 2 ancestry points to spend on the following traits, or 3 ancestry points if your [size](scc.v1:mcdm.heroes.v1/rule.character/size) is 1S. (*Quick Build:* Bloodless, plus Undead Influence if [size](scc.v1:mcdm.heroes.v1/rule.character/size) 1S.)
feature_type: trait
metadata:
    ancestry: revenant
    name: 'Signature Trait: Tough But Withered'
    scc: mcdm.heroes.v1/feature.trait.revenant/tough-but-withered
    type: trait
name: 'Signature Trait: Tough But Withered'
type: feature
```
