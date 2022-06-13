# NFTPriceBot
The aim of this bot is to find the price of an NFT depending on its rarity.

We begin by querying the collection for the following:
* The rarity and sale price of a Token
* The attribute list and their respective rarities

If we have the percentage occurance of an attribute, we can determine the rarity. Looksrare has an excellent post regarding rarity calculations on their medium.
The example given is that if an attribute appears 10 times, then its score would be (1/(10/Size of collection).

Here is a list of things we should consider:
* Should we find NFT prices valued in ETH/DAI/USDC?
* How do we deal with the creation of M1 and M2 mutants via serums?
* How do we deal with the evolution of fair value over time?
