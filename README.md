# NFT Collection Deployment and Transfer

## Overview

This project aims to deploy a 5-item NFT collection using DALLE 2 or Midjourney, store the items on IPFS using pinata.cloud, and deploy an ERC721 or ERC1155 contract to the Goerli Ethereum Testnet. Additionally, it includes mapping the NFT collection using the Polygon network token mapper for visualization purposes. Hardhat scripts are implemented to batch mint all NFTs, batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge, and approve the NFTs for transfer. Finally, the NFTs are deposited to the bridge and the balanceOf function is tested on Mumbai. A comprehensive readme is included to guide users through the project.

## Tools Used

- Hardhat
- Foundry (optional)
- DALLE 2 or Midjourney
- IPFS (pinata.cloud)
- ERC721 or ERC1155
- Goerli Ethereum Testnet
- Polygon Network Token Mapper
- FxPortal Bridge

## Project Rubric

To successfully complete the Final Challenge, the project meets the following criteria:

1. **Generate a 5-item collection using DALLE 2 or Midjourney**: Images are generated using DALLE 2 or Midjourney models.
2. **Store items on IPFS using pinata.cloud**: Images are stored on IPFS using pinata.cloud for decentralized storage.
3. **Deploy an ERC721 or ERC1155 to the Goerli Ethereum Testnet**: ERC721 or ERC1155 contract is deployed to the Goerli Ethereum Testnet to represent the NFT collection.
4. **Implement a promptDescription function**: The contract includes a promptDescription function that returns the prompt used to generate the images.
5. **Map the NFT Collection using Polygon network token mapper**: The NFT collection is mapped using the Polygon network token mapper for visualization.
6. **Write a hardhat script to batch mint all NFTs**: Hardhat script is written to batch mint all NFTs efficiently, considering ERC721A for optimal performance.
7. **Write a hardhat script to batch transfer all NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge**: Hardhat script facilitates batch transfer of NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.
8. **Approve the NFTs to be transferred**: NFTs are approved for transfer before being deposited to the bridge.
9. **Deposit the NFTs to the Bridge**: NFTs are deposited to the bridge for transfer between Ethereum and Polygon networks.
10. **Test balanceOf on Mumbai**: The balanceOf function is tested on Mumbai to ensure successful transfer.
11. **Write a comprehensive readme**: A detailed readme file is provided to guide users through the project setup, deployment, and usage.

## Project Structure

- **contracts/**: Contains Solidity smart contracts including ERC721 or ERC1155 contract with the promptDescription function.
- **scripts/**: Includes Hardhat scripts for batch minting and batch transferring of NFTs.
- **README.md**: Detailed instructions on project setup, deployment, and usage.
- **images/**: Placeholder directory for generated images.

## Installation and Setup

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Configure Hardhat network settings for Goerli Ethereum Testnet and Polygon Mumbai.
4. Generate NFT images using DALLE 2 or Midjourney and store them on IPFS.
5. Deploy ERC721 or ERC1155 contract to Goerli Ethereum Testnet.
6. Map the NFT collection using the Polygon network token mapper.
7. Write and execute Hardhat scripts for batch minting and batch transferring of NFTs.
8. Test the functionality and balanceOf on Mumbai.
9. Update the readme with project-specific details and usage instructions.

## Usage

1. Generate NFT images using DALLE 2 or Midjourney and upload them to IPFS.
2. Deploy the ERC721 or ERC1155 contract to the Goerli Ethereum Testnet.
3. Map the NFT collection using the Polygon network token mapper.
4. Execute Hardhat scripts to batch mint and transfer NFTs between Ethereum and Polygon networks.
5. Test the balanceOf function on Polygon Mumbai.
6. Refer to the readme for detailed instructions and commands.

## Conclusion

This project demonstrates the deployment and transfer of an NFT collection using various tools and platforms including Hardhat, IPFS, Ethereum Testnets, and Polygon. By following the outlined steps and utilizing the provided scripts, users can efficiently manage and transfer NFTs across different blockchain networks, facilitating broader accessibility and interoperability within the NFT ecosystem.
