# Homework-Assignment-1
# Homework Assignment 1 - RocketPool, $RPL, and rEth
## Overview and Origin


* Name of company

  Rocket Pool, and their governance token $RPL
* When was the company incorporated?

  Rocket Pool was founded on the 1st of September 2016, and is based in Brisbane, Australia.
* Who are the founders of the company?
 Rocket Pool was founded by David Rugendyke, a former developer at George Patterson Y & R. 

https://au.linkedin.com/in/david-rugendyke-260a2a60#:~:text=David%20Rugendyke%20%2D%20Rocket%20Pool%20Founder,Solidity%20Developer%20%2D%20Rocket%20Pool%20%7C%20LinkedIn
* How did the idea for the company (or project) come about?

  The idea of the company was founded by Ethereum switching from PoW (Proof of Work) to PoS (Proof of Stake). For an individual to operate a validator, a total of 32 Ether (the native token of the Ethereum network) is required. As of writing this is ~$135,000 AUD. Rocket Pool aims to decentralise the staking pool by lowering the amount needed to 16. This is done by having a Node Operator (NO) having 16 Eth, whilst those without 16 Eth can enter a pool, switching their Eth for rEth (a liquidity token representing the amount of Eth staked in the pool, given at a 1:1 ratio), to fill the rest of the 16 Eth required, a sort of crowdfunding method. 
* How is the company funded? How much funding have they received?
Rocket Pool is funded by seed money, the exact amount of money involved has not been disclosed, but the lead investor is Consensys Ventures, a blockchain startup capital venture firm based in Sacramento, California. 

https://www.crunchbase.com/organization/rocket-pool
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
## Landscape:
* What domain of the financial industry is the company in?
* What have been the major trends and innovations of this domain over the last 5-
10 years?
* What are the other major companies in this domain?
## Results
* What has been the business impact of this company so far?
* What are some of the core metrics that companies in this domain use to measure
success? How is your company performing, based on these metrics?
* How is your company performing relative to competitors in the same domain?
## Recommendations
* If you were to advise the company, what products or services would you suggest
they offer? (This could be something that a competitor offers, or use your
imagination!)
* Why do you think that offering this product or service would benefit the
company?


* What technologies would this additional product or service utilize?
* Why are these technologies appropriate for your solution?

## Appendix
