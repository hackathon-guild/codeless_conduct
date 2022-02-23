# Gnosis Safe  Design Exploration.

## About: 

here i will be sharing the overall system design for the onchain / offchain based NFT services (makretplace , metaverse , enterprise usecases ) from the persepective of standards and validation of arbitrary operations using gnosis safe (not only pre-esthablished ones like ERC721 , 1155 but also upcoming ones like 
    - 2981 for royalities standard  ,
    - 2477 for metadata integrity 
    -  725 for the smart contract based accounts etc) 

- and also highlighting the challanges faced by the users in the past, something that i can also [relate](https://github.com/gnosis/safe-react/issues/350) during the previous years when due to the ascent of defi and nft applcations necessitated the need of   digital custodial  solutions to resolve the issues being faced by  the hardware / extension wallets (primarily being need of programmable accounts and security).

- and finally i will be doing the design architectures for the real use cases of the gnosis applications across different use cases (NFT ecommerce using boson with gnosis safe, crossmarket / crosschain asset transfers and custodial solution via seamless integration with rarible , opensea and  Gem etc. 


## credits :
i could not have hacked my way out writing this extensive review without referencing extensively  generous work being done by the fellow web3 community members aggregrating the resources, standards and creating communities of higher level discussion on technical design (as well as  providing inclusive enviornment so that main stakeholders in the current NFT ecosystem) so thanks a lot for your dedication. some of the prominent i am referencing here (but will be more specific for ):
    - [NFT-standards-WG](https://www.nftstandards.wtf/NFT+Standards+Wiki+-+READ.me).
    - [gitcoin kernel community](http://kernel.community/en/).
    - [Boson Protocol](http://kernel.community/en/).
    -  rarible 
    - radicle.





## intro 101 : gnosis safe design 

technically gnosis safe is solutions provider for managing  smart contract based wallet with primarily multi-signature functionality , but at same time providing access to  varied functionalities like    
    -  building custom  transactions (like timelocks , batched transactions , fine grained access management apart from whitelisting addresses  ) for providing better UX exeperience and use cases not envisioned before .  

    - custom modules  like social recovery, access tokens to different identification token protocols (SSH , X11 ,OAUTH and sky is limit ) thanks to the modularisation based on the core use cases that are robust .
    - gasless transfer and adaptation 


it consist of both onchain based smart contract wallets via using [] , but also off chain based relay services[].


