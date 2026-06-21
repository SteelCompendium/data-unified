---
action_type: feature
class: summoner
feature_source: summoner
feature_type: feature
file_basename: basics
file_dpath: feature/summoner/level-1
item_id: basics
item_name: Basics
level: "1"
name: Basics
scc: mcdm.summoner.v1/feature.summoner.level-1/basics
source: mcdm.summoner.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        **Starting Characteristics:** You start with a [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) of 2, and you can choose one of the following arrays for your other [characteristics](scc.v1:mcdm.heroes.v1/rule.character/characteristic) scores:

        - 2, 2, -1, -1
        - 2, 1, 1, -1
        - 2, 1, 0, 0
        - 1, 1, 1, 0

        **Weak [Potency](scc.v1:mcdm.heroes.v1/rule.character/potency):** [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) - 2

        **Average [Potency](scc.v1:mcdm.heroes.v1/rule.character/potency):** [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) - 1

        **Strong [Potency](scc.v1:mcdm.heroes.v1/rule.character/potency):** [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason)

        **Starting [Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) at 1st Level:** 15

        **[Stamina](scc.v1:mcdm.heroes.v1/rule.health/stamina) Gained at 2nd and Higher Levels:** 6

        **[Recoveries](scc.v1:mcdm.heroes.v1/rule.health/recoveries):** 8

        **Skills:** You gain the [Magic](scc.v1:mcdm.heroes.v1/skill.lore/magic) and [Strategy](scc.v1:mcdm.heroes.v1/skill.lore/strategy) skills and can choose any two skills from the [intrigue](scc.v1:mcdm.heroes.v1/skill.group/intrigue) or [lore](scc.v1:mcdm.heroes.v1/skill.group/lore) skill groups. (*Quick Build:* [Eavesdrop](scc.v1:mcdm.heroes.v1/skill.intrigue/eavesdrop), [Magic](scc.v1:mcdm.heroes.v1/skill.lore/magic), [Monsters](scc.v1:mcdm.heroes.v1/skill.lore/monsters), [Strategy](scc.v1:mcdm.heroes.v1/skill.lore/strategy).)

        ###### Summoner Advancement

        | Level | Summoner Features                                                                                                  | Circle Features                              | Minions           | Abilities  |
        |-------|--------------------------------------------------------------------------------------------------------------------|----------------------------------------------|-------------------|------------|
        | 1st | [Minions](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minions), [Essence](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/essence), [Summoner Strike](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/summoner-strike), [Strike For Me](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/strike-for-me), [Minion Bridge](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/minion-bridge), [Formation](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/formation), [Quick Command](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/quick-command), [Summoner Abilities](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/summoner-abilities) | [Summoner Circle](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/summoner-circle), [Circle Features](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/1st-level-circle-features), [Portfolio](scc.v1:mcdm.summoner.v1/feature.summoner.level-1/portfolio) | 1, 1, 3, 3 | 5 |
        | 2nd | [Perk](scc.v1:mcdm.summoner.v1/feature.summoner.level-2/perk) | [Summoner's Dominion](scc.v1:mcdm.summoner.v1/feature.summoner.level-2/summoners-dominion), [New Portfolio Minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-2/new-portfolio-minion) | 1, 1, 3, 3, 5 | 5 |
        | 3rd | [Summoner's Kit](scc.v1:mcdm.summoner.v1/feature.summoner.level-3/summoners-kit), [7-Essence Ability](scc.v1:mcdm.summoner.v1/feature.summoner.level-3/7-essence-ability) | — | 1, 1, 3, 3, 5 | 5, 7 |
        | 4th | [Characteristic Increase](scc.v1:mcdm.summoner.v1/feature.summoner.level-4/characteristic-increase), [Minion Improvement](scc.v1:mcdm.summoner.v1/feature.summoner.level-4/minion-improvement), [Essence Salvage](scc.v1:mcdm.summoner.v1/feature.summoner.level-4/essence-salvage), [Minion Chain](scc.v1:mcdm.summoner.v1/feature.summoner.level-4/minion-chain), [Perk](scc.v1:mcdm.summoner.v1/feature.summoner.level-4/perk), [Skill](scc.v1:mcdm.summoner.v1/feature.summoner.level-4/skill) | — | 1, 1, 3, 3, 5 | 5, 7 |
        | 5th | — | [Circle Feature](scc.v1:mcdm.summoner.v1/feature.summoner.level-5/5th-level-circle-feature), [New Portfolio Minion](scc.v1:mcdm.summoner.v1/feature.summoner.level-5/new-portfolio-minion) | 1, 1, 3, 3, 5, 7 | 5, 7 |
        | 6th | [Perk](scc.v1:mcdm.summoner.v1/feature.summoner.level-6/perk), [Minion Machinations](scc.v1:mcdm.summoner.v1/feature.summoner.level-6/minion-machinations), [Kit Improvement](scc.v1:mcdm.summoner.v1/feature.summoner.level-6/kit-improvement), [9-Essence Ability](scc.v1:mcdm.summoner.v1/feature.summoner.level-6/9-essence-ability) | [Return to the Source](scc.v1:mcdm.summoner.v1/feature.summoner.level-6/return-to-the-source) | 1, 1, 3, 3, 5, 7 | 5, 7, 9 |
        | 7th | [Characteristic Increase](scc.v1:mcdm.summoner.v1/feature.summoner.level-7/characteristic-increase), [Minion Improvement](scc.v1:mcdm.summoner.v1/feature.summoner.level-7/minion-improvement), [Font of Creation](scc.v1:mcdm.summoner.v1/feature.summoner.level-7/font-of-creation), [Their Life for Mine](scc.v1:mcdm.summoner.v1/feature.summoner.level-7/their-life-for-mine), [Skill](scc.v1:mcdm.summoner.v1/feature.summoner.level-7/skill) | — | 1, 1, 3, 3, 5, 7 | 5, 7, 9 |
        | 8th | [Perk](scc.v1:mcdm.summoner.v1/feature.summoner.level-8/perk) | [Circle Feature](scc.v1:mcdm.summoner.v1/feature.summoner.level-8/8th-level-circle-feature), [Portfolio Champion](scc.v1:mcdm.summoner.v1/feature.summoner.level-8/portfolio-champion) | 1, 1, 3, 3, 5, 7, 9 | 5, 7, 9 |
        | 9th | [Kit Improvement](scc.v1:mcdm.summoner.v1/feature.summoner.level-9/kit-improvement), [Steward of Two Worlds](scc.v1:mcdm.summoner.v1/feature.summoner.level-9/steward-of-two-worlds), [11-Essence Ability](scc.v1:mcdm.summoner.v1/feature.summoner.level-9/11-essence-ability) | — | 1, 1, 3, 3, 5, 7, 9 | 5, 7, 9, 11 |
        | 10th | [Characteristic Increase](scc.v1:mcdm.summoner.v1/feature.summoner.level-10/characteristic-increase), [Minion Improvement](scc.v1:mcdm.summoner.v1/feature.summoner.level-10/minion-improvement), [Eidos](scc.v1:mcdm.summoner.v1/feature.summoner.level-10/eidos), [No Matter the Cost](scc.v1:mcdm.summoner.v1/feature.summoner.level-10/no-matter-the-cost), [Among Our Ranks](scc.v1:mcdm.summoner.v1/feature.summoner.level-10/among-our-ranks), [Perk](scc.v1:mcdm.summoner.v1/feature.summoner.level-10/perk), [Skill](scc.v1:mcdm.summoner.v1/feature.summoner.level-10/skill) | — | 1, 1, 3, 3, 5, 7, 9 | 5, 7, 9, 11 |
feature_type: feature
metadata:
    class: summoner
    feature_source: summoner
    level: "1"
    name: Basics
    scc: mcdm.summoner.v1/feature.summoner.level-1/basics
    type: feature
name: Basics
type: feature
```
