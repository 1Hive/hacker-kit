
# Gardens Hacker Kit 🌻

This hacker kit is intended to provide resources for people who are interested in hacking on DAOs based on the [Gardens DAO design pattern](https://forum.1hive.org/t/gardens-overview/32).

We are providing these resources and the software we have developed as open source with no warranty or associated expectations. Some of the components have been audited, others have not. **We encourage people to use, hack it, and extend it, but also be aware that it is a highly experimental codebase and you should proceed carefully and at your own risk!**

Happy Hacking!  

## Gardens Template
This template includes Marketplace (a augmented bonding curve module), Conviction Voting (bottom-up fund allocation), and Dandelion Voting (for administrative decisions with ragequit incentive) as the core components.

We have deployed the components and a dao factory on the rinkeby and xDai networks.

https://github.com/1Hive/gardens-template

## Honey Template
This template includes Issuance (A continuous minting policy), Conviction Voting (bottom-up fund allocation), and Dandelion Voting (for administrative decisions with ragequit incentive) as the core components.

We have deployed the components and a dao factory on the rinkeby and xDai networks.

https://github.com/1Hive/honey-template/

We have also created a connect frontend for this template:

https://github.com/1Hive/honey-pot

## Component Repos

The Gardens and Honey Template build on a number of Aragon Apps, which are sort of like DAO legos. You can find the repos for these apps bellow. Only the Conviction Voting app and Dandelion Voting app currently have sub-graphs and connectors, but they are the ones that you would likely need to fetch data from, the others should be easy enough to interact with directly.

Conviction Voting: https://github.com/1Hive/conviction-voting-app
Marketplace: https://github.com/1Hive/marketplace-app
Dandelion Voting: https://github.com/1Hive/dandelion-voting-app
"Hooked" Token Manager: https://github.com/1Hive/token-manager-app
Redemptions: https://github.com/1Hive/redemptions-app
Issuance: https://github.com/aragonone/issuance-app
Tollgate: https://github.com/aragonone/tollgate

## xDai Deployment

We have also deployed the Aragon infrastructure to xDai to enable us to experiment with more social DAO experiences that may be cost-prohibitive on more congested network like Ethereum.

This deployment is new and not "official", so some tooling may not work properly with xDai, but most things we have tried work fine.

Aragon Client: https://aragon.1hive.org (Note deploying using the client is not currently supported)
Subgraph: https://thegraph.com/explorer/subgraph/1hive/aragon-xdai
Registry for use in arapp.json: `0xaafca6b0c89521752e559650206d7c925fd0e530`

### If you get stuck...

You can find 1Hive community members in [our discord](https://discord.gg/YjpJx6P) or in the [DAO Hack Month discord](https://discord.gg/cwtDuGB). 
