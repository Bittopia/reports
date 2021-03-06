---
description: >-
  The reasons as to why we stopped using Coinomi for our workshops and
  educational sessions.
---

# Why We Stopped Supporting The Coinomi Blockchain Wallet

Website:  
[https://www.coinomi.com/en/](https://www.coinomi.com/en/)

Github:  
[https://github.com/coinomi/](https://github.com/coinomi/)

Coinomi was at one stage an open-source blockchain wallet that made it easy to interact with many blockchains. Due to its easy to use interface and versatility, we had used it as our wallet of choice for workshops and educational seminars for several years.

The following document outlines the reasons as to why we stopped supporting their wallet.

## **1.0 No Longer Open-Source:**

The Coinomi wallet has not been open-source for many years. Given it is a wallet that deals with a great number of blockchains, you would want to ensure the wallet is open-source so that the source code can be audited. As mentioned by a user on Bitcointalk:

> **"...**well it is a closed source wallet with some source code on github which they don't even update unlike their wallet so for all you know they might do a lot of shady things without you knowing it. so it doesn't really matter whether it is only their desktop wallet or android wallet. you shouldn't be using it in first place." -- [Bitcointalk](https://bitcointalk.org/index.php?topic=5115118.msg49953736#msg49953736), 2019.

## 2.0 Sweep Function Issue on iOS

During several workshops we faced issues with the wallet sweep function on iOS devices, when sweeping a paper wallet with the use of a QR code.

We had reported this issue to the team in the February 2020, and was told that this was a known issue and that it would be resolved in time. At the time of writing this report, we have not yet been informed of a solution.

Given that most of the users at our workshops were iOS users, we were forced to consider other options.

## 3.0 Collaboration

We were unable to find a way to collaborate with the organization, despite our many attempts at creating a conversation for joint opportunities. For several months we were repeatedly told by several members that they would get back to us to set up a meeting, or reach out for a conversation, but this led nowhere.

This did not align with our vision of the decentralization culture that had given birth to Bitcoin, as we were looking for a symbiotic partnership with an organization that respected our efforts.

## 4.0 In wallet Exchange Service \(Centralized Risk\)

Coinomi decided to include some in-wallet exchanges, allowing people to trade their tokens and/or coins for other assets directly within the wallet. This function, while enhancing convenience, could create problems as the user could send coins to exchange and be told to verify themselves prior to receiving their funds. This could create a hostage situation, which again, goes against the principles of decentralization

The following was written by [Juraj Bednár,](https://juraj.bednar.io/en/about-me/) one of the co-founders of Paralelni Polis and translated to English by [Peter Kožuch](https://bitcointipsandtricks.wordpress.com/contact/):

> _"To make matters worse, many wallets \(including Coinomi or Trezor\) have integrated access to exchanges. So not all apps where you can change cryptocurrencies are automatically exchanged. In Coinomi or Trezor, you can exchange Litecoin for Bitcoin, for example, through \[the cryptocurrency exchange\] integration. However, the difference is that the currency sold on the exchange will go to the moment of the transaction and the selection of the purchased cryptocurrency will come to your wallet immediately. The exchange, therefore, has access to your money only for the duration of the transaction. This still doesn’t necessarily mean that the transfer will take place immediately \(even such an exchange will wait for the transaction to be confirmed and may sometimes ask for additional documents."_  
> -- [Cryptocurrency wallet vs exchange – what’s the difference?](https://bitcointipsandtricks.wordpress.com/2020/05/17/cryptocurrency-wallet-vs-an-exchange/), 2020

I reached out to Juraj to share my thoughts regarding the above comments:

> _It made me think about the system design there and what you were suggesting. I did not include this in the video for I was thinking the system design would work in the following way:_
>
> * _Wallet interacts with third party app, such as changelly \(for exchange reasons\)._ 
> * _Third party app returns with a response on the overall fees and exchange rates in accordance to your set amount._ 
> * _Once confirmed, the third party app requests permission from the wallet, i.e your private key to send the amount to the exchange. This can only occur with your approval and signature \(via password or pin\)._
> * _Once the transaction is done, the amount that you have requested is sent back to your designated address._ 
>
> _Am I wrong in assuming this is the case? Because if that is the case, I do not see any security issue there and I do not see it as you not be in a non-custodian situation, as the transaction would not be any different to scanning a QR code and sending funds with your permission. Is this something you can confirm for me? -- Amin Rafiee, Bittopia University, 2020_

Juraj responded back with the following statement:

> _It works exactly like this, but there are security issues with this design. **The main one being that the exchange has the custody of the funds for the duration of the transaction and can literally lock you out - for example by requiring proof of identity and source of funds. That happened to some people that either exchanged Monero or coinjoined btc, or simply did too high of a volume. You never know in advance if the exchange flags your transfer.**_
>
> _Compare this with more decentralized designs, where the exchange either happens in one transaction or does not happen at all. For example incognito.org has something that approaches this \(and one of the values of the creators is no KYC ever\)._
>
> _The main reason for writing this in the article is that people can differentiate between wallet and an app with access to your account on the exchange. For example a Coinbase or Kraken app is not a wallet. It used to be easy to differentiate at least very superficially - does the app offer exchange services? No? =&gt; it's a wallet. Now it's not that clear, because wallets offer exchange services. There's nothing wrong with that, but you should know the risks if you choose to use them._
>
> _**Of course that does not make the use-case as a wallet less secure, Trezor is a great wallet, if you don't touch the exchange tab. -**-_ Juraj Bednár, 2020

### 4.1 Trezor Update: Invity.io \(SatoshiLabs\)

Juraj made the following update \(4/12/2020\):

> Trezor has since evolved and they are integrating Invity.io \(which is part of SatoshiLabs\). When they show you the partners to do exchange, they clearly state how they process the exchange: [https://invity.io/exchange-crypto](https://invity.io/exchange-crypto)

![](https://bittopia-university.s3.eu-central-1.amazonaws.com/resources/invity-trezor-exchange.png)

> Basically all exchanges require KYC on suspicious transactions, but some of them will refund you without KYC. Invity \(integrated in Trezor wallet\) tells you this exactly before you make a choice of an exchange. Which is nice and honest.
>
> Here I would pick ChangeNow, because they do refunds without KYC. So I would say that it is good that some wallets share this information with you in advance. Trezor is a positive example now. And I would say that integrating a crypto2crypto exchange is a feature, not a bug. If you know what you're getting into.
>
> Another good thing would be to have setting not to show you those services that require KYC for refunds. Like a checkbox.

## 5.0 Room for Improvement

Coinomi could improve their integrity by having an open-source version of their blockchain wallet. They can also implement a similar feature to that of Trezor, so that the end-user has an idea of what they are getting into, and the risk involved with the in-wallet exchanges.

As for the partnership, our research pointed us to a well-known blockchain wallet developed by BRD. The BRD website offered an easy way to [form a partnership](https://brd.com/partners). They contacted us within a few days of submitting our application to move forward on the discussion. This shows that they have thought about the bigger picture, to form unions with those wishing to support their project.

Furthermore, the BRD blockchain wallet is open-source, thus respecting the principles of the space that has allowed them to develop using existing open-source technologies. If decentralized cryptocurrencies were not open-source, these organizations would never have been able to create what they have as easily, without permission, while financially benefiting from it.

> We believe in trust through transparency. Our core wallet technology is, and will always be, open-source and free. We invite anyone to use our code according to the terms of the MIT open-source license. -- BRD.com, 2020

It would be great to see BRD support a greater range of coins, such as Litecoin and Monero, though for the time-being, BRD have provide the necessary framework and principles for us to collaborate with them.

