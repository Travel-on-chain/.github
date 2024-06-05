# Travel on Chain

![Welcom](https://www.yunique.top/upload/HomePageChainlinkCps.png)


<p align="center">
  <a href="https://youtu.be/iH6rStbv27Q" target="_blank">
    <img alt="YouTube" src="https://img.shields.io/badge/youtube-white?style=for-the-badge&logo=youtube&logoColor=F41C0C" width="256">
  </a>

</p>

The video on YouTube: [Travel on Chain](https://youtu.be/iH6rStbv27Q)

## 🛬 What is Travel on Chain?

![Static Badge](https://img.shields.io/badge/Travel%20on%20Chain-%2355AF58?style=for-the-badge&logo=chainlink&label=Chainlink&labelColor=%23375BD2)

### 🌟 Inspiration

Our original intention was to leverage fun and engaging activities to motivate people to participate in offline tourism and experience the beauty of the world firsthand. At the same time, by harnessing the power of Web3 technology, we aim to provide tangible rewards and incentives for people as they travel. This approach ensures they receive positive feedback, encouraging them to explore new areas and discover the unknown continually.

### 🚀 What It Does

**Travel on Chain** is a decentralized application (DApp) that uses NFTs as a medium, incorporating AI, social, and gaming attributes to create an interactive and enjoyable travel experience.

## 🛠️ How We Built It

Through continuous communication and brainstorming among team members, everyone has contributed their efforts, offering innovative ideas and strategies for the project, and constantly exploring new ways to play. Each member has fully utilized their strengths and actively pushed the project forward.

## 🌪️ Challenges We Ran Into

Given our limited understanding of the overall Web3 industry, we have been using our spare time to learn industry knowledge and related development skills. Our team members, all practitioners from the Web2 industry, are highly interested in the Web3 industry. However, our knowledge gap has made it difficult for us to create more complex content. This competition marks the first time we have worked together, so we also need time to work on team coordination.

### 🎉 Accomplishments That We're Proud Of

With our enthusiasm and responsible attitude, we completed the project and achieved significant results within a month, seeing it through from start to finish. Additionally, our idea received support from some industry professionals and project teams.

## 📚 What We Learned

We have gained a deeper understanding of the industry, enabling us to understand better and enter this promising field. At the same time, we have also acquired many useful development skills, making us more professional. Our progress has been rapid thanks to the Chainlink training courses.

### 🩹 Technical Challenges and Implementations

1. **Pricing for Chainlink VRF Invocation**:
   - Due to the dynamic nature of gas fees, we have adopted a fixed pricing model to cover the total costs of Chainlink and on-chain transactions for each dice throw.
   - To optimize costs and improve user experience, we plan to aggregate user requests over a specific period on the server side and then invoke the Chainlink VRF service collectively.
2. **Contract Payment Methods**:
   - Currently, the contract only supports ETH as the payment method. However, we aim to expand this by integrating more payment options such as LINK, AVAX, BNB, etc. This will require the use of an additional price conversion contract to facilitate the switch between different currencies.
3. **Contract VRF Call Return Speed**:
   - On Sepolia, the complex on-chain network conditions can cause delays in returning VRF values, which affects the user experience.
   - To address this issue, we leverage Layer 2 technology, specifically Arbitrum, which enables the callback function to quickly return values, achieving a VRF request experience within 3 seconds.
4. **NFT Implementation Approach**:
   - After comparing different technical practices both on-chain and off-chain, and considering the issue of gas consumption, we opted for a compromise solution by choosing the IPFS (InterPlanetary File System) approach for our NFT implementation. This allows us to store the metadata associated with NFTs off-chain while maintaining the integrity and decentralization of the system.
5. **Contract Upgrade Solutions**:
   - In terms of contract upgrade strategies, we evaluated the traditional proxy pattern and the UUPS (Universal Upgradeable Proxy Standard) approach. We ultimately selected the more reliable UUPS method. To ensure the correctness of the contract data during the upgrade process, we conducted extensive testing and validation to guarantee the integrity of the contract upgrades.
6. **Canvas Grid Path Creation:**
   1. I've encapsulated methods for drawing grids in different directions using canvas to complete the chessboard path, and I've optimized performance through layering. The background layer is responsible for static elements, while the animation layer handles dynamic elements. The challenge lies in the coordination between layers, and the solution is to reasonably divide the layers and only repaint the changing elements.

With precision, we offer robust NFT implementation, secure contract upgrades, and off-chain metadata storage. Chainlink's VRF ensures fairness and randomness. We balance performance and visual fidelity in chessboard paths, optimizing layering for a smooth interface. Our comprehensive solution meets user demands and technical requirements.


## 🌏 What's Next for Travel on Chain

We will continue to improve the project while considering more aspects related to the business model. Currently, the project focuses mainly on the Asian market, but we plan to expand it globally in the future. Moving forward, we will engage with more public blockchains, promote the project, and scale it up.

### ⏭️ Future Plans

1. **Expanding to other regions**: We plan to expand the project to other regions, including Europe, Africa, and South America. This will involve creating a new NFT collection for each region and integrating it into the existing system.
2. **Integrating with other platforms**: We plan to integrate the project with other platforms, such as social media, to create a more integrated experience for users.
3. **Scaling up**: We plan to scale up the project by increasing the number of NFTs and the number of users. This will involve increasing the number of NFTs and the number of users, and improving the user experience.
4. **Expanding the business model**: We plan to expand the business model by creating a subscription model, allowing users to purchase NFTs and receive rewards. This will involve creating a subscription model, and improving the user experience.
5. **NFT Marketplace**: We plan to create an NFT marketplace, allowing users to sell and buy NFTs. This will involve creating an NFT marketplace, and improving the user experience.

And there are more plans to be added.

## 👪 Team Members

![Static Badge](https://img.shields.io/badge/James-AF8260?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Yaco-7BC9FF?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Zitian-9CAFAA?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Unic-7EA1FF?style=for-the-badge&link=www.yunique.top)
![Static Badge](https://img.shields.io/badge/Rhys-F2C18D?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Lewis-9BB0C1?style=for-the-badge)

## 💕 Thanks

<p align="center">
   <a href="https://chain.link">
    <img src="https://cdn.prod.website-files.com/5f6b7190899f41fb70882d08/665705c1f3833b5b5d8f4ffb_logo-chainlink-blue.svg"  width="328"/>
  </a>
  <br>
  <br>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,solidity,go,vscode,linux,photoshop,premiere,typescript,javascript,figma" />
  </a>
</p>

Many thanks to the [**Chainlink**](https://chain.link/) team for organizing such an inspiring hackathon and for their unwavering support and guidance throughout the process.

We are truly grateful for their invaluable assistance, which has been instrumental in bringing our project to fruition.
The opportunity to leverage Chainlink's innovative technology has been a game-changer for us, and we appreciate the team's dedication to empowering developers like us to build exciting and groundbreaking projects.

Once again, thank you, Chainlink, for your exceptional support! We look forward to continuing to work with you and the broader community to push the boundaries of what's possible in the blockchain space. 🌐✨
