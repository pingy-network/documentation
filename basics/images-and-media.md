---
icon: circle-question
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
    - https://app.gitbook.com/s/yE16Xb3IemPxJWydtPOj/basics/images-and-media
---

# Why & How

## Why

{% hint style="info" %}
It is not safe to trust a single middleman with our money.
{% endhint %}

Multisigs protect against hacked private keys, but not against compromised user interfaces. Anyone managing any notable amount of money onchain has to execute transactions under the assumption that all web frontends may be compromised.

Relying on a single point of view provided by the same middleman enabled billions of US Dollars stolen from DeFi protocols and its users.

## How

{% hint style="info" %}
Pingy operates under the principle of **Multi Factor Verification**. The more confirmations we get from different nodes in the network, the harder it is for attackers to steal our tokens.
{% endhint %}

Pingy protects users by providing a decentralized point of view of the underlying blockchain. We operate under the assumption that signing the first multisig transaction is almost irrelevant, because multisigs require a quorum of valid signatures to be reached.

1. You operate a multisig of N/M signers. For instance a quorum of 2/3 means that there are 3 signers on a multisig wallet, and it takes a signature from 2 of those 3 in order to execute a transaction.
2. The Pingy Network listens to your multisig from different angles and sends you a notification to your dedicated device, which is independent of the wallet provider that you are using.
3. Since the very first signature cannot do any harm, it is safe to execute it without being 100% certain whether the used web frontend is compromised or not. In any event, the first signature registered onchain is picked up by Pingy, causing the network to send an independent verification to your device.
4. You can now verify what has been observed onchain by a third party and match the provided execution summary with your actual intent. If Pingy tells you that the observed signature is different from what you are seeing in another web interface, then you should not proceed, because the implication of such a mismatch is that some parts of the systems involved are compromised.
