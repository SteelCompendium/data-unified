---
action_type: feature
class: tactician
feature_type: feature
file_basename: studied-commander
file_dpath: feature/tactician/level-1
item_id: studied-commander
item_name: Studied Commander
level: "1"
name: Studied Commander
scc: mcdm.heroes.v1/feature.tactician.level-1/studied-commander
source: mcdm.heroes.v1
type: feature
---

```ds-feature
effects:
    - effect: |-
        Your encyclopedic knowledge of the history of battle lets you apply that knowledge to current challenges. While you are present, each hero with you treats the Discover Lore project related to a war or battle as one category cheaper. This makes projects seeking common lore free, but such projects still require a [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite) activity to complete. (See Chapter 12: [Downtime Projects](scc.v1:mcdm.heroes.v1/chapter/downtime-projects) for more information.)

        Additionally, if you have 24 hours or more before a combat encounter or negotiation, and you have one or more clues or rumors regarding the encounter or negotiation, you can make a [Reason](scc.v1:mcdm.heroes.v1/rule.character/reason) [test](scc.v1:mcdm.heroes.v1/rule.test/test) as a [respite](scc.v1:mcdm.heroes.v1/rule.resource/respite) activity. The following [test](scc.v1:mcdm.heroes.v1/rule.test/test) outcomes apply to a combat encounter:

        - **≤11:** The Director tells you the number of creatures in the encounter.
        - **12-16:** The Director tells you the number and level of the creatures in the encounter.
        - **17+:** The Director tells you the tier 2 outcome information, and when the encounter begins, all enemies are [surprised](scc.v1:mcdm.heroes.v1/rule.combat/surprised).

        The following [test](scc.v1:mcdm.heroes.v1/rule.test/test) outcomes apply to a negotiation:

        - **≤11:** The Director gives you three motivations, one of which belongs to an [NPC](scc.v1:mcdm.heroes.v1/rule.general/npc) in the negotiation.
        - **12-16:** The Director gives you one motivation for an [NPC](scc.v1:mcdm.heroes.v1/rule.general/npc) in the negotiation.
        - **17+:** The Director tells you the tier 2 outcome information, and you and each of your allies gains an [edge](scc.v1:mcdm.heroes.v1/rule.dice/edge) on [tests](scc.v1:mcdm.heroes.v1/rule.test/test) made to influence [NPCs](scc.v1:mcdm.heroes.v1/rule.general/npc) during the negotiation.

        You can make this [test](scc.v1:mcdm.heroes.v1/rule.test/test) only once for any encounter or negotiation.
feature_type: feature
metadata:
    class: tactician
    level: "1"
    name: Studied Commander
    scc: mcdm.heroes.v1/feature.tactician.level-1/studied-commander
    type: feature
name: Studied Commander
type: feature
```
