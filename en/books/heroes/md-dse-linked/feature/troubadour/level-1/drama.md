---
action_type: feature
class: troubadour
feature_type: feature
file_basename: drama
file_dpath: feature/troubadour/level-1
item_id: drama
item_name: Drama
level: "1"
name: Drama
scc: mcdm.heroes.v1/feature.troubadour.level-1/drama
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        During battles, you are fueled by the dynamic ups, downs, and upside downs of the fray, from which you derive a [Heroic Resource](../../../rule/resource/heroic-resource.md) called drama.

        ##### Drama in Combat

        At the start of a combat encounter or some other stressful situation tracked in [combat rounds](../../../rule/combat/combat-round.md) (as determined by the Director), you gain drama equal to your [Victories](../../../rule/resource/victories.md). At the start of each of your [turns](../../../rule/combat/turn.md) during combat, you gain 1d3 drama.

        Additionally, you gain drama when certain events occur during a combat encounter:

        - The first time three or more heroes use an ability on the same [turn](../../../rule/combat/turn.md), you gain 2 drama.
        - The first time any hero is made [winded](../../../rule/health/winded.md) during the encounter, you gain 2 drama.
        - Whenever a creature within your [line of effect](../../../rule/combat/line-of-effect.md) rolls a [natural 19 or 20](../../../rule/dice/natural-19-20.md), you gain 3 drama.
        - When you or another hero dies, you gain 10 drama.

        When you are dead, you continue to gain drama during combat as long as your body is intact. If you have 30 drama during the encounter in which you died, you can come back to life with 1 [Stamina](../../../rule/health/stamina.md) and 0 drama (no action required). If you are still dead after the encounter in which you died, you can't gain drama during future encounters.

        You lose any remaining drama at the end of the encounter.

        ##### Drama Outside of Combat

        Though you can't gain drama outside of combat, you can use your [heroic abilities](../../../rule/general/heroic-ability.md) and effects that cost drama without spending it. Whenever you use an ability or effect outside of combat that costs drama, you can't use that same ability or effect outside of combat again until you earn 1 or more [Victories](../../../rule/resource/victories.md) or finish a [respite](../../../rule/resource/respite.md).

        When you use an ability outside of combat that lets you spend unlimited drama on its effect, such as [Artful Flourish](../../ability/troubadour/level-1/artful-flourish.md), you can use it as if you had spent an amount of drama equal to your [Victories](../../../rule/resource/victories.md).

        > **The Auteur [Troubadour](../../../class/troubadour.md)**
        >
        > Abilities like [Guest Star](../../ability/troubadour/level-2/guest-star.md), [Missed Cue](../level-3/missed-cue.md), and [Twist at the End](../../ability/troubadour/level-2/twist-at-the-end.md) allow the auteur to rewrite bits of what happens in the battle by temporarily removing creatures from an encounter, bringing people back to life, or causing a new ally to appear. These abilities and features are no more powerful than any other, but they're narratively different from shooting rays of fire or swinging a sword.
        >
        > This is because, uniquely among all the [subclasses](../../../rule/general/subclass.md) in *Draw Steel*, the auteur knows that the combat encounter playing out at your table is really a story being told sometime later, probably in a tavern.
        >
        > When the auteur uses these abilities, they are changing that story. They rewrite stories to make them more dramatic in the telling. What *actually* happened is a matter of some debate. Even the people who were there don't agree on exactly what took place. How people *remember* it is what's important!
        >
        > This is pretty weird, but also very fun. If it's too weird for you or your table, you could always interpret those abilities as a kind of magic. A school of conjuring that really does change the battlefield, which the auteur merely *flavors* as rewriting the story.
feature_type: feature
metadata:
    class: troubadour
    level: "1"
    name: Drama
    scc: mcdm.heroes.v1/feature.troubadour.level-1/drama
    type: feature
name: Drama
type: feature
```
