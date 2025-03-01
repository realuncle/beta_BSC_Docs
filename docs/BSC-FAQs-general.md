---
sidebar_label: BSC General FAQs
hide_table_of_contents: true
sidebar_position: 2
---

# BNB Smart Chain  FAQs

### What is BNB Smart Chain ?

BNB Smart Chain  brings EVM-compatible programmability and native cross-chain communication with Beacon Chain using an innovative consensus of Proof of Staked Authority (PoSA).

### Why is BNB Smart Chain  designed as a separate chain from Beacon Chain ?

The execution of a Smart Contract may slow down the esxchange function and add non-deterministic factors to trading. Even if that compromise could be tolerated, it might be a straightforward idea to introduce a new Virtual Machine specification based on Tendermint, based on the current underlying consensus protocol and major RPC implementation of Beacon Chain . But all these will increase the learning requirements for all existing dApp communities, and will not be very welcomed.

### Where will the published whitepaper be found?

<https://binance.org/whitepaper.pdf> and also <https://github.com/binance-chain/whitepaper>, where feedback is more than welcome.

### Where can I take a look at BNB Smart Chain  code? Is there a GitHub repository?

The codebase of BSC is open-sourced here:

* <https://github.com/binance-chain/bsc>
* <https://github.com/binance-chain/bsc-relayer>
* <https://github.com/binance-chain/bsc-relayer-config>
* <https://github.com/binance-chain/bsc-genesis-contract>
* <https://github.com/binance-chain/bsc-double-sign-sdk>
* <https://github.com/binance-chain/oracle-relayer>

### Where can I find some support?

* Technical talk and support running our software: Telegram <https://t.me/joinchat/IuVfSlYWC5seijz6a0Bjww>
* Bugs or technical contributions: GitHub
* General discussion regarding our blockchain: Telegram <https://t.me/BinanceDEXchange>

### Which are BNB Smart Chain 's official channels for communication and information?

* Binance DEX announcements: <https://t.me/Binance_DEX_Announcement>
* Twitter: <https://twitter.com/binancechain>
* BNB Chain Forum: <https://community.binance.org>

### Wallet support for BNB Smart Chain 

  - [Binance Extension Wallet ](wallet/binance.md)
  - [MetaMask](wallet/metamask.md)
  - [Math Wallet](wallet/math.md)
  - [Arkane](wallet/arkane.md)
  - [Ledger](wallet/ledger.md)
  - [MEW](wallet/myetherwallet.md)

###  How to recover if you choose the wrong network type?

Please read this [guide](./wallet/withdraw-en.md)

清阅读以下 [说明](./wallet/withdraw-cn.md)

### How does BNB Smart Chain  work? What is the architecture and consensus used?

BNB Smart Chain  relies on a system of 21 validators with Proof of Staked Authority (PoSA) consensus that can support short block time and lower fees.

There will be fewer validators on BNB Smart Chain  testnet.

### Can you tell more about Proof of Staked Authority(PoSA)? What is it?

PoSA is a combination of PoA and PoS. Blocks are produced by a limited set of validators, they are elected in and out based on a staking based governance. Validators take turns to produce blocks in a PoA manner

### What are the benefits for developers to build on BNB Smart Chain ?

* EVM-compatible: BNB Smart Chain  supports all the existing Ethereum tooling

* Fast block time, cheaper cost

* Native cross-chain trasfer & communication: Binance DEX remains a liquid venue of exchange of assets on Beacon Chain and BNB Smart Chain "

### What are the benefits for developers to build on BNB Chain?

BNB Chain opens the gate for users to take advantage of the fast transferring and trading

### How many assets are issued on BNB Chain?

There are already [140 assets](https://explorer.binance.org/assets/bep2) on BNB Chain

The introduction of [BEP8](https://github.com/binance-chain/BEPs/blob/master/BEP8.md) is an innovative way for tokenization of properties

### What make BNB Smart Chain  different?

Key Innovations:

* Proof-of-staked-authority Consensus

* Native Cross-Chain Communication

* Expand the use cases of BNB token

### BNB Smart Chain  is EVM-compatible. What does that mean?

EVM means Ethereum Virtual Machine. Any smart-contract written to run in EVM can be easily ported to BNB Smart Chain .

### Can developers make hybrid Dapps using both Beacon Chain  and BNB Smart Chain  in one single Dapp?

Yes, with the help of native cross-chain functions

### How to query the current system parameters

```
bnbcli  params side-params  --side-chain-id=bsc   --node  http://dataseed4.binance.org:80   --chain-id=Binance-Chain-Tigris --trust-node --output=json
```

* minimum self-delegated amount: **10000BNB**

* minimium delegate amount: **1BNB**

* Unbonding time: 7 days

* offline Unjail fee:  1BNB

* offline jail time: 2 day

* offline slashing amount: 50BNB

* Double-sign slashing amount: 10000BNB

* Cross-chain relay fee: 0.004 BNB


### How is BNB Smart Chain  Ecosystem?

<https://github.com/binance-chain/bsc-ecosystem>

### What are the incentives for developers to build on BSC Chain?

Future coding competitions; Hackathons

* Gitcoin: https://gitcoin.co/binancex
* Dorahacks: https://hackerlink.io/en/grant/1

### What are Pegged tokens on BNB Smart Chain ?

Soon after the launch of Beacon Chain , Binance issued several pegged BEP2 tokens that are running on other blockchain networks, including BTC (BTCB), ETH, XRP, LTC, BCH, and ONT. These tokens are backed by real tokens locked in public addresses, and have allowed users to benefit from both the volatility of these tokens as well as the fast transfer and trading experience of Beacon Chain .

Current list:

* BUSD: <https://bscscan.com/address/0xe9e7cea3dedca5984780bafc599bd69add087d56>
* USDT: <https://bscscan.com/address/0x55d398326f99059ff775485246999027b3197955>
* BTC: <https://bscscan.com/token/0x7130d2a12b9bcbfae4f2634d864a1ee1ce3ead9c>
* ETH: <https://bscscan.com/token/0x2170ed0880ac9a755fd29b2688956bd959f933f8>
* DAI: <https://bscscan.com/token/0x1af3f329e8be154074d8769d1ffa4ee058b1dbc3>
* DOT: <https://bscscan.com/token/0x7083609fce4d1d8dc0c979aab8c869ea2c873402>
* XRP: <https://bscscan.com/token/0x1d2f0da169ceb9fc7b3144628db156f3f6c60dbe>
* LINK: <https://bscscan.com/token/0xf8a0bf9cf54bb92f17374d9e9a321e6a111a51bd>
* BAND: <https://bscscan.com/token/0xad6caeb32cd2c308980a548bd0bc5aa4306c6c18>
* LTC: <https://bscscan.com/token/0x4338665cbb7b2485a8855a139b75d5e34ab0db94>
* EOS: <https://bscscan.com/token/0x56b6fb708fc5732dec1afc8d8556423a2edccbd6>
* BCH: <https://bscscan.com/token/0x8ff795a6f4d97e7887c79bea79aba5cc76444adf>
* XTZ: <https://bscscan.com/token/0x16939ef78684453bfdfb47825f8a5f714f12623a>
* ONT: <https://bscscan.com/token/0xfd7b3a77848f1c2d67e05e54d78d174a0c850335>
* ADA: <https://bscscan.com/token/0x3ee2200efb3400fabb9aacf31297cbdd1d435d47>
* ATOM: <https://bscscan.com/token/0x0eb3a705fc54725037cc9e008bdede697f62f335>
* YFII: <https://bscscan.com/token/0x7f70642d88cf1c4a3a7abb072b53b929b653eda5>
* ZEC: <https://bscscan.com/token/0x1ba42e5193dfa8b03d15dd1b86a3113bbbef8eeb>

Details are [here](https://www.binance.org/en/blog/binance-presents-project-token-canal-2/)

### How to Send and Receive BNB on Smart Chain?

[Binance.com](https:/www.binance.com) can withdraw BNB to BSC.

1. If you don't have an existing address of BNB Smart Chain , please use these [wallets](Wallet.md) to create one.

2. On your Binance account, open your BNB wallet then tap on Withdraw. Select BEP20 as the Network. Indicate the amount and paste your BSC address.

3. Complete the steps to withdraw

4. Wait for the exchange to process your request. Once it is confirmed, you will immediately receive BNB to your Smart Chain address.

### How to Send and Receive Pegged tokens on Smart Chain?

[Binance.com](https:/www.binance.com) can withdraw those pegged tokens to BSC.

1. If you don't have an existing address of BNB Smart Chain , please use these [wallets](Wallet.md) to create one.

2. On your Binance account, open your wallet then tap on Withdraw. Select BEP20 as the Network. Indicate the amount and paste your BSC address.


![img](https://lh5.googleusercontent.com/dR9bBqUpNlBFX6zsKFkVRMgHz27Ak0Icu8AFsuJm_1ke6-qSG5Cg2FJLcpRYlFeuFEpisOdXpwn1KDOHBH7qQV9CpYxVb--2B1NxQm-L6B6qSl9Cq90uCSrwHEPAOh69Z0MM2VtG)


3. Complete the steps to withdraw

4. Wait for the exchange to process your request. Once it is confirmed, you will immediately receive BNB to your Smart Chain address.