# Blocksense-Oracle-Data-dApp

**Blocksense Oracle Data dApp**

**Project Overview:**
The Blocksense Oracle Data dApp is a decentralized application designed to access and display real-time data from Blocksense's comprehensive catalogue of oracle data feeds. The application features a user-friendly interface with functionalities such as real-time cryptocurrency price tracking, a dark mode toggle for enhanced user experience, and wallet connectivity to engage with blockchain networks seamlessly.

**Integration of Sponsor Technology:**
This project leverages Blocksense's oracle data infrastructure to retrieve accurate, real-time cryptocurrency prices. The smart contract is integrated with Blocksense’s oracle, ensuring efficient, secure, and reliable data delivery directly to the frontend interface.

**AI Tool Utilization:**
ChatGPT played a key role in the development process by assisting with documentation creation, code structuring, and troubleshooting. The AI was instrumental in optimizing development efficiency, generating technical explanations, and streamlining the overall application architecture.

**Project Structure**
The project's directory structure is organized as follows:

**perl
Copy
Edit
C:/Users/blocksense-dapp/
├── my-dapp/
├── node_modules/
├── package.json
└── package-lock.json**
The blocksense-dapp directory is distinct from the original EncodeLondon_Hackathon repository. The complete project source code can be accessed via the provided GitHub repository link.

**Codebase**
**GitHub Repository:**

EncodeLondon Hackathon Repository :**https://github.com/blocksense-network/EncodeLondon_Hackathon**

**README Overview:**
The README file contains a comprehensive overview of the project, including:

**Installation and setup instructions
Project structure breakdown**
Application functionality summary

**Setup Instructions
Install Dependencies:**
Run the following command in the blocksense-dapp directory to install the required dependencies:
npm install

**Compile the Smart Contract:**
Use Hardhat to compile the smart contract with:
npx hardhat compile

**Deploy the Smart Contract:**
To deploy the contract locally, run:
npx hardhat run scripts/deploy.js --network localhost

**Run the React App:**
Start the frontend application with:
npm start

**Docker Compose Commands:**
Use Docker Compose to bring up and down the services as needed:

**To start the services:**
docker-compose up -d

**To stop the services:**
docker-compose down

**https://github.com/blocksense-network/EncodeLondon_Hackathon**
