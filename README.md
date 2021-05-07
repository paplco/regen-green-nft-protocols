# The Regen Network Green NFT
### [Re: [Regen Bounty] tokenized carbon credit wrapped NFTs](https://gitcoin.co/issue/GreenNFT/GreenNFTs/3/100025306)
## Introduction
This paper provides three approaches to using Regen technology, combined with NFT technology, to create an integrated system, which incentivizes the use of tokenized carbon credits to support meaningful and impactful ecological stewardship, and planetary regeneration.
## Assumptions
* A Green NFT Protocol or Service is needed to reduce the carbon footprint of NFT transactions, and should be one of the strategies employed to help achieve RN’s goal of planetary regeneration.

* A Green NFT Protocol or Service would still be needed even after Ethereum 2.0 transitions PoW to PoS, reducing transactional energy to just 1% of its former consumption. [ETH to cut energy usage by 99%](https://spectrum.ieee.org/computing/networks/ethereum-plans-to-cut-its-absurd-energy-consumption-by-99-percent)

* RN will continuously provide an ample supply of tokenized eco credits to make available to Green NFT marketplace for purchasing.

## On what basis should we assume Green NFTs are needed?
> A single NFT can involve many transactions. 
These include minting, bidding, cancelling, sales and transfer of ownership. If we were to break down the footprint by transaction type, we get:
Minting: 142 kWh, 83 KgCO2.
Bids: 41 kWh, 24 KgCO2.
Cancel Bid: 12 kWh, 7 KgCO2.
Sale: 87 kWh, 51 KgCO2.
Transfer of ownership: 52 kWh, 30 KgCO2.
This generally pushes the footprint of a single NFT into hundreds of kWh, and hundreds of KgCO2 emissions, and often higher. ([source](https://jisuartist.medium.com/debunking-everything-about-the-technology-ecological-impact-of-nfts-cryptoart-60ee09bd00ed))

*0.211 metric tons of CO2 produced per NFT.* And that does not consider how many times its ownership may be transferred.

A metric ton of carbon offsets can range from $1 to $50 per ton. 

[Nori](https://nori.com) sells NRTs (Nori Carbon Removal Tonne) offsets for $15/ton + 15% transaction fee, adding a cost of about $3.17+0.48 to offset the average NFT.

*A total of $4.65* is a reasonable add-on price and there should be room to even add a premium “DeepGreen” registration level to help cover non-green NFTs, or to allow the purchaser to include possible future transactions as well for their GNFT.

There are 20 million+ NFTs available just on [OpenSea](https://opensea.io/) alone. Thus, the market for “greening” NFTs could have the potential of bringing in hundreds of millions to help support ecological regeneration projects.

Sounds like a Green NFT solution could have a viable market.

## How could RN Goals be met by offering Green NFT services?

The main goal of RN is to Regen Network align economics with ecology to drive regenerative land management.

Or, in other words, to economically incentivize actions that encourage regenerative outcomes. 

The desired outcome for a Green NFT is to incentivize marketplace participants to contribute to regenerative ecological impact organizations.

So the goal is not really to create a new method for minting NFTs, unless that is the best means to the end goal, but how can we incentivize what is already in place.

Why compete with the enormous markets and momentum within the current ETH NFT space? Why create/deploy a competing Green NFT format on [IRISnet](https://www.irisnet.org/docs/features/nft.html#features) or Cosmos? Or via other blockchains such as [NFTree.org and Crown Platform](https://nftree.org/)?

While the approach of creating NFT alternatives could prove viable, and have many use cases, including: the ability to set a standard for an *Internally and Eternally Green NFT* by programming its mechanics to automatically send an offsetting fee to a wallet address that supports ecological regeneration.

Why not first harness the strongest stream of energy, by providing an easy onramp for the ETH NFT market, which is already well underway, having reached a very high network effect.

In addition, bridging in other communities with an onramp, would help bring awareness of REGEN to the ETH and blockchain services at large, and perhaps even inspire ETH developers to create a new standards beyond ERC-721, that would require a certified carbon neutralizing fund address to be baked into the smart contract the time of minting, and would need this fee paid to execute the transfer, just as gas is required (achieving the *Internally and Eternally Green NFT*).

## Mechanisms for Green NFT Creation

### Possible Methods:

*Bundling with NFT Purchases* - Allow GNFTs to be bundled alongside each NFT sale, within each NFT exchange/marketplace. 
*Embed GNFT functionality into Smart Contracts* - the “green” functionality would exist within the NFT for the duration of its lifetime.
*GNFT Registry & Wrapping Service* - a powerful and flexible solution that puts RN at the center of Green NFTs.

### Method 1 - Bundling with NFT Purchases

Allow GNFTs to be bundled alongside each NFT sale, within each NFT exchange/marketplace. 

A one-time mark-up, with the price set by the NFT marketplace, using pre-purchased credits acquired in bulk from RN.

Although this is the simplest approach, and would not require a large amount of technical development, it does not track the NFT throughout its lifetime.

However, it would be a great first step in achieving RN goals.

### Method 2 - Embed GNFT functionality into Smart Contracts

One of RN’s goals is to become an open source standard for ecological impact projects. In line with this goal, the Green NFT project could be approached by creating a new open sourced protocol that could be adapted by multiple chains and in multiple use cases.

Achieving the *Internally and Eternally Green NFT* by leveraging the internal [programmability of NFTs](https://medium.com/cardstack/whats-in-your-nfts-e4e45ebc51da) and the Smart Contracts that govern them via the creation of a standardized protocol.

By embedding the code to route a portion of the Smart Contract’s payment execution to a certified beneficiary regenerative organization, then each time a transaction takes place, a predetermined portion of the fees would be routed to the beneficiary’s wallet, or organization’s wallet or general pool wallet.

Although the “Greenness” of the NFT could be advertised to incentivize its purchase and give recognition to the altruistic artist, the transaction would take place “under the hood” regardless, as a requirement for the execution of the contract.

The beneficiary wallet(s) would be added and the percentages of fees (or fee curves) set at the time of minting the *Internally and Eternally Green NFT*. These wallet addresses could be hard-coded in, or updated programmatically via the appropriately designed functions.

An artist could choose from a variety of good causes, impact organizations listed on a Regen Registry of Organizations, to bundle with their NFT. The beneficiary could also be any charitable organization.

### Method 3 - GNFT Wrapping & Registry Service

For NFT marketplaces, there could be an open API calculator that would give the current price to neutralize any NFT in its current state, based on its public ledger history.

#### # Wrapping

The Wrapping Service would expose an API to query NFT transaction history on the blockchain explorer, and calculate the cost to neutralize the NFT.

The Green NFT wrap could be applied any time: 
* Time of creation (minting)
* Time of sale (transferring)
* Or voluntarily by the holder of the NFT

This would broaden the use-cases, the flexibility of use, and allow RN to iterate on the wrapping functionality as the industry evolves.

The wrapping service would be accessed through a Regen web app hosted at a location such as https://greenft.regen.network, using a wallet such as Keplr or Metamask.

The web app would use the Regen Green NFT API to query and submit transactions on behalf of the wallet / NFT holder.

In addition, the Regen Green NFT API would be public and open to query for verification and/or registration of NFTs by NFT marketplaces and owners.

#### # Registry

RN Network would keep a registry of Green NFT Beneficiaries. The Green NFT purchaser can select the beneficiary of choice, or if left blank, RN would select the beneficiary organization, or put funds into the general pool.

Types of Beneficiary Organizations
* Carbon Neutral action organizations
* Social Impact organizations
* Regeneration Projects
 
##### A Regen Network Effect via Method 3

Regen will list the beneficiary organizations, and this directory could list which art pieces are in circulation and which organizations are benefiting from them; the artist could be credited as well if so desired, thus incentivizing the “greening” of their art in order to achieve greater exposure.

So besides the intrinsic rewards gained by the artist, the artist would also receive notoriety throughout the Web 3 community, being listed on Regen Green NFT registry, which could have leaderboard functionality to show which artists have raised the most for which Impact/Regeneration Organizations.

In addition, buying and selling Green NFTs will be more desirable because the buyer will see which Impact/Regeneration Organization will benefit when purchased, and subsequently, each time bought and sold.

A small static image (such as that used with SSL certification badges) would be hosted on a RN domain such as https://certified.regen.network/assetRegistrationId, and anyone would then be able click to verify the carbon neutrality of NFT (or any other product or asset added to the RN Registry), thus bringing more exposure to the RN project. 

Marketplaces and apps and artists would be able to display their RN Green Certified badge alongside qualifying NFTs.

#### Additional Concepts

* An NFT owner could choose a DeepGreen level, and pay double the cost, to help contribute more to beneficiaries and to help offset other NFTs that are not green, and covering it for future transactions. 

* A pointer to the last covered transaction would be stored in the registry. Thus a green NFT can lose its green status.

* An NFT can be de-wrapped and re-wrapped by the asset owner, using the RN Green Wrapping Service. Each action incurring fees, and distributing payouts to the beneficiaries included in the wrapped layers.

* The RN Green NFT Registry would track the amount of times an NFT has been wrapped, and the list of beneficiaries and the percentage payouts to be distributed to each of their wallet addresses.

* The cost to query the registry for a carbon footprint calculation of an NFT could incur a small, fractional fee, added to a general pool supporting the project and green initiatives.

* A RN Wrapping Service could extend beyond NFTs and this functionality could be a general feature to add value to the Regen Ecosystem. Allowing investors to wrap their BTC or ETH into a regenerative network token such as $REGEN would allow depositors to use their crypto assets to create equity in the ecological spaces, supporting regenerative projects.

## Conclusions

The Green status of the NFT should encompass the entire life-cycle of the NFT, allowing it to become “green” at any point of the process: minting, purchasing, selling, or holding. Thus, *methods 2 or 3* would be the most effective in achieving this goal.

*Method 2* is the most granular in nature. Requiring the creation of a specific protocol and code base to be embedded within various types of Smart Contracts. This method would be a great pilot for the IRIS NFT network, to create a roadmap for *Internally and Eternally Green NFT* deployment, which could then be adopted by other blockchain networks.

*Method 3* has the greatest networking effect for RN, because of the Wrapping and Registration service, frequent placement and greater recognition of Regen as an ecological brand for ecological change can be expected. Method 3 also gives RN the greatest control while having a broad-reaching effect on ecosystems.

However, the approach that could create the soonest impact, would be *Method 1*, selling bulk credits to the NFT marketplaces, and allowing them to price and bundle them within their platform as they see fit.

{IA}
