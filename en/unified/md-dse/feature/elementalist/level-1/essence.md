---
action_type: feature
class: elementalist
feature_type: feature
file_basename: essence
file_dpath: feature/elementalist/level-1
item_id: essence
item_name: Essence
level: "1"
name: Essence
scc: mcdm.heroes.v1/feature.elementalist.level-1/essence
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        You channel the substance of creation in the form of a [Heroic Resource](scc.v1:mcdm.heroes.v1/rule.resource/heroic-resource) called essence, gathering and burning it to cast and maintain spells.

        ##### Essence in Combat

        At the start of a combat encounter or some other stressful situation tracked in [combat rounds](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) (as determined by the Director), you gain essence equal to your [Victories](scc.v1:mcdm.heroes.v1/rule.resource/victories). At the start of each of your [turns](scc.v1:mcdm.heroes.v1/rule.combat/turn) during combat, you gain 2 essence.

        Additionally, the first time each [combat round](scc.v1:mcdm.heroes.v1/rule.combat/combat-round) that you or a creature within 10 squares takes damage that isn't untyped or holy damage, you gain 1 essence.

        You lose any remaining essence at the end of the encounter.

        ##### Essence Outside of Combat

        Though you can't gain essence outside of combat, you can use your [heroic abilities](scc.v1:mcdm.heroes.v1/rule.general/heroic-ability) and effects that cost essence without spending it. Whenever you use an ability or effect outside of combat that costs essence, you can't use that same ability or effect outside of combat again until you earn 1 or more [Victories](scc.v1:mcdm.heroes.v1/rule.resource/victories) or finish a [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite).

        When you use a persistent ability outside of combat (see [Persistent Magic](scc.v1:mcdm.heroes.v1/feature.elementalist.level-1/persistent-magic) below), you can maintain it for a number of rounds equal to your [Victories](scc.v1:mcdm.heroes.v1/rule.resource/victories).

        When you use an ability outside of combat that lets you spend unlimited essence on its effect, you can use it as if you had spent an amount of essence equal to your [Victories](scc.v1:mcdm.heroes.v1/rule.resource/victories).
feature_type: feature
metadata:
    class: elementalist
    level: "1"
    name: Essence
    scc: mcdm.heroes.v1/feature.elementalist.level-1/essence
    type: feature
name: Essence
type: feature
```
