# NFT Bot

NFT Bot is a decentralized application that enables users to generate unique non-fungible tokens (NFTs) using machine learning algorithms and sell them on the blockchain. With NFT Bot, even non-artists can utilize their creativity and generate unique NFTs that can be sold on popular marketplaces.

The NFT Bot is built on top of the Ethereum blockchain and utilizes Solidity for writing smart contracts and tests, Javascript for building the React frontend and writing tests, Hardhat as the development framework, Ethers.js for blockchain interaction, and NFT.Storage for connecting to the IPFS network. The application also integrates Hugging Face AI models for generating unique NFTs based on the user's input.

The application is designed to be user-friendly and easy to use, even for individuals with no prior experience in blockchain development. Users can simply connect their MetaMask wallet to the application, enter their desired inputs, and generate unique NFTs using the Hugging Face AI models. The generated NFTs can then be listed for sale on popular NFT marketplaces such as OpenSea and Rarible, with the transaction being processed on the Ethereum blockchain.

One of the most exciting features of NFT Bot is that it enables users to express their creativity in a unique way, even if they are not artists. With the integration of Hugging Face AI models, users can generate a wide range of unique NFTs based on their input, such as custom text, images, or even audio files. This opens up a world of opportunities for individuals who may not have considered themselves as creative before.

Another important feature of NFT Bot is its ability to provide users with full control over their NFTs. As the NFTs are generated and sold on the Ethereum blockchain, users can be assured of their ownership and control over the assets. They can also be confident that the assets are stored securely on the decentralized IPFS network, ensuring their durability and accessibility for years to come.

NFT Bot is an exciting and innovative decentralized application that opens up a new world of opportunities for individuals looking to express their creativity and sell their digital assets on the blockchain. With its user-friendly interface and powerful machine learning algorithms, the application makes it easy for anyone to generate and sell unique NFTs, even if they have no prior experience in blockchain development.

## Installation and Setup

1. Requirements:

- NodeJS installed on your machine

2. Installation Steps:
   Clone or download the repository from GitHub:

   ```
   git clone https://github.com/Siffatjot/NFTBot.git
   ```

3. Change into the project directory:

   ```
   cd NFTBot
   ```

4. Install project dependencies:

   ```
   npm install
   ```

5. Create a .env file with the following values (see .env.example) and add your Hugging Face and NFT.Storage API keys:

   ```
   REACT_APP_HUGGING_FACE_API_KEY="<your hugging face api key>"
   REACT_APP_NFT_STORAGE_API_KEY="<your nft.storage api key>"
   ```

   You can create a Hugging Face account and generate an API key by visiting your profile settings and creating a read access token. Similarly, you can create a NFT.Storage account and generate an API key.

6. Run tests to ensure everything is working properly:

   ```
   npx hardhat test
   ```

7. Start the Hardhat node:

   ```
   npx hardhat node
   ```

8. In a separate terminal, run the deployment script:

   ```
   npx hardhat run ./scripts/deploy.js --network localhost
   ```

9. Finally, start the frontend:
   ```
   npm run start
   ```

After following these steps, you should be able to use NFTBot and generate your own AI-generated NFTs to sell.

## Technology Stack & Tools

- Solidity (Writing Smart Contracts & Tests)
- Javascript (React & Testing)
- [Hardhat](https://hardhat.org/) (Development Framework)
- [Ethers.js](https://docs.ethers.io/v5/) (Blockchain Interaction)
- [React.js](https://reactjs.org/) (Frontend Framework)
- [NFT.Storage](https://nft.storage/) (Connection to IPFS)
- [Hugging Face](https://huggingface.co/) (AI Models)

## Use Cases

NFT Bot is a powerful tool that allows users to create and sell their own unique NFTs with the help of AI-generated images. Here are some of the use cases for NFT Bot:

- Artists: NFT Bot can help artists showcase their work in a new and innovative way by generating unique AI-generated images that can be used as the basis for their NFTs. This can help them stand out in the crowded NFT market and attract buyers who are looking for something truly unique.

- Collectors: NFT Bot can also be used by collectors who are looking to expand their collections with one-of-a-kind pieces. The AI-generated images can be customized to match the collector's preferences, and the resulting NFTs can be added to their digital collections.

- Gamers: NFT Bot can be used by gamers to create and sell in-game items as NFTs. This can help them monetize their gaming skills and generate income from their hobby.

- Musicians: NFT Bot can also be used by musicians to create and sell unique NFTs that showcase their music and artistic style. This can be a great way for musicians to connect with their fans and generate income from their music.

- Content creators: NFT Bot can be used by content creators to create and sell unique NFTs that showcase their content. This can include anything from videos and animations to blog posts and articles.

- Brands: NFT Bot can also be used by brands to create and sell limited-edition NFTs that showcase their products or services. This can be a great way for brands to connect with their customers and create a new revenue stream.

NFT Bot is a versatile tool that can be used by anyone looking to create and sell unique NFTs. Whether you are an artist, collector, gamer, musician, content creator, or brand, NFT Bot can help you showcase your creativity and generate income from your work.

## Conclusion

NFT Bot is an exciting project that provides a simple and user-friendly way for artists, designers, and creators to generate and sell their own NFTs. The integration of AI models from Hugging Face allows users to easily create unique and engaging artwork that can be used to generate NFTs with ease. The use of Solidity for writing smart contracts and tests, along with the Hardhat development framework, ensures that the NFTs generated are secure, reliable, and efficient.

NFT Bot provides an opportunity for non-artists to participate in the NFT space by allowing them to use their creativity to generate NFTs. Additionally, the integration with NFT.Storage makes it easy to store and access NFTs on the IPFS network, while the Ethers.js library allows for seamless interaction with the blockchain.

Overall, NFT Bot is a promising project that has the potential to revolutionize the way we think about art and digital ownership. With its intuitive interface, secure and efficient smart contract architecture, and the ability to generate unique and creative NFTs, NFT Bot is a project that is worth exploring for anyone interested in the NFT space.
