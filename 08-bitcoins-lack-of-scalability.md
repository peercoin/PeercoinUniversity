# 8. Bitcoin’s Lack of Scalability

Bitcoin was originally designed by Satoshi Nakamoto as a digital replacement for cash. In fact the original whitepaper was titled Bitcoin: A Peer-to-Peer Electronic Cash System. This implies that Bitcoin has the ability to scale to a global level where everyone in the world has the opportunity to transact with the digital currency.

However time has shown that blockchain technology is not capable of scaling to worldwide use, at least by itself. An intense debate has been raging in the crypto community for years now about the best way to scale the blockchain to higher usage levels. The core argument is about whether to increase the size of blocks.

## The Block Size Limit

One of the rules coded into the protocol states that the size of each block can only be one megabyte or less. Since blocks contain transaction data, it follows that as users increase the number of transactions they perform on the network blocks will get closer to being full. Once a block contains enough transactions in it that the space it takes up equals 1MB, that block is considered full and no more transactions can be added to it. Any transactions over the block size limit would have to wait for the next block in order to be added.

At a 1MB block size, the Bitcoin network is restricted to the point where it can only support about seven transactions per second. This block size limitation prevents the blockchain from being able to scale to support worldwide usage levels. In order to solve this problem, one faction in the Bitcoin community wanted to increase this limit so that the blockchain could support a higher capacity of transactions per block. However the other side rejected this proposal because they feared it would further centralize the network.

## Block Size Limit Increases & Centralization of Full Nodes

Remember that full nodes carry a complete copy of the public ledger. The blockchain itself is massive in size due to the requirement to store every single transaction that has ever been processed by miners. This massive ledger needs to be stored on the computer that the validation node is operating on.

If the size of the blockchain becomes larger than what a validator can store on their computer then they will be forced to upgrade their storage capacity in order to continue holding a full copy of the chain. If they do not upgrade then they won’t be able to store the entire ledger, which will prevent them from being able to perform validation of transactions and blocks.

If the block size was increased for example and the number of transactions increased along with it, one fear is that there would come a point in the future where there were so many transactions being performed on the network that advances in storage technology would not be able to keep up with and support the rate of growth in the size of the blockchain.

If this occurred and prices for higher capacity storage did not fall fast enough, it might become unaffordable for certain validators to be able to store the entire blockchain history on their computers. As the number of transactions increased per block, validators would need to continue upgrading their storage capacity in order to hold the entire chain.

This may lead to a situation where volunteers and hobbyists operating full validation nodes would have to quit because they could no longer afford the costs of upgrading their storage capacity. The number of full nodes would decrease over time due to the unsustainable growth of the blockchain and only those with enough resources would be left operating full nodes, namely large merchants, exchanges or payment processors. Once again we have another path that leads to centralization, this time affecting the number of full nodes that do accounting and verification work for the network.

However this possibility depends on how quickly storage technology advances and how affordable it becomes for the average person. It is possible that storage technology may keep up with the rate of growth in the chain size, but only time will tell. In the meantime, other more pressing issues exist with bigger blocks.
Validation nodes have the responsibility of relaying new blocks to other nodes in the network. However this process of propagating new blocks throughout the network will take much longer if block sizes start increasing, especially considering how unreliable internet infrastructure is around the world.

Bandwidth limits may also cause problems with propagating large amounts of data. Consider for example that many home internet packages have much lower upload bandwidth compared to the higher limits offered for downloads. Also remember that each new block takes about 10 minutes to produce. Once blocks become large enough they may reach a point where there is not enough time for each new block to propagate to the rest of the network before the next block becomes due.

Yet another problem is how validation nodes will process all this data. Research suggests for example that it will cost a considerable amount of RAM in order to process large blocks. Most people do not have access to the amount of processing power that will be required, which places the network in a position where volunteer nodes will no longer be able to participate. So both broadcasting and processing this level of data becomes a problem for the average user, placing the task of transaction and block validation mainly in the hands of larger entities that have the resources to continue operating full nodes.

## 2017 Bitcoin Chain Split

In 2017 the block size debate came to a head when two arguing factions inside the Bitcoin community decided to split the network into two separate blockchains that each followed different rules. Both blockchains contained the same exact history of transactions, but diverged at the block where the split occurred.

The first blockchain remained the same at a 1MB block size and continued to be called Bitcoin. The second blockchain however increased the block size from 1MB to 8MB and became known as Bitcoin Cash. Supporters of each network went their separate ways with Bitcoin Cash supporters following the philosophy of scaling with block size increases and supporters of the main Bitcoin network following an alternative scaling philosophy.

Developers on the main Bitcoin chain realized they had a problem on their hands. The block reward reduction schedule was already set in motion. It would only be a matter of time before reductions in the block reward started to negatively impact miners, so developers needed to solve all these problems quickly or risk network security being affected. Ultimately developers intentionally chose to keep the 1MB block size limit for reasons that will become clear shortly.

## Transaction Fee Market

When the Bitcoin network is too congested with transactions and blocks are full, there needs to be a way for a miner to decide which transactions to include in a block. There is limited space available, so it becomes necessary to pick and choose which transactions get priority over others. The Bitcoin network has a transaction fee market which takes over when blocks reach 1MB. When blocks are full, users realize that it will be difficult for them to get their transactions included and added to the chain, so they voluntarily begin to increase the transaction fees they pay to miners.

A higher transaction fee is more profitable for miners, so they will be more likely to include transactions from users with higher fees first over transactions with smaller fees. In this way users of the network enter a bidding war in order to get the attention of miners. The highest bidders paying the largest fees will be the first ones to get their transactions included in new blocks. The lowest bidders however will need to wait until a miner decides to include their transactions.

## Block Size Limit Solves Block Reward Halvings

Bitcoin developers eventually had the realization that this transaction fee market was the solution to their decreasing block rewards. Once again, miners need to be able to stay profitable in the future once block rewards have been reduced to nothing and users are not a reliable fallback option as they are unwilling to voluntarily increase the fees they pay. Therefore the only way to ensure miners get properly compensated is to create a situation where users are forced to pay more in fees. Bitcoin developers have brought about this very situation by deciding to artificially limit the block size to 1MB.

With this artificial limit in place, as blocks fill up and transactions reach maximum capacity, users are forced to pay higher fees in order for their transactions to be validated by miners. If a user refuses to set a higher fee, then miners will likely pass over them in favor of others who pay higher fees. They may eventually get their transaction included hours or days later by a generous miner, but not everyone can afford to wait this long so in order to avoid the long wait times they will voluntarily raise their fee so they have a better chance at getting their transaction processed sooner.

This artificial block size limit therefore motivates users to voluntarily raise the transaction fees they pay to a profitable enough level for miners to be able to continue their expensive mining operations in the face of vanishing block rewards. In this way network security is able to be sustained for a while longer.

## Block Size Limit Impacts Network Usability

This model solves the issue of decreasing block rewards so that miner provided security is retained, however at the same time it also creates new problems. As mentioned before, Bitcoin was originally designed as a peer to peer digital replacement for cash. By limiting the block size, this original vision Satoshi had for the network is no longer possible through use of the blockchain alone.

The Bitcoin community for example once advertised the blockchain as having lower fees than credit card networks. With the implementation of a fixed block size limit however, this core benefit of lower fees is completely eliminated when blocks are full. When this occurrs, users of the network are forced to pay outrageous fees in order to transact with their coins.

While the block size limit has solved the problem of decreasing block rewards, this solution effectively destroys the utility of the blockchain as a medium of exchange during periods where network traffic is considerably high. The network can operate well under normal conditions, however an extreme rise in price causes trading on exchanges to spike. At the peak of a price bubble like this, network congestion is usually at its highest.

Transaction fees will ultimately spike during conditions like this due to a fight over limited block space. This extreme rise in fees negatively impacts the user experience by preventing users from being able to make smaller transactions without significant cost to them. Not only does the block size limit raise fees to unaffordable levels during periods where trading is at its peak, but it also does not solve the scalability problem. A 1MB block size does nothing to support higher usage levels.

## Bitcoin as a Settlement Network

Bitcoin developers however recognized beforehand the negative impact this block size limit would have on the usability of the network, therefore they put plans in motion to solve these remaining issues by using an alternative solution. At some point the realization finally dawned on developers that it was just not possible for blockchain technology to directly facilitate worldwide transaction volumes.

Rather than attempting to engineer changes into the blockchain that would eventually centralize it like block size increases, it became obvious to developers that the purpose of the blockchain itself needed to be refocused to that of a settlement network. In this model, the blockchain itself acts more as a settlement layer for high value transactions.

## Secondary Layers & Off-Chain Transactions

At the same time, secondary layer technologies are built to function on top of the blockchain. These secondary networks are designed to work in conjunction with the underlying blockchain in order to take full advantage of its decentralized and trustless security. They benefit the overall network by providing additional functionality that the blockchain is unable to perform alone by itself.

Secondary layers for example allow users to make lots of transactions instantaneously at low cost without the requirement of needing to wait for miners or new blocks. This is possible because transactions that are performed on layer 2 networks exist completely outside of the blockchain.

Transactions performed directly through the blockchain for example are expensive and slow. They are processed on the blockchain and are therefore considered on-chain transactions. Transactions performed on layer 2 networks however are quick and inexpensive. They are processed off the blockchain and are therefore considered off-chain transactions. On-chain transactions are stored in the blockchain history by a miner. Off-chain transactions however are not stored in the blockchain history at all.

## The Lightning Network & Payment Channels

The primary example of this technology is a layer 2 solution being developed for Bitcoin called the Lightning Network. A user will make an on-chain transaction by first depositing some coins into a special address that is associated with the Lightning Network. The user then opens what is called a payment channel, which allows them to securely transact with other users of the Lightning Network. All transactions are performed off-chain and balances are kept track of by the Lightning Network.

A user can perform as many off-chain transactions as they want as long as they pay intermediaries on the network a small fee in order to route their transactions where they need to go. Finally, once a user is done making payments on the Lightning Network they finish by closing their payment channel. Closing a channel has the effect of settling by recording the final changes in balance on the blockchain.

In this way, it allows users the ability to bypass expensive miner fees by performing the majority of their transactions instantly off the blockchain on secondary layer networks. In this situation the blockchain itself is used mainly to synchronize balances from time to time whenever a payment channel is closed and changes need to be recorded.

This is what is meant by the blockchain becoming a settlement layer. Transactions are conducted off the blockchain, thereby preventing the chain from bloating and growing in size too much. Those off-chain transactions are then totaled at some point in the future and settled by permanently recording the changes into the ledger.

## Blockchain as a Base Layer

Lightning is also only one example of a layer 2 network. Another that exists is called Failsafe Network. There will be other examples as time goes on and improvements are made. Eventually features and improvements will build on each other to the point where we will have layer 3 networks and beyond. All future layers however are completely dependent on the security of the base layer blockchain. Without a secure base layer acting as a solid foundation, everything built on top of the blockchain will eventually collapse.

Satoshi’s original vision of a peer to peer cash system where all transactions are conducted on-chain is no more, at least when it concerns the main Bitcoin chain. Developers have instead elected to focus on an alternate scaling solution that limits the amount of on-chain transaction volume. Let’s sum all this up in order to understand the reasoning behind the decisions of the developers.

## Putting it all Together

A block reward is distributed with every new block, which compensates miners for the costly work they perform and incentivizes them to continue producing new blocks and securing the network. The block reward is on a set schedule where it will continue decreasing until it becomes zero. Voluntary user transaction fees are not a reliable replacement for block rewards because users are motivated to save as much on fees as possible. Developers therefore instituted a 1MB block size limit.

Because of this limit, as a block fills up with transactions users are forced to pay higher fees in order to have a better chance of getting their transactions accepted by miners. These raised fees are profitable enough for miners to sustain themselves in the absence of block rewards. However these raised fees make it too expensive for normal users to transact on the blockchain.

In response, developers are building secondary layer networks that make it possible to perform lots of quick and inexpensive off-chain transactions. High fees for on-chain transactions will push users conducting micro-transactions and low value consumer payments off the blockchain onto these secondary layer networks where transactions are more affordable.

These developments accomplish a number of things. Miners receive their proper compensation to continue operating. Low value transactions are off-loaded onto secondary layer networks, which makes fees cheaper and speeds faster for users and prevents the blockchain from bloating and growing too fast from too many on-chain transactions.

Any on-chain transactions will be high value transactions where the fees spent are marginal compared to the value that was exchanged. Secondary layer networks also finally make it possible for Bitcoin to scale to support global transaction volumes and usage levels. With layer 2 networks the number of possible transactions is no longer limited by the block size.

## Fee Competition Between Miners & Secondary Layers

It may seem like this finally solves the main problem, however there is still a major flaw that is being overlooked. The flaw is that proof-of-work based blockchains are inherently incompatible with layer 2 networks. The flaw is also in developer’s thinking that miners will continue to be properly compensated in the future.

Any transaction being conducted on a layer 2 network results in some amount of fees not going to miners. Instead small fees are paid to intermediaries operating on the layer 2 network who routes transactions where they need to go. In reality, miners and layer 2 networks are in direct competition with each other for earning transaction fees.

This is not even the main problem though. Regardless of whether intermediaries on layer 2 networks earn fees from users or not, it is a fact that any off-chain transaction results in a miner who doesn’t get paid. Miners can only be paid from users conducting on-chain transactions, therefore it is a fact that layer 2 networks leech off of miner profits.

As layer 2 networks develop further in the future and become easier to use, more people are going to be drawn to using them for their cheap fees and instant transaction times. There will come a point in the future where not enough users are making on-chain transactions and miners will suffer because of it. This will result in the further centralization of miners as they become unprofitable and quit, which will place the network at risk for a double spend attack. Bitcoin developers see layer 2 networks as their savior, however they could just as easily be their death sentence.

## Conclusion on Bitcoin & Proof-of-Work

In the end, proof-of-work based blockchains suffer from a number of design flaws that should cause concern for the sustainability of the system. The mining process is inherently designed to centralize over time. Faster and more efficient mining equipment is released, forcing everyone to upgrade or go broke. Mining itself is an unsustainable waste of energy. It also causes mining to centralize in locations where energy is inexpensive, opening the network up to attack from local governments and regulation. Miners and users are often out of alignment in their desires for the long-term development and evolution of the network. Miners are dependent on a high bitcoin price.

Miners are also incompatible with layer 2 networks. Eventually layer 2 networks will steal enough profits away from miners that they could centralize and open up the network to a possible double spend attack. With such a large number of systemic flaws, the Bitcoin blockchain does not seem like a great foundation to build on top of.

---
