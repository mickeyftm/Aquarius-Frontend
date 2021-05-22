<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [EthersLiquity](./lib-ethers.ethersliquity.md)

## EthersLiquity class

Convenience class that combines multiple interfaces of the library in one object.

<b>Signature:</b>

```typescript
export declare class EthersLiquity implements ReadableEthersLiquity, TransactableLiquity 
```
<b>Implements:</b> [ReadableEthersLiquity](./lib-ethers.readableethersliquity.md)<!-- -->, [TransactableLiquity](./lib-base.transactableliquity.md)

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `EthersLiquity` class.

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [connection](./lib-ethers.ethersliquity.connection.md) |  | [EthersLiquityConnection](./lib-ethers.ethersliquityconnection.md) | Information about the connection to the Aquarius protocol. |
|  [populate](./lib-ethers.ethersliquity.populate.md) |  | [PopulatableEthersLiquity](./lib-ethers.populatableethersliquity.md) | Can be used to create populated (unsigned) transactions. |
|  [send](./lib-ethers.ethersliquity.send.md) |  | [SendableEthersLiquity](./lib-ethers.sendableethersliquity.md) | Can be used to send transactions without waiting for them to be mined. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [\_getRemainingLiquidityMiningLQTYORewardCalculator(overrides)](./lib-ethers.ethersliquity._getremainingliquiditymininglqtyorewardcalculator.md) |  |  |
|  [adjustTrove(params, maxBorrowingRate, overrides)](./lib-ethers.ethersliquity.adjusttrove.md) |  | Adjust existing Trove by changing its collateral, debt, or both. |
|  [approveLqtyLpTokens(allowance, overrides)](./lib-ethers.ethersliquity.approvelqtylptokens.md) |  | Allow the liquidity mining contract to use Uniswap FTM/aUSD LP tokens for [staking](./lib-base.transactableliquity.stakeunitokens.md)<!-- -->. |
|  [approveUniTokens(allowance, overrides)](./lib-ethers.ethersliquity.approveunitokens.md) |  | Allow the liquidity mining contract to use Uniswap FTM/aUSD LP tokens for [staking](./lib-base.transactableliquity.stakeunitokens.md)<!-- -->. |
|  [borrowLUSD(amount, maxBorrowingRate, overrides)](./lib-ethers.ethersliquity.borrowlusd.md) |  | Adjust existing Trove by borrowing more aUSD. |
|  [claimCollateralSurplus(overrides)](./lib-ethers.ethersliquity.claimcollateralsurplus.md) |  | Claim leftover collateral after a liquidation or redemption. |
|  [closeTrove(overrides)](./lib-ethers.ethersliquity.closetrove.md) |  | Close existing Trove by repaying all debt and withdrawing all collateral. |
|  [connect(signerOrProvider, optionalParams)](./lib-ethers.ethersliquity.connect_1.md) | <code>static</code> | Connect to the Aquarius protocol and create an <code>EthersLiquity</code> object. |
|  [depositCollateral(amount, overrides)](./lib-ethers.ethersliquity.depositcollateral.md) |  | Adjust existing Trove by depositing more collateral. |
|  [depositLUSDInStabilityPool(amount, frontendTag, overrides)](./lib-ethers.ethersliquity.depositlusdinstabilitypool.md) |  | Make a new Stability Deposit, or top up existing one. |
|  [exitLiquidityMining(overrides)](./lib-ethers.ethersliquity.exitliquiditymining.md) |  | Withdraw all staked LP tokens from liquidity mining and claim reward. |
|  [exitLiquidityMiningLqty(overrides)](./lib-ethers.ethersliquity.exitliquiditymininglqty.md) |  | Withdraw all staked LP tokens from liquidity mining and claim reward. |
|  [getCollateralSurplusBalance(address, overrides)](./lib-ethers.ethersliquity.getcollateralsurplusbalance.md) |  | Get the amount of leftover collateral available for withdrawal by an address. |
|  [getFees(overrides)](./lib-ethers.ethersliquity.getfees.md) |  | Get a calculator for current fees. |
|  [getFrontendStatus(address, overrides)](./lib-ethers.ethersliquity.getfrontendstatus.md) |  | Check whether an address is registered as a Aquarius frontend, and what its kickback rate is. |
|  [getLiquidityMiningLQTYLpReward(address, overrides)](./lib-ethers.ethersliquity.getliquiditymininglqtylpreward.md) |  | Get the amount of AQU earned by an address through mining liquidity. |
|  [getLiquidityMiningLQTYReward(address, overrides)](./lib-ethers.ethersliquity.getliquiditymininglqtyreward.md) |  | Get the amount of AQU earned by an address through mining liquidity. |
|  [getLiquidityMiningStake(address, overrides)](./lib-ethers.ethersliquity.getliquidityminingstake.md) |  | Get the amount of Uniswap FTM/LUSD LP tokens currently staked by an address in liquidity mining. |
|  [getLiquidityMiningStakeLqtyLp(address, overrides)](./lib-ethers.ethersliquity.getliquidityminingstakelqtylp.md) |  | Get the amount of Uniswap FTM/LUSD LP tokens currently staked by an address in liquidity mining. |
|  [getLQTYBalance(address, overrides)](./lib-ethers.ethersliquity.getlqtybalance.md) |  | Get the amount of AQU held by an address. |
|  [getLqtyLpTokenAllowance(address, overrides)](./lib-ethers.ethersliquity.getlqtylptokenallowance.md) |  | Get the liquidity mining contract's allowance of a holder's Uniswap FTM/LUSD LP tokens. |
|  [getLqtyLpTokenBalance(address, overrides)](./lib-ethers.ethersliquity.getlqtylptokenbalance.md) |  | Get the amount of Uniswap FTM/LUSD LP tokens held by an address. |
|  [getLQTYStake(address, overrides)](./lib-ethers.ethersliquity.getlqtystake.md) |  | Get the current state of an AQU Stake. |
|  [getLUSDBalance(address, overrides)](./lib-ethers.ethersliquity.getlusdbalance.md) |  | Get the amount of aUSD held by an address. |
|  [getLUSDInStabilityPool(overrides)](./lib-ethers.ethersliquity.getlusdinstabilitypool.md) |  | Get the total amount of aUSD currently deposited in the Stability Pool. |
|  [getNumberOfTroves(overrides)](./lib-ethers.ethersliquity.getnumberoftroves.md) |  | Get number of Troves that are currently open. |
|  [getPrice(overrides)](./lib-ethers.ethersliquity.getprice.md) |  | Get the current price of the native currency (e.g. Ether) in USD. |
|  [getRemainingLiquidityMiningLQTYOReward(overrides)](./lib-ethers.ethersliquity.getremainingliquiditymininglqtyoreward.md) |  | Get the remaining AQU that will be collectively rewarded to liquidity miners. |
|  [getRemainingLiquidityMiningLQTYReward(overrides)](./lib-ethers.ethersliquity.getremainingliquiditymininglqtyreward.md) |  | Get the remaining AQU that will be collectively rewarded to liquidity miners. |
|  [getRemainingStabilityPoolLQTYReward(overrides)](./lib-ethers.ethersliquity.getremainingstabilitypoollqtyreward.md) |  | Get the remaining AQU that will be collectively rewarded to stability depositors. |
|  [getStabilityDeposit(address, overrides)](./lib-ethers.ethersliquity.getstabilitydeposit.md) |  | Get the current state of a Stability Deposit. |
|  [getTotal(overrides)](./lib-ethers.ethersliquity.gettotal.md) |  | Get the total amount of collateral and debt in the Aquarius system. |
|  [getTotalRedistributed(overrides)](./lib-ethers.ethersliquity.gettotalredistributed.md) |  | Get the total collateral and debt per stake that has been liquidated through redistribution. |
|  [getTotalStakedLQTY(overrides)](./lib-ethers.ethersliquity.gettotalstakedlqty.md) |  | Get the total amount of AQU currently staked. |
|  [getTotalStakedLqtyLpTokens(overrides)](./lib-ethers.ethersliquity.gettotalstakedlqtylptokens.md) |  | Get the total amount of Uniswap FTM/LUSD LP tokens currently staked in liquidity mining. |
|  [getTotalStakedUniTokens(overrides)](./lib-ethers.ethersliquity.gettotalstakedunitokens.md) |  | Get the total amount of Uniswap FTM/LUSD LP tokens currently staked in liquidity mining. |
|  [getTrove(address, overrides)](./lib-ethers.ethersliquity.gettrove.md) |  | Get the current state of a Trove. |
|  [getTroveBeforeRedistribution(address, overrides)](./lib-ethers.ethersliquity.gettrovebeforeredistribution.md) |  | Get a Trove in its state after the last direct modification. |
|  [getTroves(params, overrides)](./lib-ethers.ethersliquity.gettroves_1.md) |  | Get a slice from the list of Troves. |
|  [getUniTokenAllowance(address, overrides)](./lib-ethers.ethersliquity.getunitokenallowance.md) |  | Get the liquidity mining contract's allowance of a holder's Uniswap FTM/LUSD LP tokens. |
|  [getUniTokenBalance(address, overrides)](./lib-ethers.ethersliquity.getunitokenbalance.md) |  | Get the amount of Uniswap FTM/LUSD LP tokens held by an address. |
|  [hasStore()](./lib-ethers.ethersliquity.hasstore.md) |  | Check whether this <code>EthersLiquity</code> is an [EthersLiquityWithStore](./lib-ethers.ethersliquitywithstore.md)<!-- -->. |
|  [hasStore(store)](./lib-ethers.ethersliquity.hasstore_1.md) |  | Check whether this <code>EthersLiquity</code> is an [EthersLiquityWithStore](./lib-ethers.ethersliquitywithstore.md)<!-- -->&lt;[BlockPolledLiquityStore](./lib-ethers.blockpolledliquitystore.md)<!-- -->&gt;<!-- -->. |
|  [liquidate(address, overrides)](./lib-ethers.ethersliquity.liquidate.md) |  | Liquidate one or more undercollateralized Troves. |
|  [liquidateUpTo(maximumNumberOfTrovesToLiquidate, overrides)](./lib-ethers.ethersliquity.liquidateupto.md) |  | Liquidate the least collateralized Troves up to a maximum number. |
|  [openTrove(params, maxBorrowingRate, overrides)](./lib-ethers.ethersliquity.opentrove.md) |  | Open a new Trove by depositing collateral and borrowing aUSD. |
|  [redeemLUSD(amount, maxRedemptionRate, overrides)](./lib-ethers.ethersliquity.redeemlusd.md) |  | Redeem aUSD to native currency (e.g. Ether) at face value. |
|  [registerFrontend(kickbackRate, overrides)](./lib-ethers.ethersliquity.registerfrontend.md) |  | Register current wallet address as a Aquarius frontend. |
|  [repayLUSD(amount, overrides)](./lib-ethers.ethersliquity.repaylusd.md) |  | Adjust existing Trove by repaying some of its debt. |
|  [sendLQTY(toAddress, amount, overrides)](./lib-ethers.ethersliquity.sendlqty.md) |  | Send LQTY tokens to an address. |
|  [sendLUSD(toAddress, amount, overrides)](./lib-ethers.ethersliquity.sendlusd.md) |  | Send aUSD tokens to an address. |
|  [stakeLQTY(amount, overrides)](./lib-ethers.ethersliquity.stakelqty.md) |  | Stake LQTY to start earning fee revenue or increase existing stake. |
|  [stakeLqtyLpTokens(amount, overrides)](./lib-ethers.ethersliquity.stakelqtylptokens.md) |  | Stake Uniswap FTM/aUSD LP tokens to participate in liquidity mining and earn LQTY. |
|  [stakeUniTokens(amount, overrides)](./lib-ethers.ethersliquity.stakeunitokens.md) |  | Stake Uniswap FTM/aUSD LP tokens to participate in liquidity mining and earn LQTY. |
|  [transferCollateralGainToTrove(overrides)](./lib-ethers.ethersliquity.transfercollateralgaintotrove.md) |  | Transfer [collateral gain](./lib-base.stabilitydeposit.collateralgain.md) from Stability Deposit to Trove. |
|  [unstakeLQTY(amount, overrides)](./lib-ethers.ethersliquity.unstakelqty.md) |  | Withdraw LQTY from staking. |
|  [unstakeLqtyLpTokens(amount, overrides)](./lib-ethers.ethersliquity.unstakelqtylptokens.md) |  | Withdraw Uniswap FTM/aUSD LP tokens from liquidity mining. |
|  [unstakeUniTokens(amount, overrides)](./lib-ethers.ethersliquity.unstakeunitokens.md) |  | Withdraw Uniswap FTM/aUSD LP tokens from liquidity mining. |
|  [withdrawCollateral(amount, overrides)](./lib-ethers.ethersliquity.withdrawcollateral.md) |  | Adjust existing Trove by withdrawing some of its collateral. |
|  [withdrawGainsFromStabilityPool(overrides)](./lib-ethers.ethersliquity.withdrawgainsfromstabilitypool.md) |  | Withdraw [collateral gain](./lib-base.stabilitydeposit.collateralgain.md) and [LQTY reward](./lib-base.stabilitydeposit.lqtyreward.md) from Stability Deposit. |
|  [withdrawGainsFromStaking(overrides)](./lib-ethers.ethersliquity.withdrawgainsfromstaking.md) |  | Withdraw [collateral gain](./lib-base.lqtystake.collateralgain.md) and [LUSD gain](./lib-base.lqtystake.lusdgain.md) from LQTY stake. |
|  [withdrawLQTYORewardFromLiquidityMining(overrides)](./lib-ethers.ethersliquity.withdrawlqtyorewardfromliquiditymining.md) |  | Withdraw LQTY that has been earned by mining liquidity. |
|  [withdrawLQTYRewardFromLiquidityMining(overrides)](./lib-ethers.ethersliquity.withdrawlqtyrewardfromliquiditymining.md) |  | Withdraw LQTY that has been earned by mining liquidity. |
|  [withdrawLUSDFromStabilityPool(amount, overrides)](./lib-ethers.ethersliquity.withdrawlusdfromstabilitypool.md) |  | Withdraw aUSD from Stability Deposit. |
