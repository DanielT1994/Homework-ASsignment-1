# Homework Assignment 1 - RocketPool, $RPL, and rEth
![rocketpool](https://miro.medium.com/max/1400/1*f4VImbYjouJjszFAa0f5Dw.png)
## Overview and Origin


* Name of company

  Rocket Pool, and their governance token $RPL
* When was the company incorporated?

  Rocket Pool was founded on the 1st of September 2016, and is based in Brisbane, Australia.
* Who are the founders of the company?
 Rocket Pool was founded by David Rugendyke, a former developer at George Patterson Y & R. 


* How did the idea for the company (or project) come about?

  The idea of the company was founded by Ethereum switching from PoW (Proof of Work) to PoS (Proof of Stake). For an individual to operate a validator, a total of 32 Ether (the native token of the Ethereum network) is required. As of writing this is ~$135,000 AUD. Rocket Pool aims to decentralise the staking pool by lowering the amount needed to 16. This is done by having a Node Operator (NO) having 16 Eth, whilst those without 16 Eth can enter a pool, switching their Eth for rEth (a liquidity token representing the amount of Eth staked in the pool, given at a 1:1 ratio), to fill the rest of the 16 Eth required, a sort of crowdfunding method. 
* How is the company funded? How much funding have they received?
Rocket Pool is funded by seed money, the exact amount of money involved has not been disclosed, but the lead investor is Consensys Ventures, a blockchain startup capital venture firm based in Sacramento, California. 


___
## Business Activities:
* What specific financial problem is the company or project trying to solve?

  According to the Ethereum Foundation's roadmap, they are planning to move the main chain of Ethereum from PoW to PoS, and merge it with the current PoS chain. Under PoS validators will need 32 Eth to make a validator, currently this costs ~$135,000 AUD, a very large sum of money. Under these circumstances only either early adopters, or those in a financially priveledged position may be able to run a validator node. The consequences of this is that this shifts the Ethereum network towards being centralised under the "rule" of those who have 32 Eth. Rocket Pool solves this by having NOs, who have 16 Eth, while the other 16 is crowdfunded into a pool. This allows people who have as little as 0.01 Eth to enter the staking market, increasing decentralisation. 
* Who is the company's intended customer? Is there any information about the
market size of this set of customers?
What solution does this company offer that their competitors do not or cannot
offer? (What is the unfair advantage they utilize?)

  Rocket Pool's intended customer are both people who have less than 32 Eth, and do not want to run a node, but just want to stake and earn interest on their cryptocurrency investment, as well as early adopters, or more financially available investors who wish to run minipools of 16 Eth, and collect comission. Currently there is approximately ~7.7 million Ether locked into the staking contract, a fraction of the ~117 million circulating. The market is large, as other providers such as Lido, Stakefish, and cex (centralised exchanges) Coinbase, and Binance all have launched their own staking programs allowing users to stake less than 32 Eth. The advantage of Rocket Pool is that the owners of the minipools running with 16 Eth learn a larger comission than the current APR % given by the default PoS stake (~6%). They also have an advantage of liquidity. Stakers who stake with Rocket Pool receive rEth, a token with the value pegged to the interest earned on 1 Eth, e.g. 1 rEth would be worth 1.06 Eth by the end of one year. Currently, staking Eth requires the Eth to be locked until the merge of the main PoW chain and the PoS Beaconchain, however with the tokenization of rEth, the staker would be allowed to withdraw at anytime. 
* Which technologies are they currently using, and how are they implementing them?
(This may take a little bit of sleuthing–– you may want to search the company’s
engineering blog or use sites like Stackshare to find this information.)

  Rocket Pool uses smart contracts, the smart node network, and minipool validators. Smart contracts are set up so that when a user deposits Eth, the smart contract automatically assigns them into a minipool run by a NO. 
The Smart Node Network helps run the smart contracts, and communicates between Rocket Pool and Ethereum's Beaconchain. 
Minipool validators are a form of smart contract, but is the core of Rocket Pool. They are created by NOs who deposit 16 Eth to start a node. The Minipool Validator contract then receives 16 Eth from stakers who do not want to run a node. Upon reaching the 32 Eth required to launch a validator, the validator is then sent to the Beaconchain's validator queue. 

![howrplworks](https://rocketpool.net/images/infographic-rocket-pool-2.png)
#### A quick visual guide on how RocketPool works. Image taken from https://medium.com/rocket-pool/rocket-pool-101-faq-ee683af10da9
---
## Landscape:
* What domain of the financial industry is the company in?

 
  Rocket Pool is part of the alternative finance industry. They are also in the infrastructure industry as they provide a service for the PoS system of Ethereum. 
* What have been the major trends and innovations of this domain over the last 5-
10 years?
Alternative Finance and Blockchain have both made large improvements and developments in the past decade. Bitcoin, the technology that pioneered blockchain was invented in January 2009, after the 2008 Wall St crash as a reaction to traditional finance. Ethereum's whitepaper was published by Vitalik Buterin in 2013, with the mainnet going live in 2015. 
The first mainstream crowdfunding site GoFundMe was created in 2010, but the concept of crowdfunding had been around the late 1990s. Due to the popularity it has spawned a number of similar websites such as Kickstarter, Indiegogo, and Seed Invest. These platforms have all raised large amounts of money for their projects, the largest being $376 million dollars for *Star Citizen*, an online Role Playing Game. 
In the last 5 years developments such as DeFi, and Dexs (Decentralise Exchanges where orders are completed with liquidity pools rather than orderbooks) have emerged. The governance token RPL is traded currently only on Dexs. This allows release of tokens that do not have to be passed through the stringent checks of regulations in traditional finance. 
In the last 5 years there was been a rapid growth in crowdfunding, with sites such as Patreon allowing individuals to be crowdfunded for their work. The rise of cryptocurrency has also spilled into crowdfunding, with supporters now able to directly send funds via crypto directly to their favourite projects. Social network Twitter recently added cryptocurrency tipping to verified accounts. 

* What are the other major companies in this domain?

  In this specific domain, Rocket Pool is competing with other Eth2 staking services such as Lido, Stakefish, and Staked.us. However centralised exchanges have also begun offering their own Eth2 staking, with exchanges such as Binance, Coinbase and Kraken. As Rocket Pool is the first Eth2 staking platform to utilise smart contracts there are not any similar competitors. In terms of alternative finance, competitors include yield aggregators and other DeFi services that offer competitive APR%s for the user's cryptocurrency holdings.
## Results
* What has been the business impact of this company so far?
  
  Rocket Pool's impact on Eth2 staking has been significant. Beaconchain (the main Eth2 staking explorer) is planning on hosting a launch party. Other staking services have also been pushed to provide a fully decentralised solution to Eth2 staking. In terms of yield, many users feel safer using Rocket Pool's smart contract service for staking their Ethereum, rather than running a dedicated node. However, as of writing the project has not launched its mainnet yet, so how significant the impact is cannot be fully measured.
* What are some of the core metrics that companies in this domain use to measure
success? How is your company performing, based on these metrics?

  Core metrics include % of Eth staked from circulating supply, volume of RPL traded, and ratio from RPL to Eth. Currently the ratio of RPL to Eth has recently hit a high of 0.011 RPL : 1 Eth. This ratio is important as the minimum required RPL to run a node is 1.6 Eth worth. Currently as mainnet has not launched it is not possible to see % of Eth staked. However, recently there was a critical bug found in the Node code that would allow multiple withdrawals that also affected other provider's nodes. 
 
* How is your company performing relative to competitors in the same domain?

  Currently as the project has not launched it is not possible to have an accurate figure. However, going by sentiment, a large number of current stakers would consider moving to Rocket Pool.

## Recommendations
* If you were to advise the company, what products or services would you suggest
they offer? (This could be something that a competitor offers, or use your
imagination!)

  Better PR, recently Rocket Pool had a launch delay due to a critical bug found on launch day. However, the staff were fairly active on Discord, but news was not shared outside that channel. I would suggest that they be more vocal on other channels when releasing news.
  I would also advise Rocket Pool to up their current marketing strategy. Even though the product is niche, other staking serves currently have a large online presence, while Rocket Pool, having a superior product has a very small presence.
  Currently, the only way to acquire RPL the governance token is to use UniSwap, a decentralised exchange, or an aggregator. This is a very high skill floor to get into Rocket Pool. I would suggest getting a listing on a centralised exchange, or if that is not possible being on more liquid swap sites.
* Why do you think that offering this product or service would benefit the
company?
 
 As the service requires RPL to function it would make sense for ease of access to the governance token. This will provide: 
 
  1. An easier location to acquire the governance token.
  2. Solves liquidity issues. The token recently underwent a liquidity crunch which sent the price from $22 to $39 in the span of two days. This was due to the reliance on UniSwap, where liquidity was extremely low, which led to even small buys leading to huge swings in prices. 

 

* What technologies would this additional product or service utilize?
  

  Social Media. Rocket Pool and their team are currently not active on any social media other than Discord. This is not ideal as most people in the space of cryptocurrency are very new, and are not familiar with the very very niche options such as Rocket Pool. 
  Centralised exchanges, even though against the fundamental idea of Rocket Pool (decentralised) is required due to the liquidity provided.
 
 * Why are these technologies appropriate for your solution?

   As the solution is very niche, it would benefit the team to have a more accessible option to access the service. Decentralisation is only viable as a solution if the solution is accessible to everyone. If the requirements, both technical and financial are too high then the service risks being centralised. 

## Appendix
https://au.linkedin.com/in/david-rugendyke-260a2a60#:~:text=David%20Rugendyke%20%2D%20Rocket%20Pool%20Founder,Solidity%20Developer%20%2D%20Rocket%20Pool%20%7C%20LinkedIn

https://www.crunchbase.com/organization/rocket-pool

https://medium.com/rocket-pool/rocket-pool-101-faq-ee683af10da9

https://beaconcha.in/pools

https://beaconcha.in/stakingServices

https://ethereum.org/en/eth2/staking/

https://www.binance.com/en/eth2

https://v2.info.uniswap.org/pair/0x70ea56e46266f0137bac6b75710e3546f47c855d

https://github.com/rocket-pool/rocketpool-research/blob/master/Reports/withdrawal-creds-exploit.md


