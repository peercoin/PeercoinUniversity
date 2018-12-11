# 5. Bitcoin & Proof-of-Work Consensus

In order to create the world’s first decentralized blockchain, Bitcoin’s original inventor Satoshi Nakamoto had to figure out how to solve a number of different problems. How to get a large distributed group of validators to agree on the true version of the ledger. How to incentivize and motivate those validators to process new transactions and provide overall security for the blockchain network. How to prevent malicious and hostile entities from being able to easily alter transaction records by tampering with the ledger’s history of events. How to space out the production of new blocks so the time between each one is consistent and predictable.

The brilliance of Satoshi is in combining multiple fields of study in order to solve all these problems. Some of these fields include incentive engineering, cryptography, game theory and computer science. This specific combination led to a solution for Bitcoin known as proof-of-work consensus, also referred to as Nakamoto consensus.

## Mining Blocks by Solving Problems

The specific set of validators that are responsible for producing new blocks in Bitcoin are called miners. The block production process itself is called mining. In order for a miner to be able to add their newly created block as the next link in the chain, they are first required to do the work necessary to solve a difficult math problem. The problem itself involves making lots of random guesses in order to find a solution that matches.

There is more than one possible guess that will work as an answer for each problem. Every time a miner makes a new guess, that guess is first combined with some other relevant data and then it is run through a hashing algorithm, which is a special program that checks and verifies whether the guess is correct or not as an answer to the problem. The first miner that is able to solve the problem is the one who gets the honor of adding their new block onto the chain.

## Hashing Algorithms

The hashing algorithm is very important to the overall mining process for more than just simple verification of whether the problem has been solved or not. When a hashing algorithm is fed some data as input, the algorithm takes all that data and converts it, producing output data in the form of a small string of numbers and letters. This output data is called a hash. A hashing algorithm only works in one direction, which means the hash that is produced from the input data will always result in the same string of numbers and letters as the output.

For example, you could take an entire book as input data and run it all through this algorithm and it will always produce the same resulting hash no matter how many times you do it. If however you were to change just a single character in the book and run it through the algorithm again, then the resulting string of numbers and letters would be completely different. This makes it possible to verify whether something in the book or the input data has been tampered with, even if it is something as simple as changing a single character.

If the resulting hash features the same string of numbers and letters every time it is run through the algorithm, then you can always be sure that the input data was not tampered with. Every single block in the blockchain contains its own hash, which acts as a guarantee that the contents of each block is true and has not been tampered with.

## Searching for a Valid Hash

In order to find an answer to the problem, miners need to combine three pieces of data together, the hash from the previous block, the transactions from the block they are currently working on building and a random guess. They run this combined input data through the algorithm in order to produce a hash. The resulting hash of this data is then checked to see if it works as an answer to the original problem.

If it matches then the hash is considered valid. If not, then it is considered an invalid hash and miners will repeat this process over and over again by changing their guess and hashing all three pieces of data until they are able to find a hash that is valid. When a miner finally finds a valid hash, then they can be sure that the problem has been solved.

Once a miner succeeds in finding a valid hash, they broadcast their new block along with their correct guess to the rest of the validators on the network, who then take this guess and verify whether it is correct by also running it through the algorithm to see if they can produce the same valid hash. This makes it possible for validators across the network to quickly verify and prove that the miner did the necessary work to solve the problem.

If the hash produced from the three pieces of data can be verified by others as valid, then the block will be accepted by participants of the network and added as the next block in the chain. If however validators are unable to produce a valid hash when doing their verification check on the miner’s guess, then the new block will be rejected and not added onto the chain because validators were not able to prove that the miner did the work to solve the problem. In the case of rejection, validators will just wait until another miner submits a new block that can be accurately verified.

This whole process may sound complicated, but it is vital in order for proof-of-work based blockchains to function properly. To simplify it into several sentences, a miner basically makes a number of guesses until they find the correct answer to a problem. Once the correct answer is found the miner lets other validators on the network know so they can all verify whether the answer they got is correct. Once verified, the new block is then added onto the chain.

This process is not done manually by miners, but automatically using computer processing power. Modern computers for example are able to try out thousands of combinations of hashes per second, so miners are capable of making many guesses very quickly.

## Block Rewards

The process of mining blocks is very expensive because of the use of limited resources like electricity to power the computers that do the hashing. To make up for this cost, every time a miner solves a problem and their block is accepted by the network, that miner receives a block reward in the form of new coins. These new coins are created out of thin air by the network with every new block that is produced. This is how new currency is introduced into the supply and distributed over time.

Validators in Bitcoin are called miners because they are always digging for new coins by fulfilling the requirements of producing new blocks. Miners then sell the new coins they earn on the market to cover their costs while keeping the profit for themselves or reinvesting it in better mining equipment, which allows them to increase the hashes per second they perform along with their chances of earning more block rewards.

## The Cost of Lying

The purpose of requiring miners to solve a problem before being allowed to add their new block of transactions onto the chain is to make it difficult, expensive and costly to lie. Mining is a money generating business and it can be very costly to mine blocks that contain fraudulent transaction data.

If a miner for example tries to include invalid transactions in the block they submit or they attempt a double spend and it is detected by the network’s validators, that miner risks having their block rejected by the network. A rejected block means the miner will forfeit their block reward and they will end up losing any money they spent on electricity to mine that block. Bad behavior is punished and is therefore money losing behavior. This results in miners having a financial incentive to tell the truth and play by the rules.

This process also explains how blockchains are designed to be immutable and unchangeable. For example, if a miner tried submitting an alternate version of the blockchain history where they altered previous transactions from a specific block in the distant past, validators would be able to detect the change because the hash of the altered block would no longer be considered valid.

It is similar to the previously mentioned book hashing example. A miner that makes a change to a transaction from some block in the past is simultaneously changing the input data that was originally used to produce the hash for that specific block. Changing any transactions in that block will also change the original input data, which will cause the hash that is produced from that data to no longer work as a valid solution to the problem associated with that block. Network validators will detect this invalid hash and reject the altered version of the blockchain. The miner will then lose any money they invested in attempting to alter the blockchain.

## Blockchain History Protection

In order to get around this detection mechanism a miner would need to spend the electricity required to prove they did the necessary work to find a valid hash for the altered block. Basically this means they would need to spend the resources necessary to mine the altered block over again, however even if the miner did this there is still a problem.

Recall that every block’s hash is produced by including the previous block’s hash as one of the three pieces of input data. This causes the hash contained in every block to be connected to the hash of the block that comes directly before it, which means every single block in the chain is cryptographically linked.

Because of this, if you try to alter data in one block the hash for every subsequent block will become invalid. This means that the only way to truly alter a block in the past is to mine that block over again and every single block that comes after it until the end of the chain. You would literally need to spend the resources to prove that you did the work to find a valid hash for every single block after the one you altered. Currently it would cost billions of dollars to mine Bitcoin’s blockchain from scratch in order to change something, which is financially infeasible even for the very wealthy.

Proof-of-work consensus therefore acts as a financial deterrent against altering the history of the blockchain by forcing a massive cost on those who try to attempt it. By rewarding miners, it incentivizes them to tell the truth and submit blocks with accurate transaction data while also punishing those who attempt to cheat the system with the risk of losing invested funds.

In addition, the requirement of solving a problem first before being permitted to add a new block onto the chain has the side effect of creating a time delay so that new blocks end up being spaced out by a time span of about ten minutes, which keeps block times consistent and predictable. In this way, proof-of-work consensus solves all the main problems that Satoshi faced when trying to invent a decentralized Bitcoin.

---
