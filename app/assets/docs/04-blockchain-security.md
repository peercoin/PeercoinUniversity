# 4. Blockchain Security

Although blockchain technology has the potential to transform finance as we know it, it’s important to realize that not all blockchains are the same. When choosing a blockchain to operate on, the most important factor to consider is the chain’s underlying security. If the blockchain is not secure, then it's like building on top of quicksand. At some point it may be compromised, which could result in the total loss of all funds. It’s not just a question about whether a blockchain is secure right now, but whether it will continue to be secure in the future.

## Collusion

A blockchain can only be considered trustless if there are a sufficient number of security validators and they are widely distributed around the world. Blockchain security stems from the fact that there are many validators and power is decentralized among them. This prevents collusion among validators as a great majority are likely to continue working in the interest of the network and its users. The few who attempt to collude and defraud will have no impact because they will be highly outnumbered by the many who play by the rules.

If a blockchain's security protocol contained a design flaw that caused the number of validators to shrink over time then that would result in a highly centralized blockchain, which would completely defeat the purpose behind the technology as it could no longer be considered trustless. The fewer validators there are securing a blockchain, the more centralized it becomes and the more trust creeps back into the system making it just like the centralized organizations that we tried leaving behind.

As validators dwindle in number, the few that remain end up having a larger degree of influence and control over the network, which means there is a much higher chance they could collude and perform a double spend attack against the network. If a single entity somehow managed to gain majority control over the blockchain, then users of that blockchain would be at the mercy of that entity and would need to trust and hope that it would continue working in their interest instead of sabotaging the network for personal gain. The ideal blockchain is if validators continue to remain thoroughly decentralized so users of the network never have to trust anyone.

## Consensus on a Single Shared Truth

A blockchain network's ability to preserve its level of decentralization over time is highly dependent on how its distributed consensus protocol is designed. There are many types of distributed consensus protocols, but the two most well known are called proof-of-work and proof-of-stake.

These two consensus protocols operate in very different ways, but their overall goal is the same; to bring validators to consensus so they can agree on a single shared version of the truth regarding the state of the blockchain and its ledger, while at the same time preventing malicious or hostile actors from exploiting and derailing the system.

It is possible for certain validation nodes across the network to hold slightly different versions of the public ledger. This can happen if, for example, nodes are unreliable or slow because of issues with network latency, or because they are acting maliciously and run by people trying to fool the system by passing off their tampered version of the ledger as the real one.

Regardless of the reason for any disparity, it is the purpose of the consensus protocol to strive to keep all validation nodes synchronized so that a single version of the blockchain can be decided on, used and followed by all the participants of the network.

## Incentivizing Validator Security

A consensus protocol achieves all this by incentivizing validators with monetary rewards in order to motivate them to perform validation and transaction processing work for the blockchain and its users. There are different types of validators however and not all of them receive this compensation for their work.

A full node is a validation node that has a full copy of the blockchain downloaded. There are three types of full nodes. The first type is run by individual volunteers or hobbyists who just want to help support the network, and so perform verification of transactions and blocks for free.

The second type are full nodes that are run by large entities such as merchants, exchanges and payment processors. These nodes are voluntarily operated, but the ability to monitor new transactions can give these entities benefits that can be passed on to their customers.

The third type of validator is only responsible for the task of building and adding new blocks of transactions onto the chain. These block producing nodes are different however and receive automated payments for their service from the network itself. In this way the blockchain literally pays for its own security maintenance and upkeep. Whether this validator is required to hold a full copy of the ledger differs with each blockchain. Block producers in Bitcoin are not required to hold a full copy of the ledger, whereas it is a requirement in Peercoin.

Validator roles can be thought of in this way. Simple validators who voluntarily run full nodes work to perform validation of transactions and blocks. Block producers however make it possible for the network to settle on a common truth every 10 minutes. If there was no consensus protocol to help decide who can produce the next block, anyone would be able to produce and submit a new block to the rest of the network. Validators would try verifying the transactions and blocks that were submitted to them, however each validator would end up checking a different block which would make it impossible to determine which block gets added to the chain. The consensus protocol ensures it is possible for these validation nodes to settle on a common state. Once this state is decided, it is broadcast to the rest of the network so that all validators work to verify the same block of transactions. It is a way of putting all validators in the network on the same page.

The way in which a blockchain’s consensus protocol is designed to incentivize validators to produce blocks is precisely what causes them to either retain or lose their level of decentralization over time. This is exactly what we need to learn in order to develop an understanding of which blockchain protocols are designed for long-term security and which are not.

---
