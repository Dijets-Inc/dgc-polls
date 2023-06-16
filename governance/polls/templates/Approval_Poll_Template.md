---
title: Approval Poll for $proposal_name ($dip_code) - $date_MONTH_DD,_YYYY
summary: $sentence_summary
discussion_link: $discussion_link for the RFC Category
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
start_date: $YYYY-MM-DDT16:00:00
end_date: $YYYY-MM-DDT16:00:00
---
# Approval Poll for $proposal_name ($dip_code) - $date_MONTH_DD,_YYYY

The DIP-Editor and Governance Arbiter have placed an approval poll into Dijets Governance [voting system](https://governance.dijets.io/polling) in accordance to the DIPs Framework [DIP0](https://dips.dijets.io/dips/details/DIP0). This Governance Poll will be active for 7 days beginning on $date_DAY,_MONTH_DD at 16:00 UTC.

**This is a binary vote.**
- **DGC Members may vote for a single option.**
- **DGC Members should vote for the option they prefer.**
- **If DGC Members prefer not to vote, they should vote 'Abstain'.**

## Review

DGC Members may vote in this poll to express support or opposition to $dip_code being accepted and implemented or rejected and dropped.

A brief summary of this proposal has been provided by the DIP authoring DGC Member and is shown below:

*$paragraph_summary*

Please review the links below to inform your position on this proposal before voting.
* [Proposal Version]($link_to_github_commit_version)
* [Proposal Discussion Thread]($discussion_link)

## Outcomes

$Minimum_Positive_Participation? This poll implements a **Minimum Positive Participation** value. The Minimum Positive Participation is currently set to **10,000 HAL**.

**If the votes for the 'Yes' option fail to reach or exceed the $Minimum_Positive_Participation? of 10,000 HAL, then the following actions will occur:**
* The DIP Editor will confirm its passage by marking the proposal **Accepted** on the [DIPs Repository](https://github.com/Dijets-Inc/dips) and across all other relevant governance mediums.
* Any further work required to implement the proposal will be tasked to the relevant team and conveyed to the members.

**If the votes for the 'Yes' option fail to reach or exceed the $Minimum_Positive_Participation? of 10,000 HAL, then the proposal will be marked as rejected**

---

## Resources

Additional information about the Governance process can be found on the [Councillor's Hub](https://core-council.dijets.io).
