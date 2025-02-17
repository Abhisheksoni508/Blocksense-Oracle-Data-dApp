# Blocksense-Oracle-Data-dApp

**Blocksense Oracle Data dApp**

## Project Overview
The Blocksense Oracle Data dApp is a decentralized application designed to access and display real-time data from Blocksense's comprehensive catalogue of oracle data feeds. The application features seamless integration with smart contracts to retrieve and display accurate, real-time cryptocurrency prices and other data.

## Integration of Sponsor Technology
This project leverages Blocksense's oracle data infrastructure to retrieve accurate, real-time cryptocurrency prices. The smart contract is integrated with Blocksense’s oracle, ensuring efficient and reliable data retrieval.

## AI Tool Utilization
ChatGPT played a key role in the development process by assisting with documentation creation, code structuring, and troubleshooting. The AI was instrumental in optimizing development efficiency, and ensuring high-quality code and documentation.

## Project Structure
The project's directory structure is organized as follows:

```
blocksense-dapp/
├── node_modules/
├── package.json
├── package-lock.json
├── src/
│   ├── components/
│   └── ...
└── contracts/
    └── ...
```

## Codebase
**GitHub Repository:**

- EncodeLondon Hackathon Repository: [https://github.com/blocksense-network/EncodeLondon_Hackathon](https://github.com/blocksense-network/EncodeLondon_Hackathon)

## README Overview
The README file contains a comprehensive overview of the project, including:

- Installation and setup instructions
- Project structure breakdown
- Application functionality summary

## Setup Instructions

### Install Dependencies
Run the following command in the blocksense-dapp directory to install the required dependencies:
```sh
npm install
```

### Compile the Smart Contract
Use Hardhat to compile the smart contract with:
```sh
npx hardhat compile
```

### Deploy the Smart Contract
To deploy the contract locally, run:
```sh
npx hardhat run scripts/deploy.js --network localhost
```

### Run the React App
Start the frontend application with:
```sh
npm start
```

### Docker Compose Commands
Use Docker Compose to bring up and down the services as needed:

**To start the services:**
```sh
docker-compose up -d
```

**To stop the services:**
```sh
docker-compose down
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors
- Abhishek Soni

Feel free to reach out if you have any questions or need further assistance with the setup or usage of the dApp.
```` ▋
