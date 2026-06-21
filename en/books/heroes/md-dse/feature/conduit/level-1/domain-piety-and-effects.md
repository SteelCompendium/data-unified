---
action_type: feature
class: conduit
feature_type: feature
file_basename: domain-piety-and-effects
file_dpath: feature/conduit/level-1
item_id: domain-piety-and-effects
item_name: Domain Piety and Effects
level: "1"
name: Domain Piety and Effects
scc: mcdm.heroes.v1/feature.conduit.level-1/domain-piety-and-effects
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        Your choice of domains provides you with two additional ways to earn piety during combat, as triggered by specific events. You might even have a single event trigger both your piety effects. For example, the Sun domain grants piety when a nearby creature takes fire or holy damage, while the War domain grants piety when a nearby creature takes damage of 10 + your level or higher. If you have both those domains and a nearby creature takes an appropriate amount of fire damage, you gain piety from both your domains.

        Additionally, whenever you activate a domain effect by praying for piety, you can choose one of your domains and have that domain's prayer effect take effect immediately.

        ###### Creation Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that a creature within 10 squares uses an area ability.
        - **Prayer Effect:** You summon the forces of creation and create a wall of stone within 10 squares whose [size](scc.v1:mcdm.heroes.v1/rule.character/size) is 5 + your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. The wall lasts until the end of the encounter.

        ###### Death Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that a creature within 10 squares who isn't a minion is reduced to 0 [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina), or the first time in an encounter that a solo creature within 10 squares becomes [winded](scc.v1:mcdm.heroes.v1/rule.health/winded).
        - **Prayer Effect:** You inflict a deadly curse on up to two enemies within 10 squares of you. Each target takes corruption damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.

        ###### Fate Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that an ally within 10 squares obtains a tier 3 outcome on a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll), or an enemy within 10 squares obtains a tier 1 outcome on a [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
        - **Prayer Effect:** You call on the forces of fate to create a reliable future. Choose a creature within 10 squares. That creature automatically obtains a tier 1 or tier 3 outcome (your choice) on their next [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll) made before the end of the encounter.

        ###### Knowledge Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that the Director spends Malice (see *Draw Steel: Monsters*).
        - **Prayer Effect:** Choose up to five allies within 10 squares of you, or choose yourself instead of one ally. Each target gains 1 [surge](scc.v1:mcdm.heroes.v1/rule.resource/surge).

        ###### Life Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that a creature within 10 squares regains [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina).
        - **Prayer Effect:** Choose yourself or one ally within 10 squares. That character can spend a [Recovery](scc.v1:mcdm.heroes.v1/rule.health/recoveries), can end one effect on them that is ended by a [saving throw](scc.v1:mcdm.heroes.v1/rule.general/saving-throw) or that ends at the end of their [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn), or can stand up if they [are prone](scc.v1:mcdm.heroes.v1/condition/prone). Alternatively, you or one ally within 10 squares gains [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to two times your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.

        ###### Love Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that you or any ally within 10 squares uses the [Aid Attack](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/aid-attack) maneuver or an ability that targets an ally.
        - **Prayer Effect:** Each ally within 10 squares of you gains [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to two times your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.

        ###### Nature Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that you or a creature within 10 squares takes acid, cold, fire, lightning, poison, or sonic damage.
        - **Prayer Effect:** Vines whip up from the floor or ground within 10 squares, wrapping around a number of creatures equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. You can [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) each creature up to a number of squares equal to your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score. The vines then fade away.

        ###### Protection Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that you or any ally within 10 squares gains [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina), or uses a [triggered action](scc.v1:mcdm.heroes.v1/feature.conduit.level-1/triggered-action) to reduce incoming damage or to impose a [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) or double [bane](scc.v1:mcdm.heroes.v1/rule.dice/bane) on an enemy's [power roll](scc.v1:mcdm.heroes.v1/rule.dice/power-roll).
        - **Prayer Effect:** One ally within 10 squares gains [temporary Stamina](scc.v1:mcdm.heroes.v1/rule.health/temporary-stamina) equal to four times your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.

        ###### Storm Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that an enemy within 10 squares is [force moved](scc.v1:mcdm.heroes.v1/movement/forced-movement).
        - **Prayer Effect:** Each enemy in a 3 [cube](scc.v1:mcdm.heroes.v1/rule.combat/cube) within 10 squares takes lightning damage equal to twice your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.

        ###### Sun Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that an enemy within 10 squares takes fire or holy damage.
        - **Prayer Effect:** One enemy within 10 squares takes fire damage equal to three times your [Intuition](scc.v1:mcdm.heroes.v1/rule.character/intuition) score.

        ###### Trickery Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that you or a creature within 10 squares takes the [Aid Attack](scc.v1:mcdm.heroes.v1/feature.common.maneuvers/aid-attack) or [Hide](scc.v1:mcdm.heroes.v1/skill.intrigue/hide) maneuver.
        - **Prayer Effect:** You [slide](scc.v1:mcdm.heroes.v1/movement/forced-movement) one creature within 10 squares of you up to a number of squares equal to 5 + your [conduit](scc.v1:mcdm.heroes.v1/class/conduit) level.

        ###### War Domain Piety and Effect

        - **Piety:** You gain 2 piety the first time in an encounter that you or a creature within 10 squares takes damage greater than 10 + your level in a single [turn](scc.v1:mcdm.heroes.v1/rule.combat/turn).
        - **Prayer Effect:** Choose up to three allies within 10 squares of you, or choose yourself instead of one ally. Each target gains 2 [surges](scc.v1:mcdm.heroes.v1/rule.resource/surge).
feature_type: feature
metadata:
    class: conduit
    level: "1"
    name: Domain Piety and Effects
    scc: mcdm.heroes.v1/feature.conduit.level-1/domain-piety-and-effects
    type: feature
name: Domain Piety and Effects
type: feature
```
