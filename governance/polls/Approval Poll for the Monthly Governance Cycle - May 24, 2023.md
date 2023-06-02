---
title: Approval Poll for the Monthly Governance Cycle - May 31, 2023
summary: DIP1 introduces a standardised Monthly Governance Cycle by which DGC Members can participate in governance without any time constraints.
discussion_link: https://forum.dijets.io/t/dgc-governance-schedule-monthly-governance-cycle/29
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
end_date: 2023-06-06T16:00:00
---
# Approval Poll for DIP1 standardising the Monthly Governance Cycle - May 31, 2023

Dijets Core Team acting as interim Governance Arbiter has placed an approval poll in Dijets Voting System for [DIP1](https://dips.dijets.io/dips/details/DIP1). This Governance Poll will be active for seven days beginning on Wednesday, May 31 at 16:00 UTC. Note that the DGC Members do not require a CAP position before voting on this approval poll.

**This is a binary vote.**
- **Members may vote for a single option.**
- **Members should vote for the option they prefer.**
- **Members can choose to 'Abstain' should they not have any preference or if they prefer either options.**

## Review

Dijets Council may vote in this approval poll to express support or opposition to DIP1 being accepted and implemented in Dijets Governance Framework.

A brief summary of this proposal is as follows:

*DIP1 provides a predictable monthly cadence by which DGC Members can participate in governance activities and decision making without any time constraints.*

Please review the links below to inform your position on this proposal before voting.
* [DIPs Directory Link](https://dips.dijets.io/dips/details/DIP1)
* [Proposal Discussion Thread](https://forum.dijets.io/t/dgc-governance-schedule-monthly-governance-cycle/29)

## Outcomes

**If the votes for the 'Yes' option exceed the votes for the 'No' option PLUS the votes for the 'Yes' option exceed the minimum set voting weight of 10000 HAL tokens, then the following outcomes will occur:**

**In the event of the proposal not reaching the minimum set voting weight of 10000 HAL tokens or if the votes for the 'No" option exceed the votes for the 'Yes' option then the proposal will be marked as rejected.**

---

## Resources

[DIP1: Dijets Monthly Governance Cycle](https://dips.dijets.io/dips/details/DIP1) aims to provide advance notification and high predictability of governance activities to occur during any given month for DGC Members to stay informed on relevant subjects and the progress of DIPs.

Visit the [Councillor's Hub](https://core-council.dijets.io) for more information on Dijets Governance and Council.

[Dijets Forum](https://forum.dijets.io) - Discussion Forum for Dijets Ecosystem & its Domains.

[Qowalts](https://qowalts.dijets.io) - Join the dedicated DIPs space on Qowalts to follow live discussions.
