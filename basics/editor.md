---
icon: bell-plus
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
metaLinks:
  alternates:
    - https://app.gitbook.com/s/yE16Xb3IemPxJWydtPOj/basics/editor
---

# Notifications

## Email

The first notification type to enhance your multisig security is good old Email. Pingy sends you email notifications for the signer requests that are most relevant to you. Never send the wrong amount to the wrong address ever again!

<figure><img src="../.gitbook/assets/Pingy-Network-Notification.svg" alt="" width="563"><figcaption></figcaption></figure>

## Webhook

Pingy offers webhook notifications for all of your developer needs. Integrate any application into your opsec workflow and never fall victim to scammers ever again!

```json
{
  "type": "outbound",
  "time": "2025-02-18T18:52:14Z",
  "status": "pending",
  "wallet": {
    "address": "0x3d77c4E0e8dFf72aD763b4A7062C24079B9000F1",
    "network": "ethereum-mainnet",
    "chain_id": 1
  },
  "asset": {
    "symbol": "USDC",
    "amount": "5000.00",
    "address": "0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48"
  },
  "recipient": {
    "ens": "vitalik.eth",
    "address": "0x8dA6F49E0b9Bbd49476c5F608A980bAa96045c9a"
  },
  "signatures": {
    "confirmed": 2,
    "required": 3
  },
  "source": [
    "Alchemy",
    "Infura",
    "QuickNode"
  ]
}
```

## Wildcard

Tell us what you need and we make sure to support your very individual onchain journey. A mobile app? Farcaster integration? Don't be shy and let us know how we can make Pingy better together!
