---
title: Why ExinOne AutoInvest Data Differs From Your Wallet
layout: article
---

## Reconcile your assets

Following the steps shown below, confirm the quantity of the assets you have invested through AutoInvest:

![depth](/assets/images/findinvestedassets.png)

After recording them, compare them with the assets in your own wallet, check the differences, and then review your transfer history to find out what caused each discrepancy.


## How AutoInvest data is calculated

### Where AutoInvest assets are stored

When you complete an AutoInvest order on ExinOne, the system will distribute the assets across the following two accounts:

- Mixin wallet
- Trading account

### How return rate is calculated

ExinOne records:

- The value of the assets invested at the time of each order
- The quantity of assets received
- The cumulative return rate

Note that the return rate is calculated based on one important assumption: **you have never sold the assets from your AutoInvest orders, and you have never moved them anywhere else or transferred them to anyone else**.

### What is not counted

The following asset changes will NOT be included in AutoInvest statistics:

- AutoInvest assets that have already been sold
- Assets received through token-to-token trading
- Assets earned through Savings or other channels
- Assets obtained through other platforms
- Assets participating in other products such as Savings


## Why there can be a discrepancy

If you find the token balance in your wallet does not match the AutoInvest data, it may be caused by:

1. You have sold part or all of the assets
2. The assets have been moved to another account
3. The assets are still in the old system and have not been migrated


## Looking up AutoInvest data from before 2023-09-01

If you used AutoInvest before 2023-09-01, we suggest looking up your assets through the old-system Mixin wallet with the following steps:

1. Confirm the token you historically invested in through AutoInvest (for example BOX).
2. Use the Mixin bot @7000101500 to view the transfer history of that token.
3. Read the transfer records:
   - `+xxx` means you received assets.
   - Check the transfer icon to confirm whether the source is ExinOne.

4. Analyze where the assets went:
   - An outgoing transfer to ExinOne (`-xxx`) usually means you sold them.
   - Frequent small incoming transfers may be earnings from savings.
   - Other outgoing transfers may be transfers to friends or trades through other platforms (such as TIGA-Safe).

**Important note**: Assets participating in savings products may not be visible in your Mixin wallet. You need to check the corresponding savings product page to see their current status.
