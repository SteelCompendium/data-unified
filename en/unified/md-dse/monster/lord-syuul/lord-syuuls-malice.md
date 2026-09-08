---
features:
    - body: Lord Syuul projects a psionic screen over his body, preventing other creatures from treating him as an enemy until the end of his next turn.
      cost: 3 Malice
      effects:
        - effect: Lord Syuul projects a psionic screen over his body, preventing other creatures from treating him as an enemy until the end of his next turn.
      icon: "\U0001F464"
      name: Guise
    - cost: 5 Malice
      effects:
        - effect: Lord Syuul psionically plunders the minds of each creature within 2 squares of him. Each such creature makes a **Reason test**.
          tier1: 13 psychic damage; the target uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against a creature of Lord Syuul's choice
          tier2: 10 psychic damage; the target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of Lord Syuul's choice
          tier3: No effect.
      icon: ❇️
      intro: Lord Syuul psionically plunders the minds of each creature within 2 squares of him. Each such creature makes a **Reason test**.
      name: Do It for Me
      power_roll:
        tiers:
            high: No effect.
            low: 13 psychic damage; the target uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against a creature of Lord Syuul's choice
            mid: 10 psychic damage; the target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of Lord Syuul's choice
    - body: Lord Syuul takes an additional main action on his turn. He can use this feature even if he is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      effects:
        - effect: Lord Syuul takes an additional main action on his turn. He can use this feature even if he is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      icon: ☠️
      name: Solo Action
    - cost: 7 Malice
      effects:
        - effect: Lord Syuul sends out a psionic burst to completely overpower his greatest threats. He makes a **Reason test** (2d10 + 4).
          tier1: Lord Syuul has damage weakness 5.
          tier2: Lord Syuul has damage immunity 2.
          tier3: Lord Syuul has damage immunity 5.
        - effect: Once per round as a maneuver, Lord Syuul can repeat this test, replacing the previous Overpower effect.
        - effect: Whenever an Overpower effect is active, any hero who has one or more psionic abilities can use a maneuver to push back by making a **Reason test**, replacing the previous Overpower effect.
          tier1: Lord Syuul has damage immunity 5.
          tier2: Lord Syuul has damage immunity 2.
          tier3: Lord Syuul has damage weakness 5.
        - effect: The Overpower effect lasts until the end of the encounter.
      icon: "\U0001F300"
      intro: Lord Syuul sends out a psionic burst to completely overpower his greatest threats. He makes a **Reason test** (2d10 + 4).
      name: Overpower
      power_roll:
        tiers:
            high: Lord Syuul has damage immunity 5.
            low: Lord Syuul has damage weakness 5.
            mid: Lord Syuul has damage immunity 2.
      trailing: |-
        Once per round as a maneuver, Lord Syuul can repeat this test, replacing the previous Overpower effect.

        Whenever an Overpower effect is active, any hero who has one or more psionic abilities can use a maneuver to push back by making a **Reason test**, replacing the previous Overpower effect.

        The Overpower effect lasts until the end of the encounter.
file_basename: lord-syuuls-malice
file_dpath: monster/lord-syuul
flavor: At the start of Lord Syuul's turn, you can spend Malice to activate one of the following features.
item_id: lord-syuuls-malice
item_name: Lord Syuul's Malice
kind: malice
name: Lord Syuul's Malice
scc: mcdm.monsters.v1/monster.lord-syuul/lord-syuuls-malice
source: mcdm.monsters.v1
type: featureblock
---

```ds-fb
features:
    - body: Lord Syuul projects a psionic screen over his body, preventing other creatures from treating him as an enemy until the end of his next turn.
      cost: 3 Malice
      effects:
        - effect: Lord Syuul projects a psionic screen over his body, preventing other creatures from treating him as an enemy until the end of his next turn.
      icon: "\U0001F464"
      name: Guise
    - cost: 5 Malice
      effects:
        - effect: Lord Syuul psionically plunders the minds of each creature within 2 squares of him. Each such creature makes a **Reason test**.
          tier1: 13 psychic damage; the target uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against a creature of Lord Syuul's choice
          tier2: 10 psychic damage; the target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of Lord Syuul's choice
          tier3: No effect.
      icon: ❇️
      intro: Lord Syuul psionically plunders the minds of each creature within 2 squares of him. Each such creature makes a **Reason test**.
      name: Do It for Me
      power_roll:
        tiers:
            high: No effect.
            low: 13 psychic damage; the target uses a [signature ability](scc.v1:mcdm.heroes.v1/rule.combat/signature-ability) against a creature of Lord Syuul's choice
            mid: 10 psychic damage; the target makes a [free strike](scc.v1:mcdm.heroes.v1/feature.common.main-actions/free-strike) against a creature of Lord Syuul's choice
    - body: Lord Syuul takes an additional main action on his turn. He can use this feature even if he is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      cost: 5 Malice
      effects:
        - effect: Lord Syuul takes an additional main action on his turn. He can use this feature even if he is [dazed](scc.v1:mcdm.heroes.v1/condition/dazed).
      icon: ☠️
      name: Solo Action
    - cost: 7 Malice
      effects:
        - effect: Lord Syuul sends out a psionic burst to completely overpower his greatest threats. He makes a **Reason test** (2d10 + 4).
          tier1: Lord Syuul has damage weakness 5.
          tier2: Lord Syuul has damage immunity 2.
          tier3: Lord Syuul has damage immunity 5.
        - effect: Once per round as a maneuver, Lord Syuul can repeat this test, replacing the previous Overpower effect.
        - effect: Whenever an Overpower effect is active, any hero who has one or more psionic abilities can use a maneuver to push back by making a **Reason test**, replacing the previous Overpower effect.
          tier1: Lord Syuul has damage immunity 5.
          tier2: Lord Syuul has damage immunity 2.
          tier3: Lord Syuul has damage weakness 5.
        - effect: The Overpower effect lasts until the end of the encounter.
      icon: "\U0001F300"
      intro: Lord Syuul sends out a psionic burst to completely overpower his greatest threats. He makes a **Reason test** (2d10 + 4).
      name: Overpower
      power_roll:
        tiers:
            high: Lord Syuul has damage immunity 5.
            low: Lord Syuul has damage weakness 5.
            mid: Lord Syuul has damage immunity 2.
      trailing: |-
        Once per round as a maneuver, Lord Syuul can repeat this test, replacing the previous Overpower effect.

        Whenever an Overpower effect is active, any hero who has one or more psionic abilities can use a maneuver to push back by making a **Reason test**, replacing the previous Overpower effect.

        The Overpower effect lasts until the end of the encounter.
flavor: At the start of Lord Syuul's turn, you can spend Malice to activate one of the following features.
kind: malice
metadata:
    scc: mcdm.monsters.v1/monster.lord-syuul/lord-syuuls-malice
    source: mcdm.monsters.v1
name: Lord Syuul's Malice
type: featureblock
```
