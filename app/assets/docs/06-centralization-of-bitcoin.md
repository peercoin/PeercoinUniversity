# 6. Centralization of Bitcoin

Proof-of-work is not perfect however and years of operating in the wild have exposed many of its weaknesses as a distributed consensus protocol. Recall that a blockchain can only be considered trustless if there are many different network validators and power is distributed among them, which works to prevent collusion or outright majority control by a central authority.

Unfortunately, proof-of-work does not fit this model as its design has caused a large and distributed group of miners to naturally centralize over time. This centralizing effect is inherent in the economics governing the protocol and cannot be eliminated by any technical improvement or upgrade of the code.

## Mining is a Profit Driven Competition

By its very nature, proof-of-work is a consensus protocol that incentivizes heavy competition among its validators. As a money generating business, miners compete with each other to be the first one to mine a block so they can add it to the chain and receive their block reward of new coins.

In order to stay ahead of the competition, miners will reinvest their profit in order to purchase better mining equipment that is capable of increased hashes per second. This increased hashing power allows a miner to be able to make more guesses per second, which gives them a higher chance of solving a block’s problem before other miners. Miners who can afford to purchase this specialized mining equipment will naturally have an edge over others when it comes to earning block rewards.

In the very beginning, Bitcoin miners were plentiful, distributed and they used basic CPUs to mine blocks. As time went on, the CPU became obsolete as miners began using their GPUs to increase their hashing power along with their chances of receiving block rewards. Eventually miners graduated to ASICs, which are customized chips that are designed specifically for mining Bitcoin rather than for general purpose use.

At each phase, miners were either forced to upgrade their equipment in order to keep up with the competition or face becoming obsolete as their block rewards dried up. The mining industry became similar to an arms race. Faster and more efficient mining equipment was being released that needed to be purchased by miners in order for them to remain profitable.

## Mining Pools

The constant upgrading and lack of profitability led to a situation where smaller miners with obsolete equipment could no longer compete with the hashing power of larger miners who used better equipment. In order to increase the lifespan of their outdated mining equipment, these small miners began pooling their processing power together into mining pools. Instead of block rewards being distributed to individual miners, mining pools split rewards which were partially shared among all participants of the pool in proportion with the overall hashing power they each contributed to mining a block.

Mining pools became necessary once the probability of mining a block took years for small miners working alone by themselves. Pools allowed smaller miners the chance to pool their computing resources together and receive smaller but more consistent rewards so they could continue competing a little while longer. Even with pools though, eventually mining equipment became obsolete and miners were either forced to upgrade to something better or drop out completely.

## Difficulty Adjustments

Difficulty adjustments also had a large impact on the profitability of outdated mining equipment. Over time mining technology advances and faster and more efficient mining equipment is released onto the market. Due to economies of scale, miners with larger operations can afford to be the first ones to upgrade to the newer equipment when it is first released, giving them an edge over their smaller competitors.

As a result of the faster speeds and increased hashing power of the newer technology, blocks start getting solved faster than the usual ten minutes. In order to maintain the ten minute timespan between blocks, the protocol detects miners are solving blocks faster than usual and in response it automatically adjusts the difficulty of the problem that needs to be solved for each block.

A higher difficulty increases the amount of hashing power required to solve a block, which has the side effect of increasing the time it takes to solve a block so that blocks are always able to maintain a consistent time span of around ten minutes. However a difficulty adjustment upward also has the effect of forcing miners who cannot afford to upgrade their hardware to either drop out altogether or join a mining pool so they can maintain their profitability.

## Domination by Large Mining Pools

Due to lack of profitability and the inability to compete, the number of miners in Bitcoin have dwindled over time. What began as a distributed network with a large group of individual miners has slowly devolved into an increasingly centralized operation with a small number of larger mining pools. The operators of the mining pools have been able to increase their power and influence over the network because they are now the ones responsible for submitting new blocks.

The individual participants of a pool can contribute their hashing power to the pool and collect their partial block reward, but only the owners of the pools themselves can build new blocks and submit them to be added onto the chain. If an individual pool comes close to owning the majority of the hashing power on the network, participants of that pool are forced to redirect their hashing power to smaller pools in order to prevent the larger pool from gaining too much power over the network.

## Majority Attacks

This is precisely the situation that blockchains were designed to move away from, centralized control by trusted entities. If one of these large mining pools were able to obtain majority control over the hashing power or a few of the larger pools got together and colluded, they could perform a number of actions against the network and its users.

They would be able to control who gets their transactions included in new blocks, effectively having the ability to temporarily prevent the processing of transactions from certain individuals. Someone having their transactions censored by a misbehaving mining pool would need to wait until a different pool produced a block that included their transactions.

Worse though is a double spending attack against the network in which the mining pool attempts to spend the same coins twice. A double spend attack could potentially destabilize the network and compromise the trust users have in the system itself. In reality users are only supposed to be able to spend the coins they currently own.

Breaking the rules by being able to spend the same coins over and over again would constitute a severe violation of the trustless nature of the blockchain. Double spends have already been successfully performed against other proof-of-work based blockchains besides Bitcoin, so it is not out of the realm of possibility that this could occur in the future if the centralization of miners is allowed to worsen.

With that said, miners are financially dependent on the Bitcoin network through the dedicated mining hardware they own. The sole purpose of this hardware is to mine proof-of-work based networks like Bitcoin. It is useless for any other computing task. Therefore directly attacking the network in this way may render all this hardware useless as trust in the network is lost.

There are other proof-of-work blockchains that miners could switch to in the event Bitcoin falls victim to an attack, however a successful attack against Bitcoin may completely destroy confidence in proof-of-work as a security protocol. In this case there would be no safe haven for miners because all proof-of-work based networks would suffer incredible price drops from the loss in trust.

This possibility acts as a financial deterrent against attempting double spends against the network. Rational miners would not want to destroy their golden goose. This deterrent however would do nothing to stop a government sponsored attack with the sole purpose of bringing down the network. If a pool is the one committing the attack, then the only thing that could be done to stop it is for miners to withdraw their support from that pool.

## Unsustainable Energy Consumption

Centralization of mining power is not the only major concern though. The level of energy consumption by miners in order to keep the network securely operating is completely unsustainable and only growing worse by the day. While it is difficult to accurately determine, current estimates put Bitcoin energy expenditure in the same league as what some medium sized countries consume in an entire year and this is only expected to increase as time goes on. This increasing energy consumption just to secure a distributed network and prevent cheating is incredibly wasteful, especially when other consensus protocols exist which have been proven to drastically reduce the level of energy usage.

## Geographical Centralization of Miners

Another problem concerning energy usage is the fact that most large miners operate in areas where there are low energy costs. Lower energy costs make it possible for miners to keep more of the profit they earn from block rewards distributed to them by the network. The problem with this is that it has had the effect of centralizing the majority of mining in one country where the electricity is inexpensive.

Geographically centralizing the majority of mining power in a single country opens up those miners and the network itself to the possibility of being targeted by the local government. This could include heavy regulations, the potential for shutting down mining operations altogether or even forced censorship of transactions. A truly distributed network needs to have global security providers who are based around the world. A worldwide security setup like this makes it incredibly difficult to influence or shut down the network.

## Diverging Interests of Miners & Users

It should also be noted that miners may not necessarily have the interests of the blockchain in mind when it comes to the long-term development and evolution of the network. Miners are first and foremost profit generating businesses. Their main priority above all else is making money, therefore they will inherently favor developments to the network that may place them at odds with users of the network. When considering technical improvements and upgrades to the network for example, miners may want one thing while users want something completely different. The desires of both groups end up out of alignment, making governance and protocol rule changes difficult.

This may even lead to situations where miners act against the network, favoring short-term rewards over long-term growth. There have been examples of this in the past, anywhere from miners mining empty blocks to spreading misinformation and fearmongering on blogs and forums in order to turn public perception in their favor.

In a severe case where miners refused to upgrade the network, other validation nodes were forced to start rejecting new blocks from miners who would not upgrade to the newest version of Bitcoin. This caused miners that refused to upgrade to lose block rewards, since their blocks were no longer being accepted by validation nodes until they upgraded. Validators across the network basically held miners hostage financially, forcing them into a situation where they had to upgrade in order to continue earning money to pay for their mining operations.

This ability creates a sort of separation of powers where block validators on the network can force miners to upgrade the blockchain to a new version by rejecting their blocks and not providing them compensation. A better model however would be if the interests of both users and miners were aligned so that many of the toxic community disagreements between different factions were reduced, however a model like this is impossible with proof-of-work.

---
