# 12. Scalability of Peercoin
Unlike most blockchain projects, Peercoin developers have never believed that blockchains alone by themselves could scale to full worldwide usage levels. In fact Sunny King himself tailored the Peercoin blockchain and its economics to fit what he originally termed the “backbone currency” role, which is now commonly known in the crypto community as a settlement layer.

The Backbone of Crypto

From the very beginning, Sunny believed that adapting blockchains directly for wide scale use only through on-chain transactions would negatively impact the decentralization level and security of the network over time, therefore he intentionally chose to develop the Peercoin blockchain to function as a base layer settlement network, or in his own words, a backbone currency.

The following quote by Sunny King is from a 2013 interview conducted for the Peercoin community. As you can see below, Sunny’s deep understanding of blockchain technology greatly influenced his design for the Peercoin network. The quote has been slightly modified from its original state to remove references of Primecoin, another blockchain that was invented by Sunny which is not very relevant to this text.

Sunny_King:

>Peercoin is energy efficient and is designed to last. Bitcoin has a long term uncertainty as to whether transaction fees can sustain good enough level of security. Before that the main concern is how to balance transaction volume and transaction fee levels. Currently I get the feeling that bitcoin developers favor very low transaction fees and very high transaction volume, to be competitive against centralized systems (paypal, visa, mastercard etc) in terms of transaction volume, to the point of sacrificing decentralization. This also brings major uncertainties to bitcoin’s future.

>From my point of view, I think the cryptocurrency movement needs at least one ‘backbone’ currency, or more, that maintains a high degree of decentralization, maintains a high level of security, but not necessarily providing high volume of transactions. Thinking of savings accounts and gold coins, you don’t transact them at high velocity but they form the backbone of the monetary systems.

>Pure proof-of-work systems such as bitcoin are not 100% suitable for this task. This is because the transaction fee is not a reliable incentive to sustain network security. If the mining generation amount is kept constant (there have been several such attempts in altcoins) it would work better security-wise but then it would also significantly weaken the scarcity property of the currency.

>Peercoin is designed to serve as a backbone currency. The proof-of-stake technology in Peercoin is not only energy efficient; it also maintains a high level of security without relying on transaction fees. Thus Peercoin could be safely designed with a strong scarcity property yet serve well as backbone currency. Peercoin uses protocol enforced transaction fees, which reflects my preference that high transaction volume is discouraged in favor of serving as backbone currencies.

>Right now if we are talking about micropayments in the US $1 range, Peercoin still handles them with much lower overhead than credit card networks. In the long term micropayments should be provided by centralized providers, or a less decentralized network optimized for high capacity transaction processing.

>On the other hand there is no promise that the minimum transaction fee wouldn’t be adjusted. If processing capacity of personal computers continues to advance at the current pace, both max block size and minimum transaction fee could very well be adjusted at some point. However I do take a very cautious approach to adjusting transaction fees, as opposed to bitcoin devs. The impact to the fitness of the currency as a backbone currency is of great concern to me.

Sunny’s main worry in this quote was the potential loss of decentralization over time by focusing the blockchain on directly supporting high on-chain transaction volumes. This fear eventually became realized with the creation of Bitcoin Cash, a blockchain completely focused on on-chain transaction volume through regular increases in the block size. Recall that these increases in block size make it difficult over time for network validators to store the entire chain on their personal devices due to the increasing need for more hard drive space as well as the difficulty of broadcasting and processing bigger blocks.

Focusing Peercoin on supporting high on-chain transaction volume for example would negatively impact both validators who voluntarily operate nodes as well as proof-of-stake minters. Over time this would lead to the centralization of security providers as only those who could afford to keep up with the demands of larger blocks would be left running nodes. Unsustainable growth in the size of the blockchain, bandwidth requirements for broadcasting big blocks and hardware requirements for processing big blocks would drive away both volunteers and small stakeholders.

## The Original Base Layer Settlement Network

Sunny King had incredible foresight however and designed Peercoin to completely avoid this problem. Instead he implemented a fixed transaction fee to act as a deterrent against high on-chain transaction volume. By doing this, Sunny was purposefully treating the Peercoin blockchain as a settlement network. He recognized early on in the design phase that the crypto community needed a secure and censorship resistant base layer for the future blockchain connected world. Peercoin was designed as this base layer, upon which other supporting layers could be developed.

In fact Sunny realized this long before Bitcoin’s core developers started thinking in these terms, which makes Peercoin the original base layer settlement network even before Bitcoin. Through changes to its core protocol and the adoption of second layer networks, Blockstream, the company responsible for Bitcoin’s development, has basically done all it can to make Bitcoin more and more like Peercoin. Peercoin developers are happy to see the world’s largest blockchain becoming closer to the way we’ve always imagined blockchains should operate.

Bitcoin developers for example have basically been forced into changing Bitcoin from a peer to peer electronic cash system into a settlement network with high fees and limited transaction volumes in order to sustain network security in the future. This is the only way that Bitcoin can survive. Instead they will treat Bitcoin as a base layer and attempt to unload micro-transactions onto secondary layers built on top of the blockchain such as the Lightning Network. This is the way Peercoin was designed from the very beginning.

In the quote above, Sunny mentioned that in the long-term micropayments should be provided by centralized providers, or a less decentralized network optimized for high capacity transaction processing. Sunny was referring to layer 2 networks in this quote. At the time Sunny said this however the crypto community had not yet come up with a naming convention for the concept of varying blockchain layers. Terminology like base layer, settlement layer, secondary layer all came afterward once the idea was more established in the community.

## Compatibility of Minters & Second Layers

Previously it was explained that layer 2 networks are ultimately incompatible with proof-of-work miners. This is true because any off-chain transaction prevents miners from being compensated. Once block rewards are gone, miners can only be paid if users perform on-chain transactions, therefore any increase in off-chain transactions will cause miners to suffer financially. Eventually this will negatively impact network security as miners become unprofitable and drop out.

However once again, Peercoin completely solves this issue. Since proof-of-stake minters are compensated from block rewards that are automatically generated by the network, off-chain transactions that are conducted on layer 2 networks have absolutely no impact on the Peercoin blockchain’s overall security.

In other words, minters do not rely on user transaction fees. They obtain their motivation to provide security from network generated block rewards. As a result, proof-of-stake minters are not impacted if off-chain transactions increase. Minters have no reason to care whether transactions are being made on-chain or off-chain, since they are being compensated from a completely different source.

Therefore Peercoin is one of the only blockchains that really makes sense to be paired with secondary layers like the Lightning Network. Unlike proof-of-work networks, security validators at Peercoin do not depend on expensive transaction fees in order to sustain network security. Instead transaction fees in Peercoin are burned rather than distributed to minters as compensation.

This is important because it means off-chain transactions being conducted on the Lightning Network will not compete with Peercoin minters. Minters can sustain themselves completely on network generated block rewards, which means Lightning and other layer 2 networks are not a threat to Peercoin’s security model.

A conclusion that can be drawn from this is that only proof-of-stake blockchains that burn fees are compatible with secondary layer networks. Any blockchain that is reliant on fees to sustain network security will be incompatible with secondary layers.

## Dynamic Block Sizes

The Peercoin Team is actually interested in implementing both on-chain and off-chain scaling mechanisms. Off-chain scaling would rely on secondary layer networks like Lightning that are developed by external development teams. On-chain scaling in Peercoin would consist of a change to the core protocol that allows for dynamic block sizes.

If dynamic block sizes are implemented in the future, it will most likely function like the following. When a block is filling up and transactions are almost at maximum capacity, the block size limit will be allowed to temporarily rise above 1MB. As long as there is demand for the extra space, the block size limit will stay at this level. If transaction volume decreases however, then the limit will fall back to 1MB.

These temporary block size increases in Peercoin would be much different than the ones in Bitcoin Cash however due to Peercoin’s use of a static transaction fee. In Bitcoin Cash a user attempting to transact with their coins can volunteer to pay whatever fee they want to miners, no matter how small it is.

Since the block size limit in Bitcoin Cash is much larger than 1MB, the extra space means there is much less of a chance for a block to be filled up, which also means higher fees are less likely to be triggered because of a full block. Without higher fees, it is much easier for users to fill up the blockchain with cheap on-chain transactions. A minimum transaction fee is required to help filter out and prevent severe transaction spam and the resulting bloating of the chain size.

In Peercoin however a user is forced to pay the mandatory fixed fee of 0.01 PPC per kilobyte of space used. This static fee acts as a restriction to curb the number of on-chain transactions, which prevents bloating of the blockchain size. Consider also the fact that the fee is priced in Peercoin rather than in fiat money like the dollar or the euro. If the price of Peercoin rises in terms of dollar value, the 0.01 fee will cost more.

For example, if the price per peercoin is $10, then the value of the 0.01 PPC fee will cost a user about 10 cents per transaction. If the price per peercoin is $100, then the value of the 0.01 PPC fee will cost a user $1 per transaction. If the price is $1,000, then the transaction fee will cost $10. As the price of Peercoin rises, the cost of on-chain transaction fees will rise along with it. It is possible to adjust the static fee lower in the future if transactions become cost prohibitive, however an upgrade of the network like this would require consensus from stakeholders.

The way this would work in Peercoin is that users would make transactions on the chain only up to the point of affordability. Users who are transacting large amounts of peercoin for example may consider the high fee marginal compared to the amount they’re trying to send. Plus they may not mind high transaction fees if it means taking advantage of the higher security of on-chain transactions over doing those same transactions on layer 2 networks. On the other hand a user that is trying to transact small amounts may find the transaction fee they need to pay is worth more than the coins they are trying to send.

There may be enough transaction volume to temporarily raise the block size limit for a short period of time, but there are only so many people who are willing to pay for on-chain transactions when the cost is so high. This results in a situation where users only pay for on-chain transactions if the security advantages of transacting directly on the blockchain are worth it for them when the fees of those transactions are taken into consideration.

The remaining users who feel the cost of on-chain transactions aren’t worth the security benefit will use secondary layer networks instead. For example, small transactions that are too costly to be performed on the blockchain will end up being off-loaded by users onto layer 2 networks where they are less expensive to perform. In this way the cost of the transaction fee will determine whether users decide to transact on-chain or off-chain. With dynamic block sizes in Peercoin, the limit would only increase as long as there are users willing to pay the fee for on-chain transactions.

---
