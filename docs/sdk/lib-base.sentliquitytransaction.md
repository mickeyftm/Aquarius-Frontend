<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@liquity/lib-base](./lib-base.md) &gt; [SentLiquityTransaction](./lib-base.sentliquitytransaction.md)

## SentLiquityTransaction interface

A transaction that has already been sent.

<b>Signature:</b>

```typescript
export interface SentLiquityTransaction<S = unknown, T extends LiquityReceipt = LiquityReceipt> 
```

## Remarks

Implemented by [SentEthersLiquityTransaction](./lib-ethers.sentethersliquitytransaction.md)<!-- -->.

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [rawSentTransaction](./lib-base.sentliquitytransaction.rawsenttransaction.md) | S | Implementation-specific sent transaction object. |

## Methods

|  Method | Description |
|  --- | --- |
|  [getReceipt()](./lib-base.sentliquitytransaction.getreceipt.md) | Check whether the transaction has been mined, and whether it was successful. |
|  [waitForReceipt()](./lib-base.sentliquitytransaction.waitforreceipt.md) | Wait for the transaction to be mined, and check whether it was successful. |
