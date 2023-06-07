---
title: DIP0m11-SP1 onboards Member Alisha Ramazannezhad as DIP Editor - Jun 06, 2023
summary: DIP0m11-SP1 onboards Member Alisha Ramazannezhad as DIP Editor to enforce the administrative and editorial aspects of the DIPs process and the DIPs framework.
discussion_link: https://forum.dijets.io/t/onboarding-dgc-member-alisha-ramazannezhad-as-dip-editor-under-dip0m11-sp1/28
parameters:
    input_format:
        type: single-choice
        abstain: [0]
    victory_conditions:
        - {
            type: 'and',
            conditions: [
                { type : plurality },
                { type : comparison, comparator : '>=', value: 10000 }
            ]
        }
        - {type : default, value : 2 }  
    result_display: single-vote-breakdown
version: v2.0.0
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2023-06-06T16:00:00
end_date: 2023-06-13T16:00:00
---
# Poll: RE-POLL DIP0m11-SP1 onboards Member Alisha Ramazannezhad as DIP Editor - Jun 06, 2023

Dijets Core Team acting as interim Governance Arbiter have placed an approval poll into Dijets Voting System for the appointment of DIP Editor as described in [DIPs Framework](https://github.com/Dijets-Inc/dips/blob/master/DIP0/dip0.md#dip0m9-dip-editor-role). This Governance Poll will be active for seven days beginning on Tuesday, Jun 06 at 16:00 UTC. Note that the DGC Members do not require a CAP position before voting on this approval poll. Procuring a CAP will become a mandatory step to undergo for DGC members before each governance cycle begins. CAPs and the Governance Cycle will come into effect as soon as the program has the required core personnel onboarded and it has had some time to mature.

**This is a binary vote.**
- **Members may vote for a single option.**
- **Members should vote for the option they prefer.**
- **Members can choose to 'Abstain' should they not have any preference or if they prefer either options.**

## Review

Dijets Council may vote in this approval poll to express support or opposition to DIP0m11-SP1 being accepted and implemented in Dijets Governance.

A brief summary of this proposal is as follows:

*DIP0m11-SP1 onboards Alisha Ramazannezhad as DIP Editor to enforce the administrative and editorial aspects of the DIPs process and DIPs framework.*

Please review the links below to inform your position on this proposal before voting.
* [Proposal Repo Link](https://github.com/Dijets-Inc/dips/blob/master/DIP0/DIP0m11-Subproposals/DIP0m11-SP1.md)
* [Proposal Discussion Thread](https://forum.dijets.io/t/onboarding-dgc-member-alisha-ramazannezhad-as-dip-editor-under-dip0m11-sp1/28)

---

## Outcomes

**If the votes for the 'YES' option exceed the votes for the 'NO' option then the following outcomes will occur:**
 - The Governance Arbiter will mark the proposal accepted (Only dip editors can mark proposals accepted or rejected but this being the proposal to onboard the very first editor, Governance Arbiter will be tasked with marking proposals in the interim).
 - Member Alisha will take on the DIP Editor responsibilities and be granted PR and Merge access to the relevant organisational github repositories.
 - The DIP Editor will confirm the proposal's passage to the [DIPs Directory](https://dips.dijets.io) on Friday, June 8 by submitting a pull request with her particulars.
 - The DIP Editor will review and merge the pull request into the master repo signalling the conclusion of the appointment implementation process under [DIP0m11-SP](https://github.com/Dijets-Inc/dips/tree/master/DIP0/DIP0m11-Subproposals).

**If the votes for the 'NO' option exceed the votes for the 'YES' option then the following outcomes will occur:**
 - The Governance Arbiter will mark the proposal rejected.
 - The Council will re-submit a proposal under DIP0m11-SP for core personnel onboarding.
 - Proposal begins its passage towards voting.
---

## Resources

[DIP1: Dijets Monthly Governance Cycle](https://dips.dijets.io/dips/details/DIP1) describes different types of proposals and related polls and process scheduling. Note that the Governance Cycle will come into effect immediately after the Governance Program's initial setup phase has completed.

DGC Members wishing to learn more about Dijets Governance Model, Voting Mechanism/Guides, HAL assessments and scoring processes can visit the  [Councillor's Hub](https://core-council.dijets.io).

Additional information about the Governance process can be found at dedicated spaces on Qowalts.

[Dijets Forum](https://forum.dijets.io) is the best place for all DGC Members to discuss DIPs, HAL and governance polls.
