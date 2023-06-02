---
title: DIP3 submits an approval poll for adding domains and indices to all DIPs - May 31, 2023
summary: This Proposal provides the council with a complete overview of what specific DIPs are used to address which specific division/domain of Dijets Ecosystem.
discussion_link: https://forum.dijets.io/t/dip3-principal-domains-indices-for-segmenting-dips/42
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
start_date: 2023-05-31T16:00:00
end_date: 2023-06-07T16:00:00
---
# DIP3 submits an approval poll to include Domains and Indices to all DIPs - May 31, 2023

Dijets Core Team acting as interim Governance Arbiter have placed an approval poll into Dijets Voting System for [DIP3](https://dips.dijets.io/dips/details/DIP3)proposing the addition of a further classification of the Domains and Indices into the preamble of the DIPs. This Governance Poll will be active for seven days beginning on Wednesday, May 31 at 16:00 UTC. Note that the DGC Members do not require a CAP before voting on this approval poll.

**This is a binary vote.**
- **Members may vote for a single option.**
- **Members should vote for the option they prefer.**
- **Members can choose to 'Abstain' should they not have any preference or if they prefer either options.**

## Review

Dijets Council may vote in this approval poll to express support or opposition to DIP3 being accepted and implemented in Dijets Governance Framework.

A brief summary of this proposal is as follows:

*DIP3 submits an approval poll to include Domains and Indices with each dip to facilitate a far more structured and organised approach to formulating DIPs.*

Please review the links below to inform your position on this proposal before voting.
* [DIPs Directory Link](https://dips.dijets.io/dips/details/DIP3)
* [Proposal Discussion Thread](https://forum.dijets.io/t/dip3-principal-domains-indices-for-segmenting-dips/42)

## Outcomes

**If the votes for the 'Yes' option exceed the votes for the 'No' option PLUS the votes for the 'Yes' option exceed the minimum set voting weight of 10000 HAL tokens, then the following outcomes will occur:**
 - The DIP Editor will mark the proposal accepted and start the DIPs passage to the Directory.
 - The Governance Arbiter starts implementation of the accepted DIP by making necessary edits to the DIP templates.

**In the event of the proposal not reaching the minimum set voting weight of 10000 HAL tokens or if the votes for the 'No" option exceed the votes for the 'Yes' option then the proposal will be marked as rejected.**
 - The Governance Arbiter will mark the proposal rejected.

---

## Resources

[DIP1: Dijets Monthly Governance Cycle](https://dips.dijets.io/dips/details/DIP1) aims to provide advance notification and high predictability of governance activities to occur during any given month for DGC Members to stay informed on relevant subjects and the progress of DIPs.

Visit the [Councillor's Hub](https://core-council.dijets.io) for more information on Dijets Governance and Council.

[Dijets Forum](https://forum.dijets.io) - Discussion Forum for Dijets Ecosystem & its Domains.

[Qowalts](https://qowalts.dijets.io) - Join the dedicated DIPs space on Qowalts to follow live discussions.
