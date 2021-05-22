<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-ethers](./lib-ethers.md) &gt; [EthersLiquity](./lib-ethers.ethersliquity.md) &gt; [approveLqtyLpTokens](./lib-ethers.ethersliquity.approvelqtylptokens.md)

## EthersLiquity.approveLqtyLpTokens() method

Allow the liquidity mining contract to use Uniswap FTM/aUSD LP tokens for [staking](./lib-base.transactableliquity.stakeunitokens.md)<!-- -->.

<b>Signature:</b>

```typescript
approveLqtyLpTokens(allowance?: Decimalish, overrides?: EthersTransactionOverrides): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  allowance | [Decimalish](./lib-base.decimalish.md) | Maximum amount of LP tokens that will be transferrable to liquidity mining (<code>2^256 - 1</code> by default). |
|  overrides | [EthersTransactionOverrides](./lib-ethers.etherstransactionoverrides.md) |  |

<b>Returns:</b>

Promise&lt;void&gt;

## Exceptions

Throws [EthersTransactionFailedError](./lib-ethers.etherstransactionfailederror.md) in case of transaction failure.

## Remarks

Must be performed before calling [stakeUniTokens()](./lib-base.transactableliquity.stakeunitokens.md)<!-- -->.
