# 6. Centralization of Bitcoin

Years of operating in the wild have exposed weaknesses in Bitcoin’s proof-of-work protocol. Blockchains can only be considered trustless if power is distributed among many network validators; proof-of-work’s design, however, has centralized its validators (miners) over time. This centralizing effect is inherent in the economics governing the proof-of-work protocol and cannot be eliminated by any technical improvement or upgrade of the code.

## Mining is a Profit Driven Competition

Why is this? By its nature, proof-of-work incentivizes competition between its validators who, as miners, compete with each other to mine blocks, add them to the chain and receive their block reward of new coins.

To stay ahead of the competition, miners reinvest their profit in better mining equipment that increases their hashes per second. This allows a miner to make more guesses per second, which gives them a higher chance of solving a block’s problem before other miners. Miners who can afford to purchase this specialized mining equipment will have an edge over others when it comes to earning block rewards.

In the beginning, Bitcoin miners were plentiful, distributed and used basic computers to mine blocks. As time went on, miners began using more powerful and expensive machines to increase their hashing power. Eventually miners graduated to ASICs, which are customized chips designed specifically for mining. At each phase, miners were either forced to upgrade to faster and more efficient equipment in order to keep up with the competition, or face becoming obsolete as their block rewards dried up.

## Domination by Mining Pools

The constant upgrading and lack of profitability led to a situation where smaller miners with obsolete equipment could no longer compete with the hashing power of larger miners. In order to increase the lifespan of their equipment, these small miners began pooling their processing power together into mining pools. Instead of block rewards being distributed to individual miners, mining pools split rewards among participants, allowing miners with outdated equipment the chance to receive smaller but more consistent rewards so they could continue competing a little while longer. Even with pools though, eventually mining equipment became obsolete and miners were either forced to upgrade or drop out completely.

Due to lack of profitability and the inability to compete, what began as a distributed network with a large group of individual miners has slowly devolved into an increasingly centralized operation with a small number of larger mining pools. The operators of these mining pools have been able to increase their power and influence over the network because they are now the ones responsible for submitting the majority of new blocks. Individual participants of a pool can contribute their hashing power and collect their partial block reward, but only the owners of the pools themselves can build new blocks and submit them to be added onto the chain. As a result, the Bitcoin mining industry has come to be dominated by a handful of pool owners.

## Majority Attacks

This is precisely the situation that blockchains were designed to move away from, centralized control by entities that need to be trusted. If one of these large mining pools were able to obtain enough control over the hashing power, or if a few of the larger pools got together and colluded, they could perform a number of actions against the network and its users.

For example, they would be able to control who gets their transactions included in new blocks, effectively having the ability to temporarily prevent the processing of transactions from certain individuals. Someone having their transactions censored by a misbehaving mining pool would need to wait until a different pool produced a block that included their transactions.

Even worse is a double spend attack against the network in which the mining pool attempts to spend the same coins twice. This attack could potentially destabilize the network and compromise the trust users have in the system itself. Naturally, users are only supposed to be able to spend the coins they own once. Double spends have already been successfully performed against other smaller proof-of-work blockchains besides Bitcoin, so it is a possibility this could occur again in the future if the centralization of miners worsens.

With that said, miners are financially dependent on the Bitcoin network through the dedicated mining hardware they own. The sole purpose of this hardware is to mine proof-of-work networks like Bitcoin. It is useless for any other computing task. Therefore directly attacking the network in this way may render all this hardware useless as trust in the network is lost. The potential loss of invested hardware acts as a financial deterrent against attempting double spends against Bitcoin. This deterrent however would do nothing to stop a government sponsored attack with the sole purpose of bringing down the network. If such a situation ever came about and a mining pool was committing the attack, the only thing that could be done to stop it is for individual miners to withdraw their hashing power from that misbehaving pool and move it to another.

## Unsustainable Energy Consumption

Centralization of mining power is not the only major concern. The level of energy consumption by miners to keep the network securely operating is growing larger by the day. While it is difficult to accurately determine, current estimates put Bitcoin energy expenditure in the same league as the consumption of some medium sized countries in an entire year, and this is only expected to increase as time goes on. Such energy consumption just to secure a distributed network and prevent cheating is incredibly wasteful, especially when other blockchains like Peercoin exist which have been proven to drastically reduce the level of energy usage.

## Geographical Centralization of Miners

Another problem concerning energy usage is the fact that most large miners operate in areas where there are low energy costs. Lower energy costs make it possible for miners to keep more of the profit they earn from block rewards. The problem with this is that it has had the effect of centralizing the majority of mining in countries where the electricity is inexpensive.

Centralizing mining power in a single country exposes those miners, and therefore the network itself, to the possibility of being targeted by that country’s government. This could include heavy regulations, shutting down mining operations altogether or even forced censorship of transactions. A truly distributed network like Peercoin has security providers that are spread globally, making it incredibly difficult to influence or shut down the network.

## Diverging Interests of Miners & Users

It should also be noted that miners may not personally have the interests of the blockchain in mind when it comes to long-term development. Miners are first and foremost profit generating businesses. Their main priority is making money, therefore they may favor developments that may place them at odds with those who use the network (i.e. bitcoin holders). When considering technical improvements and upgrades to the network, for example, miners may want one thing while users want something else. The desires of both groups fall out of alignment, making governance and protocol rule changes difficult, even impossible.

This may even lead to situations where miners act against the development of the network, favoring short-term rewards over long-term growth. In a severe case where miners refused to upgrade to the newest version of Bitcoin, other validation nodes were forced to start rejecting their new blocks; this caused miners that refused to upgrade to lose block rewards. Validators across the network held miners hostage financially, forcing them into a situation where they had to upgrade in order to continue earning money to pay for their mining operations.

This ability creates a sort of separation of powers where block validators on the network can force miners to upgrade the blockchain to a new version by rejecting their blocks and not providing them compensation. A better model however would be if the interests of both users and miners were aligned so that many of the toxic community disagreements between different factions were reduced, however a model like this is impossible with proof-of-work.

This ability creates a separation of powers where block validators on the network can force miners to upgrade the blockchain to a new version by rejecting their blocks and not providing them compensation. A much better model however would be where the interests of both users and miners were aligned so that many of the toxic community disagreements between different factions were eliminated. A model like this, however, is impossible with proof-of-work; only proof-of-stake which Peercoin operates on.

---
