# 9. Peercoin & Proof-of-Stake Consensus

Proof-of-stake is an alternative consensus protocol that was invented by Sunny King and Scott Nadal and first implemented in Peercoin in 2012. In a proof-of-stake based blockchain, coin owners are the ones who wield influence over the network, produce new blocks and secure the chain. Stakeholders of Peercoin effectively co-own the blockchain network, similar to how shareholders co-own a publicly traded corporation.

## Time as an Alternative Scarce Resource

In Peercoin, the process of validating new transactions and blocks works quite differently. Block producers in Peercoin are called minters rather than miners. In place of electricity, Peercoin emulates proof-of-work competition in its protocol by using time as an alternative limited resource. In order to select the minter that produces the next block, Peercoin’s protocol relies on a concept called coin age.

Coin age is a number that is derived from multiplying the amount of coins a minter owns by the number of days those coins have been held in their wallet. A minter who has a high coin age for example has both a high number of coins in their wallet and those coins have also been sitting in that wallet for quite a long period of time.

Peercoin’s protocol combines some amount of randomization with coin age in order to automatically select the next person who mints a block. A minter with a high coin age has a higher probability of minting the next block over a minter with a low coin age. There are no computationally difficult problems for minters to solve in Peercoin’s protocol. A minter’s chances of being selected as the next block producer rely specifically on the number of coins held and time in the form of coin age and some amount of luck.

## Time Based Rules & Restrictions

There are a number of rules coded into the protocol to keep minters with a high coin age from being able to dominate the process of minting new blocks. Minters are first required to hold coins in their wallet for a total of 30 days before they can become eligible to compete in the process of minting new blocks.

Once a new block is minted, a transaction is automatically generated where the participating coins that were used to mint that block are sent back to the minter. Basically minters automatically send the coins being held back to themselves. This automated transaction back to the minter of the new block causes the age of the coins to be reset. It is an automatic and forced transaction to move the coins that were used to produce a block, which resets the number of days that those coins have been held back to zero.

The minter then needs to start from scratch and wait another 30 days in order to be eligible to participate in the minting process again. This helps avoid a situation in which a minter is able to consistently produce blocks one after the other over and over again. The mandatory coin age reset institutes a 30 day wait time which gives other stakeholders a better chance of minting blocks.

A third rule also states that a minter’s probability of finding a new block reaches its maximum after 90 days. So after this period of time a minter’s stake reaches maturity and their chances of minting a new block are maxed out. All of these rules are put in place in order to prevent minters with high coin age from being able to hold a monopoly on the block generation process.

## Majority Attacks are Cost Prohibitive

The process of proving your stake produces new blocks and secures the network against malicious attacks. The proof-of-stake protocol also makes Peercoin much less susceptible to a double spend attack. For example, a potential attacker would need to own a majority of the total coin age of all coins participating in the minting process. Given that most coins are in personal wallets and not trading on exchanges, it would require a considerable investment in order to pull off such an attack.

A malicious actor would need to purchase enough coins from the market in order to try mounting an attack against the network. Attempting this vast purchase would cause demand to spike and the price per peercoin to skyrocket. Any attempt to acquire the amount of coins necessary to perform a successful attack would likely bankrupt the attacker in the process.

The only thing they would succeed at is driving the price of Peercoin out of the range of affordability. The attacker would likely run out of funds long before being able to complete their total purchase. Attempting to purchase more than half of minting coins in circulation is also likely more costly than attempting to acquire a majority of the hashing power that exists in proof-of-work blockchains.

## Attackers are Financially Tied to the Network

If by some miracle a successful attack was able to be performed, an attacker would only end up harming themselves in the process. In order to pull off an attack they would need to make a significant investment in Peercoin. A successful attack however would end up damaging the price of Peercoin and along with it the attacker’s original investment in the coins they used for the attack.

Further, any attempt by the double spender to cash out such a massive number of coins after a successful attack would only end up crashing the market price, which would also harm the attacker’s original investment. If the ultimate goal of a double spend attack is earning money then it should be considered counterproductive as the attacker would likely end up losing more funds as a result of the drop in value of the coins they purchased than they could ever hope to gain from a successful attack.

With proof-of-work consensus on the other hand there is no requirement to hold bitcoin in order to pull off a successful attack. All that is required is a majority of hashing power. In Peercoin however the attacker is financially tied to the network they are initiating an attack against through the coins they purchase.

As such, an attack of this nature would likely not be profitable and is best avoided completely. The only way an attack like this would make sense is if the goal of the attacker was to destroy trust in the network itself rather than use it to earn money. The attacker would need to be completely willing to risk losing their total financial investment in the network in order to achieve their desired result.

---
