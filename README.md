# fxportal

## Tools Used
- **Hardhat:** A development environment to compile, deploy, test, and debug Ethereum software.
- **Foundry (optional):** A toolchain for developing Ethereum smart contracts.
- **DALLE 2 or Midjourney:** Tools for generating images using AI.
- **Pinata.cloud:** A service for managing and storing files on IPFS.

## Project Rubric
To successfully complete the Final Challenge, your project should include the following components:

1. **Generate a 5-item Collection Using DALLE 2 or Midjourney:**
   - Create five unique items (images) using AI tools like DALLE 2 or Midjourney.

2. **Store Items on IPFS Using Pinata.cloud:**
   - Upload the generated items to IPFS using Pinata.cloud to get their IPFS hashes.

3. **Deploy an ERC721 or ERC1155 to the Goerli Ethereum Testnet:**
   - Implement and deploy an ERC721 or ERC1155 smart contract to the Goerli Ethereum Testnet.

4. **Implement promptDescription Function:**
   - Add a `promptDescription` function to the smart contract that returns the prompt used to generate each image.

5. **Map Your NFT Collection Using Polygon Network Token Mapper (Optional):**
   - Use Polygon network token mapper to map your NFT collection for better visualization.

6. **Write a Hardhat Script to Batch Mint All NFTs:**
   - Use Hardhat to write a script that batch mints all the NFTs. The ERC721A standard is recommended for optimal batch minting.

7. **Write a Hardhat Script to Batch Transfer All NFTs from Ethereum to Polygon Mumbai Using the FxPortal Bridge:**
   - Create a Hardhat script to facilitate the batch transfer of all NFTs from the Ethereum network to the Polygon Mumbai network using the FxPortal Bridge.

8. **Approve the NFTs to be Transferred:**
   - Ensure that the NFTs are approved for transfer to the bridge contract.

9. **Deposit the NFTs to the Bridge:**
   - Deposit the NFTs into the bridge to complete the transfer process.

## Steps to Complete the Project

### 1. Generate NFT Collection
Use DALLE 2 or Midjourney to create five unique digital art pieces for your NFT collection.

### 2. Store Images on IPFS
Upload each generated image to IPFS using Pinata.cloud and note down the IPFS hash for each image.

### 3. Smart Contract Development
- **Implement ERC721 or ERC1155 Contract:**
  - Write a smart contract for your NFT collection.
  - Ensure the contract includes a `promptDescription` function that returns the image generation prompt.

- **Deploy to Goerli Testnet:**
  - Use Hardhat to compile and deploy your contract to the Goerli Ethereum Testnet.

### 4. Map NFTs on Polygon (Optional)
If you choose to, map your NFT collection using Polygon's token mapper tool for enhanced visualization.

### 5. Batch Minting Script
Create a Hardhat script to batch mint your NFTs using ERC721A for efficiency.

### 6. Transfer NFTs to Polygon
- **Approve NFTs:**
  - Write a script to approve the NFTs for transfer.

- **Batch Transfer Using FxPortal Bridge:**
  - Create a Hardhat script to batch transfer the NFTs from Ethereum to Polygon Mumbai using the FxPortal Bridge.

- **Deposit NFTs:**
  - Deposit the NFTs into the bridge contract to finalize the transfer.

## Conclusion
By following the steps outlined above, you will successfully complete the Final Challenge and create a fully functional NFT collection that is generated, stored, deployed, and transferred across Ethereum and Polygon networks.
