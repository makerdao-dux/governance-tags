---
title: Add WBTC-B as a new Vault Type - November 8, 2021
summary: This poll proposes system parameters which could be used to initialize WBTC-B as a new vault type.
discussion_link: https://forum.makerdao.com/t/signal-request-new-iam-vault-type-for-wbtc-with-lower-lr/5736
vote_type: Plurality Voting
categories:
   - Collateral
   - Risk Variable
options:
   0: Abstain
   1: Yes
   2: No
start_date: 2021-11-08T16:00:00
end_date: 2021-11-11T16:00:00
---
# Poll: Add WBTC-B as a new Vault Type - November 8, 2021

The Governance Facilitators have placed a Governance Poll into the [voting system](https://vote.makerdao.com/polling) on behalf of the MakerDAO mandated actors. This Governance [Poll](https://community-development.makerdao.com/en/learn/governance/on-chain-gov) will be active for three days beginning on Monday, November 8 at 16:00 UTC.

**This is a binary vote.** 
- **You may vote for a single option.** 
- **You should vote for the option which you prefer.**
- **If you would accept either option, you should vote 'Abstain'.**

## Review

This poll allows the MakerDAO governance community to signal their support or opposition to adding WBTC-B as a new vault type in the Maker Protocol with the parameters below:

### Collateral Parameters

* Underlying Collateral: Wrapped Bitcoin (WBTC)
* [Stability Fee](https://community-development.makerdao.com/en/learn/governance/param-stability-fee): 5%
* [Liquidation Ratio](https://community-development.makerdao.com/en/learn/governance/param-liquidation-ratio): 130%
* [Debt Ceiling (`line`)](https://community-development.makerdao.com/en/learn/governance/param-debt-ceiling): 500 million DAI
* [Target Available Debt(`gap`)](https://makerdao.world/en/learn/governance/module-dciam): 30 million
* [Ceiling Increase Cooldown(`ttl`)](https://makerdao.world/en/learn/governance/module-dciam): 8 million
* [Debt Floor (`dust`)](https://community-development.makerdao.com/en/learn/governance/param-debt-floor): 30,000 DAI

### Liquidation Parameters

* [Auction Price Function (`calc`)](https://community-development.makerdao.com/en/learn/governance/param-auction-price-function): Stairstep Exponential
* [Price Change Multiplier (`cut`)](https://community-development.makerdao.com/en/learn/governance/param-auction-price-function): 0.99
* [Price Change Interval (`step`)](https://community-development.makerdao.com/en/learn/governance/param-auction-price-function): 60 seconds
* [Auction Price Multiplier (`buf`)](https://community-development.makerdao.com/en/learn/governance/param-auction-price-multiplier): 1.2
* [Liquidation Penalty (`chop`)](https://community-development.makerdao.com/en/learn/governance/param-liquidation-penalty): 13%

**Limits**

* [Local Liquidation Limit (`ilk.hole`)](https://community-development.makerdao.com/en/learn/governance/param-local-liquidation-limit): 25 million DAI
* [Maximum Auction Drawdown (`cusp`)](https://community-development.makerdao.com/en/learn/governance/param-max-auction-drawdown): 0.4
* [Maximum Auction Duration (`tail`)](https://community-development.makerdao.com/en/learn/governance/param-max-auction-duration): 90 minutes
* [Breaker Price Tolerance (`tolerance`)](https://community-development.makerdao.com/en/learn/governance/param-breaker-price-tolerance): 0.5

**Incentives**

* [Proportional Kick Incentive (`chip`)](https://community-development.makerdao.com/en/learn/governance/param-proportional-kick-incentive): 0.1%
* [Flat Kick Incentive (`tip`)](https://community-development.makerdao.com/en/learn/governance/param-flat-kick-incentive): 300 DAI

Please review the following forum threads containing information about WBTC-B to inform your position before voting.
* [Proposal Thread](https://forum.makerdao.com/t/signal-request-new-iam-vault-type-for-wbtc-with-lower-lr/5736)
* [Risk Core Unit Evaluation](https://forum.makerdao.com/t/wbtc-b-collateral-onboarding-risk-assessment/11397)


## Outcomes

**If the votes for the 'Yes' option exceed the votes for the 'No' option then the following actions will be taken:**
* WBTC-B will be onboarded in a future executive vote as the Protocol Engineering Core Unit's schedule allows. 
* It is expected that this executive vote will take place within 30 days of this poll passing, absent external factors.
* If the executive vote passes, then these changes will become active in the Maker Protocol after the [GSM Pause Delay](https://community-development.makerdao.com/en/learn/governance/param-gsm-pause-delay) has expired.

**If the votes for the 'No' option equal or exceed the votes for the 'Yes' option then no further action will be taken at this time.**

---

## Resources

If you are new to voting in the Maker Protocol, please see the [voting guide](https://community-development.makerdao.com/en/learn/governance/how-voting-works/) to learn how voting works, and this [wallet setup guide](https://community-development.makerdao.com/en/learn/governance/voting-setup/) to set up your wallet to vote.

Additional information about the Governance process can be found in the [Governance](https://community-development.makerdao.com/en/learn/governance) section of the MakerDAO community portal.

To participate in future Governance calls, please [join us](https://github.com/makerdao/community/tree/master/governance/governance-and-risk-meetings) every Thursday at 17:00 UTC.

To add current and upcoming votes to your calendar, please see the [MakerDAO Public Events Calendar](https://calendar.google.com/calendar/embed?src=makerdao.com_3efhm2ghipksegl009ktniomdk%40group.calendar.google.com&ctz=UTC&mode=week&showCalendars=0&showPrint=0).
