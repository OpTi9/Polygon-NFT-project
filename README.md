# Polygon NFT project
Simple NFT minting dapp project build on Polygon network using React.JS and Hardhat.
- [Website](https://practical-joliot-27375b.netlify.app/)
- [OpenSea](https://opensea.io/collection/coronft)
<img src="https://i.imgur.com/Tc0bPfP.png" width="600">

## Overview
CoroNFT is a Limited Edition NFT art collection of 1,000 coronavirus particles randomly generated from manually created assets.

## Tech used
- [Adobe Illustrator](https://www.adobe.com/products/illustrator.html) - used to draw the layers of an artwork.
- [Hashlips](https://github.com/HashLips/hashlips_art_engine) - used to create 1,000 unique instances of artworks based on provided layers.
- [Pinata](https://www.pinata.cloud/) - used to host the art instances on [IPFS](https://ipfs.io/) network.
- [OpenZeppelin](https://docs.openzeppelin.com/contracts/4.x/wizard) - used to generate the initial boilerplate Polygon contract code.
- [Mocha](https://mochajs.org/) - testing framework.
- [Hardhat](https://hardhat.org/) - a development environment to compile, deploy, test, and debug smart contracts.
- [React](https://reactjs.org/) - used for the front end of a minting dapp.
- [Redux](https://redux.js.org/) - managing and centralizing application state.

## Traits rarity
- Out of 1,000 instances, most have all the traits; the rarer the instance, the fewer traits it has.
```
type: Trait number {
	total_nft: 1000,
	all_traits: 670,
	no_back_spikes: 200,
	no_front_spikes: 100,
	no_mouth: 20,
	no_spikes: 10 
}
```

- Each layer has a different variations, ranging in rarity from Common to Legendary ([full rarity info](https://github.com/OpTi9/Polygon-NFT-project/blob/main/rarity.txt))
