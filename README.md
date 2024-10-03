# DAOTown 🚀

Managing DAOs requires technical expertise, creating high entry barriers and inefficiencies. Our project aims to streamline DAO activities, including governance and tokenomics, through a decentralized infrastructure. By lowering these barriers, we enhance accessibility and efficiency, enabling broader participation and user-friendly DAO management for communities, organizations, and individuals.

## Tech Stack 🧰

- Solidity
- ethers.js
- Next.js
- React.js
- Foundry
- OpenZeppelin
- RainbowKit
- TypeScript
- JavaScript
- Chakra UI
- Lighthouse Storage (IPFS gateway)
- NeoX T4

## Foundry Setup 🚧

### Prerequisites

Before you begin, ensure you have the following installed:

- Follow the installation instructions in the [Foundry documentation](https://book.getfoundry.sh/).

For Windows users, it is recommended to use Windows Subsystem for Linux (WSL) for the Foundry setup.

### Getting Started

#### Cloning the Repository

1. Clone the DAOTown repository:

```bash
git clone https://github.com/AlexAnon88/DAOTown
```

2. Navigate to the `contracts/` directory:

```bash
cd DAOTown/contracts/
```

#### Setting Up Environment Variables

1. Create a file named `.env` in the contracts directory.

2. Configure the `.env` file according to the provided `.env.example` file.

#### Installing Dependencies

Install the necessary dependencies for the Foundry setup:

```bash
forge install
```

#### Building the Project

Build the project with the following command:

```bash
make build
```

#### Deployment

The Makefile is set up for deployment on NeoX T4 Testnet.

```bash
make deploy ARGS="--network neox"
```

## Frontend Setup 🚧

**Note:** Update the compiled ABIs of the contracts in the `/frontend/src/utils/abis/` directory.

1. From the root, navigate to the `frontend/` directory:

```bash
cd DAOTown/frontend/
```

2. Create a `.env` file in the root directory of the project:

```bash
touch .env
```

3. Refer to `.env.example` to update the `.env` file.

4. Install Dependencies:

```bash
yarn
```

5. Run the project at `localhost:3000`:

```bash
yarn run dev
```



<!-- ## Deployed & Verified contracts on NeoX Network -

- DAOManager.sol: [0x...](#)
- GovernanceToken.sol: [0x...](#)
- CreateGovernanceToken.sol: [0x...](#) -->
