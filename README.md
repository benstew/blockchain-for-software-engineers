# Blockchain for Software Engineers
Inspired by [Google Interview University](https://www.google.com), [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers), [The Authoritative Guide to Blockchain Development](https://medium.freecodecamp.org/the-authoritative-guide-to-blockchain-development-855ab65b58bc)

"The blockchain symbolizes a shift in power from the centers to the edges of the networks." - William Mougayar

## What is it?
A collection of resources that I've gathered over the past couple years while advancing in the blockchain world. I'm by no means a blockchain expert but I found the below resources proved useful on my journey from a full stack software engineer to a blockchain engineer. Hope this can help others.

This list is by no means exhaustive and is centered on the end goal of building production quality smart contracts and DApps. My journey has been focused on Ethereum but I would love this list to expand and not just be limited to one Blockchain. All contributions welcome!

## About me
My background is in FinTech and I've worked in Investment Banking, Private Equity, and consumer facing investment companies. I'm currently exploring the intersection of deep learning and blockchain to engineer Web 3.0. If you are doing something similar, reach out :).

Linkedin: https://www.linkedin.com/in/benstewart2008/

Twitter: @bigbenstew

Medium: https://medium.com/@BIGbenStew


## Goal
Create and curate a list of resources for aspiring and seasoned blockchain engineers.


## Table of Contents
- [What is it?](#what-is-it)
- [About me](#about-me)
- [Goal](#goal)
- [Covering the Material](#covering-the-material)
- [How to use it](#how-to-use-it)
- [Data Structures](#data-structures)
- [Cryptography](#cryptography)
- [Distributed Systems](#distributed-systems)
- [Networking](#networking)
- [Economics](#economics)
- [Intro to Bitcoin and Blockchain](#intro-to-bitcoin-and-blockchain)
- [Bitcoin and Blockchain Tutorials](#bitcoin-and-blockchain-tutorials)
- [Advanced Bitcoin](#advanced-bitcoin)
- [Bitcoin and Blockchain Books](#bitcoin-and-blockchain-books)
- [Intro to Ethereum](#intro-to-ethereum)
- [Solidity and Smart Contracts](#solidity-and-smart-contracts)
- [Beginner Ethereum Tutorials](#beginner-ethereum-tutorials)
- [Smart Contract Security](#smart-contract-security)
- [Tools of the Trade](#tools-of-the-trade)
- [Ethereum Tutorials](#ethereum-tutorials)
- [Ethereum Books](#ethereum-books)
- [Blockchain Blogs](#blockchain-blogs)
- [Forums and Threads](#forums-and-threads)
- [Other Tools](#other-tools)
- [Podcasts](#podcasts)
- [Hackathons](#hackathons)
- [Additional Curated Lists of Resources](#additional-curated-lists-of-resources)
- [Getting a Job](#getting-a-job)
- [Job Boards](#job-boards)


## Covering the Material
Over the past two years, I found it useful to pick a subject from the list below, read it thoroughly, take notes, and implement on a blockchain running locally. I tend to prefer a top-down, hands on approach to learning. I found it extremely important to build and push my understanding further daily.


## How to use it
Everything below is a prioritized outline and you should work from the top to the bottom.

- [x] **Create a new branch so you can check items like this, just put an x in the brackets: [x]**

# Background
Blockchain technology is a multi-disciplinary field built atop cryptography, economics, and computer science. The background section includes some requisite fundamentals in these fields that will ensure you have solid footing before diving deeper into the blockchain specifics since many of the features that exist today are results of years and years of previous research.

## Data Structures
- [x] [Linked Lists](https://en.wikipedia.org/wiki/Linked_list)
- [ ] [Binary Search Trees](https://en.wikipedia.org/wiki/Binary_search_tree)
- [ ] [Hash Maps](https://en.wikipedia.org/wiki/Hash_table)
- [ ] [Graphs](https://en.wikipedia.org/wiki/Graph_%28discrete_mathematics%29)
- [ ] [Directed Acyclic Graphs](https://en.wikipedia.org/wiki/Directed_acyclic_graph)

## Cryptography
- [ ] [Public/Private Key Cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)
- [ ] [RSA](https://www.youtube.com/watch?v=vgTtHV04xRI)
- [ ] [ECDSA](https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm)
- [ ] [Cryptographic Hash Function](https://en.wikipedia.org/wiki/Cryptographic_hash_function)
- [ ] [Commitment Schemes](https://en.wikipedia.org/wiki/Commitment_scheme)
- [ ] [Merkle Trees](https://en.wikipedia.org/wiki/Merkle_tree)
- [ ] [Merkle Proofs](https://indigocore.org/documentation/v0.1.0/references/proof-of-existence/)

## Distributed Systems
- [ ] [Consistency](https://en.wikipedia.org/wiki/Consistency_model)
- [ ] [Consensus](https://en.wikipedia.org/wiki/Consensus_%28computer_science%29)
- [ ] [Linearizable](https://en.wikipedia.org/wiki/Linearizability)
- [ ] [Eventual Consistency](https://en.wikipedia.org/wiki/Eventual_consistency)
- [ ] [Fault Tolerance](https://en.wikipedia.org/wiki/Fault_tolerance)
  - [ ] [Paxos](https://en.wikipedia.org/wiki/Paxos_%28computer_science%29)
  - [ ] [RAFT](https://en.wikipedia.org/wiki/Raft_%28computer_science%29)
- [ ] [Time In a Distributed System](https://www.youtube.com/watch?v=BRvj8PykSc4)
- [ ] [Tradeoff: Safety vs. Liveness](http://www.bailis.org/blog/safety-and-liveness-eventual-consistency-is-not-safe/)
- [ ] [Byzantine Fault Tolerance](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance)
  - [ ] [PBFT](https://blog.acolyer.org/2015/05/18/practical-byzantine-fault-tolerance/)
- [ ] [Distributed Databases](https://en.wikipedia.org/wiki/Distributed_database)
  - [ ] [Sharding](https://en.wikipedia.org/wiki/Shard_%28database_architecture%29)
    - [ ] [Consistent Hashing](https://en.wikipedia.org/wiki/Consistent_hashing)
  - [ ] [Leader-Follower Replication](https://en.wikipedia.org/wiki/Replication_%28computing%29)
  - [ ] [Quorum-based commits](https://en.wikipedia.org/wiki/Quorum_%28distributed_computing%29)
  - [ ] [Distributed Hash Tables](https://en.wikipedia.org/wiki/Distributed_hash_table)
    - [ ] [Chord](https://en.wikipedia.org/wiki/Chord_%28peer-to-peer%29)
    - [ ] [Kademilia](https://en.wikipedia.org/wiki/Kademlia)

## Networking
- [ ] [Computer Networking](https://en.wikipedia.org/wiki/Computer_network)
  - [ ] [TCP vs. UDP](https://www.diffen.com/difference/TCP_vs_UDP)
  - [ ] [The Packet Model](https://en.wikipedia.org/wiki/Network_packet)
  - [ ] [Internet Routing](https://en.wikipedia.org/wiki/Routing)
- [ ] [Gossip Protocols](https://en.wikipedia.org/wiki/Gossip_protocol)
  - [ ] [Flooding](https://en.wikipedia.org/wiki/Flooding_%28computer_networking%29)
- [ ] [P2P Network Design](https://en.wikipedia.org/wiki/Peer-to-peer)
  - [ ] [BitTorrent](https://en.wikipedia.org/wiki/BitTorrent)
  - [ ] [Tor](https://en.wikipedia.org/wiki/Tor_%28anonymity_network%29)

## Economics
- [ ] [Game Theory](https://en.wikipedia.org/wiki/Game_theory)
  - [ ] [Nash Equilibria](https://en.wikipedia.org/wiki/Nash_equilibrium)
  - [ ] [Schelling Point](https://en.wikipedia.org/wiki/Focal_point_%28game_theory%29)
- [ ] [Macroeconomics](https://en.wikipedia.org/wiki/Macroeconomics)
  - [ ] [Monetary policy](https://en.wikipedia.org/wiki/Monetary_policy)
  - [ ] [Inflation](https://en.wikipedia.org/wiki/Inflation)
  - [ ] [Deflation](https://en.wikipedia.org/wiki/Deflation)
  - [ ] [Velocity of Money](https://en.wikipedia.org/wiki/Velocity_of_money)
- [ ] [Microeconomics](https://en.wikipedia.org/wiki/Microeconomics)
  - [ ] [Supply and Demand Curves](https://en.wikipedia.org/wiki/Supply_and_demand)
  - [ ] [Opportunity Cost](https://en.wikipedia.org/wiki/Opportunity_cost)
  - [ ] [Auction Theory](https://www.youtube.com/watch?v=4kWuxfVbIaU)

# Bitcoin
## Intro to Bitcoin and Blockchain
- [ ] [Blockchain 101](https://youtu.be/_160oMzblY8)
- [ ] [The Blockchain Explained to Web Developers](https://marmelab.com/blog/2016/04/28/blockchain-for-web-developers-the-theory.html)
- [ ] [What is a distributed ledger?](https://www.coindesk.com/information/what-is-a-distributed-ledger/)
- [ ] [How Bitcoin actually works](https://youtu.be/bBC-nXj3Ng4)
- [ ] [Bitcoin Whitepaper](https://bitcoin.org/bitcoin.pdf)
- [ ] [Bitcoin Mining](https://www.youtube.com/watch?v=jXerV3f5jN8)
- [ ] [Walk through a Bitcoin Block header](https://www.youtube.com/watch?v=gUwXCt1qkBU)
- [ ] [Bitcoin Block Explorer](https://blockchain.info/)
- [ ] [Bitcoin History](https://youtu.be/apYieuvnUaE)
- [ ] [Bitcoin Forum](https://bitcointalk.org/index.php?board=1.0)
- [ ] [Blockchains from a distributed computing perspective](http://cs.brown.edu/courses/csci2952-a/papers/perspective.pdf)

## Bitcoin and Blockchain Tutorials
- [ ] [Build your own Blockchain](https://youtu.be/3aJI1ABdjQk)
- [ ] [Review Blockchain Projects](https://github.com/openblockchains/awesome-blockchains)

## Advanced Bitcoin
- [ ] [Bitcoin's Academic Pedigree](https://queue.acm.org/detail.cfm?id=3136559)
- [ ] [Bitcoin Forks](https://www.coindesk.com/short-guide-bitcoin-forks-explained/)
- [ ] [Double Spends, 51% Attacks](https://www.youtube.com/watch?v=UPxaCj8ZsEU)
- [ ] [Replay Attacks](https://bitcointechtalk.com/how-to-protect-against-replay-attacks-7a00bd2fe52f?gi=618160cafff4)
- [ ] [Segregated Witness](https://en.wikipedia.org/wiki/SegWit)
- [ ] [Bitcoin Scalability Problems](https://en.wikipedia.org/wiki/Bitcoin_scalability_problem)
- [ ] [Mega Bitcoin Resources List](https://lopp.net/bitcoin.html)

## Books
- [ ] [Mastering Bitcoin](https://www.amazon.com/Mastering-Bitcoin-Unlocking-Digital-Cryptocurrencies/dp/1449374042)
- [ ] [Blockchain: Blueprint for a New Economy](https://www.amazon.com/Blockchain-Blueprint-Economy-Melanie-Swan/dp/1491920491)
- [ ] [CryptoAssets: The Innovative Investors Guide to Bitcoin and Beyond](https://www.amazon.com/Cryptoassets-Innovative-Investors-Bitcoin-Beyond/dp/1260026671)
- [ ] [The Business Blockchain](https://www.amazon.com/Business-Blockchain-Practice-Application-Technology/dp/1536663468)
- [ ] [Blockchain Revolution](https://www.amazon.com/Blockchain-Revolution-Technology-Changing-Business/dp/151135769X)

# Ethereum
## Intro to Ethereum
- [ ] [Ethereum Whitepaper](https://github.com/ethereum/wiki/wiki/White-Paper)
- [ ] [Ethereum in 25 Minutes](https://youtu.be/mCzyDLanA7s)
- [ ] [Intro to Crypto-economics](https://www.youtube.com/watch?v=sbd4xe9OHJg)
- [ ] [Ethereum's Account Model](https://ethereum.stackexchange.com/questions/326/what-are-the-pros-and-cons-of-ethereum-balances-vs-utxos)
- [ ] [Industry Support](https://entethalliance.org/members/)
- [ ] [The Ethreum Community Forum](https://forum.ethereum.org/)
- [ ] [ERC-20](https://medium.com/@james_3093/ethereum-erc20-tokens-explained-9f7f304055df)
- [ ] [The Anatomy of ERC20](https://medium.com/blockchannel/the-anatomy-of-erc20-c9e5c5ff1d02)
- [ ] [Ethereum for Web Developers](https://medium.com/@mvmurthy/ethereum-for-web-developers-890be23d1d0c)
- [ ] [Ethereum Wallets](https://cointelegraph.com/ethereum-for-beginners/ethereum-wallets)
- [ ] [A Crash Course for Mechanism Design](https://medium.com/blockchannel/a-crash-course-in-mechanism-design-for-cryptoeconomic-applications-a9f06ab6a976)

## Solidity and Smart Contracts
- [ ] [Solidity Docs](http://solidity.readthedocs.io/en/v0.4.20/)
- [ ] [Basics of Solidity By Example](https://www.toshblocks.com/solidity/basics-solidity-example/)
- [ ] [Learn X in Y](https://learnxinyminutes.com/docs/solidity/)
- [ ] [Browser IDE](https://remix.ethereum.org/)
- [ ] [BitDegree](https://solidity.bitdegree.org/)
- [ ] [The Hitchhiker's Guide to Smart Contracts](https://blog.zeppelin.solutions/the-hitchhikers-guide-to-smart-contracts-in-ethereum-848f08001f05)
- [ ] [11 Best Ethereum Development Tools](https://hackernoon.com/11-best-ethereum-development-tools-to-grow-your-stack-e782fd7156ab)

## Beginner Tutorials
- [ ] [Build Your First Blockchain Application in 5 Quick Steps](https://itnext.io/build-your-first-blockchain-application-in-5-quick-steps-89ebb96adbfe)
- [ ] [CryptoZombies](https://cryptozombies.io/)
- [ ] [Build Your Own Ethereum Token](https://enlight.nyc/ethereum-token)
- [ ] [Building a Voting System](https://karl.tech/learning-solidity-part-2-voting/)

## Smart Contract Security
- [ ] [Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/)
  - [ ] [The DAO Hack](http://hackingdistributed.com/2016/06/18/analysis-of-the-dao-exploit/)
  - [ ] [Parity Wallet Hack](https://medium.freecodecamp.org/a-hacker-stole-31m-of-ether-how-it-happened-and-what-it-means-for-ethereum-9e5dc29e33ce)
  - [ ] [Parity Wallet Hack II](https://hackernoon.com/parity-wallet-hack-2-electric-boogaloo-e493f2365303)
- [ ] [Secure Generation of Randomness](http://www.swende.se/blog/Breaking_the_house.html)
- [ ] [Ethernaut - Smart Contract Hacking Game](https://ethernaut.zeppelin.solutions/)
- [ ] [Hack This Contract Game](http://hackthiscontract.io/)
- [ ] [Additional Resources](https://consensys.github.io/smart-contract-best-practices/bibliography/)

## Tools of the Trade
- [ ] [Truffle Docs](http://truffleframework.com/docs/)
- [ ] [Ganache](http://truffleframework.com/docs/ganache/using)
- [ ] [IPFS Docs](https://ipfs.io/docs/)
- [ ] [Geth](https://github.com/ethereum/go-ethereum/wiki/geth)

## Ethereum Tutorials
- [ ] [End to End Ethereum Tutorial](https://medium.com/@merunasgrincalaitis/the-ultimate-end-to-end-tutorial-to-create-and-deploy-a-fully-descentralized-dapp-in-ethereum-18f0cf6d7e0e)
- [ ] [Introduction to Ethereum Smart Contract Development](https://www.youtube.com/watch?v=8jI1TuEaTro)
- [ ] [Ethereum Programming for Web Developers](https://happyfuncorp.com/whitepapers/webthereum)
- [ ] [Ethereum Petshop](http://truffleframework.com/tutorials/pet-shop)
- [ ] [How to Create Your Own Token in 1 Hour](https://steemit.com/ethereum/@maxnachamkin/how-to-create-your-own-ethereum-token-in-an-hour-erc20-verified)
- [ ] [How Launch Your Own Production Ready Cryptocurrency](https://hackernoon.com/how-to-launch-your-own-production-ready-cryptocurrency-ab97cb773371)
- [ ] [How to Create Your Own Crowdsale](https://www.ethereum.org/crowdsale)
- [ ] [Building Battle Tested Contract w/ Open Zeppelin](http://truffleframework.com/tutorials/robust-smart-contracts-with-openzeppelin)

## Books
- [ ] [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook)
- [ ] [The business Blockchain](https://www.amazon.com/Business-Blockchain-Practice-Application-Technology/dp/1536663468)
- [ ] [Mastering Ethereum](https://www.amazon.com/Mastering-Ethereum-Building-Smart-Contracts/dp/1491971940)
- [ ] [Introducing Ethereum and Solidity](https://www.apress.com/us/book/9781484225349)
- [ ] [Ethereum Development with Go](https://goethereumbook.org/)

# Blockchain Community
## Blogs
- [ ] [Coindesk](https://www.coindesk.com)
- [ ] [ETH Research](https://ethresear.ch/)
- [ ] [Vitalik Buterin](https://vitalik.ca/)
- [ ] [Hacking, Distributed](http://hackingdistributed.com/)
- [ ] [Unenumerated](http://unenumerated.blogspot.com/)
- [ ] [Money Stuff](https://www.bloomberg.com/view/topics/money-stuff)
- [ ] [Chris Burniske](https://medium.com/@cburniske)
- [ ] [Great Wall of Numbers](http://www.ofnumbers.com/)

## Forums and Threads
- [ ] [r/Ethereum](https://reddit.com/r/ethereum)
- [ ] [r/CryptoCurrency](https://www.reddit.com/r/CryptoCurrency)
- [ ] [Bitcoin Talk](https://bitcointalk.org/)

## Other Tools
- [ ] [CryptoPanic News Feed](https://cryptopanic.com/)
- [ ] [Crypto Price Screener](https://www.cryptocompare.com/coins/list/USD/1)

## Podcasts
- [ ] [Unchained Podcast](https://itunes.apple.com/us/podcast/unchained-big-ideas-from-worlds-blockchain-cryptocurrency/id1123922160?mt=2)
- [ ] [Epicenter Podcast](https://itunes.apple.com/us/podcast/epicenter-podcast-on-blockchain-ethereum-bitcoin-distributed/id792338939?mt=2)
- [ ] [Conspiratus Podcast](https://itunes.apple.com/us/podcast/conspiratus/id1335928646?mt=2)

## Hackathons
- [ ] [Hackathon.com](https://www.hackathon.com/theme/blockchain)

## Additional Curated Lists of Resources
- [ ] [CryptoMinded](https://cryptominded.com/)

## Getting a job
- [ ] [How to Get a Job at a Crypto Startup](https://angel.co/talent-hacks/how-to-get-a-job-at-a-crypto-startup)

## Job Boards
  - [ ] [AngelList Crypto Startups](https://angel.co/bitcoin/jobs)
  - [ ] [BlockchainJobz](http://blockchainjobz.com/)
  - [ ] [Ethereum Jobs](https://jobs.ethercasts.com/)
  - [ ] [Be in Crypto](https://beincrypto.com/)
  - [ ] [Blockchain Job Board](http://www.blockchainjobboard.org/)
