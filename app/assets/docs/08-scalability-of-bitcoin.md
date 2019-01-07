# 8. Scalability of Bitcoin

Bitcoin was originally designed by Satoshi Nakamoto as a digital replacement for cash. In fact the original whitepaper was titled Bitcoin: A Peer-to-Peer Electronic Cash System. This implies that Bitcoin has the ability to scale to a global level where everyone in the world has the opportunity to transact with the digital currency.

Time has shown, however, that blockchain technology is not capable of scaling to worldwide use alone by itself. An intense debate has been raging in the crypto community for some years about the best way to scale the blockchain to higher usage levels. The core argument is about whether to increase the size of blocks.

## The Block Size Limit

One of the rules coded into the protocol is that the size of each block can be no more than one megabyte. Since blocks contain transaction data, blocks will fill as users increase transactions on the network. Once a block contains enough transactions to reach 1MB, no more transactions can be added to it. Any transactions over the block size limit must wait for the next block to be added.

At a 1MB block size, the Bitcoin network can only support about seven transactions per second, and this prevents the blockchain from being able to scale to support worldwide usage levels. One proposal in the Bitcoin community was to increase this limit, so that the blockchain can support a higher capacity of transactions per block. However, others in the Bitcoin community believe that this will further centralize the network.

## Block Size Limit Increases & Centralization of Full Nodes

Remember that full nodes carry a complete copy of the public ledger. The blockchain itself is massive in size due to the requirement to store every single transaction that has ever been processed by miners. This massive ledger needs to be stored on the computer that the validation node is operating on.

If the size of the blockchain becomes larger than what a validator can store on their computer then they will be forced to upgrade their storage capacity in order to continue holding a full copy of the chain. If they do not upgrade then they won't be able to store the entire ledger, which will prevent them from being able to perform validation of transactions and blocks.

If the block size was increased for example and the number of transactions increased along with it, one fear is that there would come a point in the future where there were so many transactions being performed on the network that advances in storage technology would not be able to keep up with and support the rate of growth in the size of the blockchain.

If this occurred and prices for higher capacity storage did not fall fast enough, it might become unaffordable for certain validators to be able to store the entire blockchain history on their computers. As the number of transactions increased per block, validators would need to continue upgrading their storage capacity in order to hold the entire chain.

This may lead to a situation where volunteers and hobbyists operating full validation nodes would have to quit because they could no longer afford the costs of upgrading their storage capacity. The number of full nodes would decrease over time due to the unsustainable growth of the blockchain and only those with enough resources would be left operating full nodes, namely large merchants, exchanges or payment processors. Once again we have another path that leads to centralization, this time affecting the number of full nodes that do accounting and verification work for the network.

However this possibility depends on how quickly storage technology advances and how affordable it becomes for the average person. It is possible that storage technology may keep up with the rate of growth in the chain size, but only time will tell. In the meantime, other more pressing issues exist with bigger blocks.
Validation nodes have the responsibility of relaying new blocks to other nodes in the network. However this process of propagating new blocks throughout the network will take much longer if block sizes start increasing, especially considering how unreliable internet infrastructure is around the world.

Bandwidth limits may also cause problems with propagating large amounts of data. Consider for example that many home internet packages have much lower upload bandwidth compared to the higher limits offered for downloads. Also remember that each new block takes about 10 minutes to produce. Once blocks become large enough they may reach a point where there is not enough time for each new block to propagate to the rest of the network before the next block becomes due.

Yet another problem is how validation nodes will process all this data. Research suggests for example that it will cost a considerable amount of RAM in order to process large blocks. Most people do not have access to the amount of processing power that will be required, which places the network in a position where volunteer nodes will no longer be able to participate. So both broadcasting and processing this level of data becomes a problem for the average user, placing the task of transaction and block validation mainly in the hands of larger entities that have the resources to continue operating full nodes.

## 2017 Bitcoin Chain Split

In 2017 the block size debate came to a head when the two opposing camps decided to split the network into two separate blockchains that each followed different rules. Both blockchains contained the same history of transactions, but diverged at the block where the split occurred.

One blockchain retained the 1MB block size and continued to be called Bitcoin. The second blockchain increased the block size from 1MB to 8MB and became known as Bitcoin Cash. Supporters of each network went their separate ways: Bitcoin Cash supporters following the philosophy of scaling with block size increases; and supporters of Bitcoin following an alternative scaling solution.

Developers on the main Bitcoin chain had a problem on their hands. The block reward halvings would eventually impact miner profits, so developers needed to solve this problem quickly or risk network security. Ultimately, developers intentionally chose to keep the 1MB block size limit for reasons that will become clear.

## Transaction Fee Market

When the Bitcoin network is too congested with transactions and blocks are full, miners need to decide which transactions to include in a block. There is limited space available, so it becomes necessary to choose which transactions get priority. The Bitcoin network has a transaction fee market which takes over when blocks reach 1MB. When blocks are full, users realize that it will be difficult to get their transactions added to the chain, so they voluntarily begin to increase the transaction fees they pay to miners.

A higher transaction fee is more profitable for miners, so they will be more likely to prioritize transactions with higher fees over those with smaller fees. In this way users of the network enter a bidding war for the attention of miners. The highest bidders paying the largest fees will be the first ones to get their transactions included in new blocks, while the lowest bidders will need to wait.

## Block Size Limit Solves Block Reward Halvings

Bitcoin developers realized that this transaction fee market was the solution to decreasing block rewards. Miners need to be able to stay profitable when block rewards are reduced, and so the only way to ensure miners are properly compensated is to create a situation where users are incentivized to pay more in fees. Bitcoin developers have brought this situation about by limiting the block size to 1MB.

With this artificial limit in place, as blocks fill up and transactions reach maximum capacity, users are incentivized to pay higher fees in order for their transactions to be validated by miners. If a user refuses to set a higher fee, then miners will likely pass over them in favor of others who pay higher fees. They may eventually get their transaction included hours or days later by a generous miner, but not everyone can afford to wait this long so in order to avoid the long wait times they will voluntarily raise their fee so they have a better chance at getting their transaction processed sooner.

This artificial block size limit therefore motivates users to voluntarily raise the transaction fees they pay to a profitable enough level for miners to be able to continue their expensive mining operations in the face of vanishing block rewards. In this way network security is able to be sustained for a while longer.

## Block Size Limit Impacts Network Usability

This model solves the issue of decreasing block rewards so that miner provided security is retained, but at the same time it creates new problems. Bitcoin was originally designed as a peer to peer digital replacement for cash. By limiting the block size, this vision is no longer possible through use of the blockchain alone.

The Bitcoin community once advertised the blockchain as having lower fees than credit card networks. The implementation of a fixed block size limit means this advantage of lower fees is eliminated when blocks are full. When this does occur, users of the network are forced to pay exorbitant fees in order to transact.

While the block size limit solves the problem of decreasing block rewards, the resultant transaction fees will ultimately spike during extreme price rises; at the peak of a price bubble, network congestion is at its highest due to a fight over limited block space. This extreme rise in fees negatively impacts users by preventing them from making smaller transactions without significant cost. Not only does the block size limit increase fees to unaffordable levels during peak trading, but it also does not solve the scalability problem. A 1MB block size does nothing to support higher usage levels.

## Bitcoin as a Settlement Network

Bitcoin developers however realized that it was not possible for the blockchain to facilitate worldwide transaction volumes, due to the block size limit, so they made plans for an alternative solution.

Rather than attempting to engineer changes into the blockchain that would eventually centralize it like block size increases, it became obvious to developers that the purpose of the blockchain needed to be refocused to that of a settlement layer for high value transactions.

## Secondary Layers & Off-Chain Transactions

The purpose of the blockchain as a settlement layer is that secondary layer technologies can be built on top of it. These secondary or layer 2 networks are designed to take full advantage of the blockchain’s trustless security. They benefit the overall network by providing additional functionality that the blockchain is unable to perform by itself.

For example, some layer 2 networks allow users to make high speed transactions at low cost without needing to wait for miners to produce new blocks. This is possible because transactions that are performed on layer 2 networks exist outside of the blockchain.

Transactions performed directly through the blockchain are considered on-chain transactions. Transactions performed on layer 2 networks are processed off the blockchain, and are quick and inexpensive. On-chain transactions are stored in the blockchain history by a miner. Off-chain transactions are not stored in the blockchain history at all.

## The Lightning Network & Payment Channels

The primary example of layer 2 technology is the Lightning Network, which was developed for Bitcoin. To begin, a user will make an on-chain transaction by first depositing some coins into a special address associated with the Lightning Network; the user then opens a payment channel which allows them to transact with other users of the Lightning Network. All transactions are performed off-chain and the Lightning Network keeps track of balances.

A user can perform as many off-chain transactions as they want. Finally, once a user is done making payments on the Lightning Network they finish by closing their payment channel. Closing a channel has the effect of settling by recording the final changes in balance on the blockchain.

In this way, the Lightning Network and other layer 2 solutions allow users to bypass expensive miner fees by performing the majority of transactions on secondary layer networks. The blockchain is used mainly to synchronize balances whenever a payment channel is closed and changes need to be recorded.

This is what is meant by the blockchain becoming a settlement layer. Transactions are conducted off the blockchain, thereby preventing the chain from bloating and growing in size too much. Off-chain transactions are periodically totaled and permanently recorded on the ledger.

## Blockchain as a Base Layer

Lightning is only one example of a layer 2 network; another is PeerAssets, which is a layer 2 token protocol developed for Peercoin. There will be other examples as time goes on. Eventually features and improvements will build to the point where we will have layer 3 networks and beyond. All future layers remain completely dependent on the security of the base layer blockchain. Without a secure base layer acting as a solid foundation, everything built on top will be jeopardized.

Satoshi’s original vision - a peer to peer cash system where transactions are typically conducted on chain - is no more, at least with regards to Bitcoin. Developers have instead elected to focus on an alternate scaling solution that limits the amount of on-chain transaction volume.

## Putting it all Together

Let’s summarize now to make sure we fully understand the reasoning behind the decisions of the developers.

A block reward is distributed with every new block, which compensates miners for the costly work they perform and incentivizes them to continue producing new blocks and security for the network. The block reward is on a set schedule where it will continue decreasing until it becomes zero. Voluntary user transaction fees are not a reliable replacement for block rewards because users are motivated to save as much on fees as possible. Bitcoin developers therefore instituted a 1MB block size limit.

As a result of this limit, when a block fills up with transactions, users are incentivized to pay higher fees to have a better chance of getting their transactions accepted by miners. These raised fees are profitable enough for miners to sustain themselves in the absence of block rewards. However these raised fees make it too expensive for normal users to transact on the blockchain.

In response, developers refocused the Bitcoin blockchain from a peer-to-peer cash system to a base layer settlement network. This base layer blockchain works in conjunction with other layer 2 networks such as Lightning, which makes it possible to perform lots of quick and inexpensive off-chain transactions. The high fees of on-chain transactions push users conducting micro-transactions off the blockchain onto these layer 2 networks where transactions are more affordable.

These developments accomplish a number of things. Miners receive their proper compensation to continue operating. Micro-transactions are off-loaded onto layer 2 networks, which makes fees cheaper and speeds faster for users and prevents the blockchain from bloating and growing too fast from too many on-chain transactions.

Any on-chain transactions will be high value transactions where the fees spent are marginal compared to the value that was exchanged. Layer 2 networks also finally make it possible for Bitcoin to scale to support global transaction volumes and usage levels. With layer 2 networks, the number of possible transactions is no longer limited by the block size.

## Fee Competition Between Miners & Secondary Layers

One issue that remains to be explored is how the existence of layer 2 networks will impact miner profitability. Off-chain transactions on layer 2 networks do not provide any fees to Bitcoin miners. Only on-chain transactions do this. It would appear then that Bitcoin miners and layer 2 networks are in direct competition with each other when it concerns fees, maybe even incompatible.

However this is untested since layer 2 networks are still new and have not seen significant adoption yet. Some even argue that the low fees of layer 2 networks will actually attract more on-chain transactions, resulting in higher profitability for miners. Price is also a major factor. If bitcoin were high priced, miners may be able to remain profitable off few very expensive transactions, even when 90% of users are conducting off-chain transactions on layer 2 networks. The crypto industry is currently in unexplored territory and it remains to be seen how these new technologies will impact blockchain security.

What we can say for sure however is that Peercoin and proof-of-stake were intentionally designed without this conflict over transaction fees. Peercoin by design is not dependent on transaction fees for security, therefore it is 100% compatible with layer 2 networks. This will be fully explained later in the article.

---
